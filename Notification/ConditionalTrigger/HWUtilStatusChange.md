# Hardware & Utilization

**Hardware & Utilization** allows you to add or delete rules on notifications. When a managed device's hardware sensor or utilization status changes to one that you have set a notification for, a notification will be sent to the system administrator. Below is an example of a notification sent when the CPU status of a managed device changes from **Normal** to **LowCritical**.

![Example notification email showing the basic information of the device and a CPU Core sensor with the status LowCritical](../../IMG/6-1_p09-1_hwutil-notification-example.png)

## Adding a new rule

1. Click **Add**.

    ![Rule Management page showing the empty Rule List, Notify Host List, Monitor Hardware Sensor List, and Monitor Utilization List, with the Add button highlighted](../../IMG/6-1_p10-1_hwutil-rule-list.png)

2. Enter a rule name, then select the devices to apply the rule to. Click **Next**.

    ![Add Rule window at Step 1 with the Rule Name field and a selected host highlighted, and the Next button highlighted](../../IMG/6-1_p10-2_rule-step1.png)

3. Select conditions (type and status of hardware sensors or utilization) to send notifications, then click **Next**.

    > **NOTE:**
    >
    > - The checkbox checked when selecting the hardware sensor or utilization type and status will send notifications when the status shifts from the other two statuses to the status checked. For example, checking **Normal** will send notifications when the status changes from **Warning** or **Critical** to **Normal**.
    > - To set the status thresholds for the Utilization Type, please refer to the **Utilization** section.

    ![Add Rule window at Step 2 with the hardware sensor and utilization types and statuses highlighted, and the Next button](../../IMG/6-1_p11-1_rule-step2.png)

4. Select the notification method between the following options (multiple notification methods may be selected):

    - Event Log

        The notification will be displayed on the device's event log and system overview.

        ![Add Rule window at Step 3 with the Event Log notification method highlighted](../../IMG/6-1_p12-1_rule-notify-eventlog.png)

    - SNMP Trap

        The notification is recorded in the SNMP Trap Receiver, ensure to enter the corresponding information into the **Community** and **Receiver's IP address** fields.

        ![Add Rule window at Step 3 with the SNMP Trap notification method, including the Community and Receiver's IP address fields, highlighted](../../IMG/6-1_p13-1_rule-notify-snmp.png)

    - Email

        The notification is sent to the entered email addresses of the IT department as well as all people associated with the device.

        > **NOTE:**
        >
        > - Ensure to set up the SMTP server settings before using the email function. For more information please refer to the **SMTP Settings** section.
        > - When entering multiple emails, use a semicolon '**;**' to separate the emails.

        ![Add Rule window at Step 3 with the Email notification method highlighted](../../IMG/6-1_p14-1_rule-notify-email.png)

5. Click on **Save** after finished selecting your notification method(s).

    ![Add Rule window at Step 3 with the Save button highlighted](../../IMG/6-1_p15-1_rule-save.png)

    Your newly added rule should appear in the main Hardware & Utilization screen, under **Rule List**, this displays the rule name and details of your selected notification method. Clicking on the newly added rule will display the devices associated with the rule in the **Notify List**, and the list of hardware and utilizations being monitored in the **Monitor Hardware Sensor List** and **Monitor Utilization List**.

    > **NOTE:** Ensure SMTP settings have been set and that a test email can be successfully sent to ensure notifications can be properly sent and received. For more information on SMTP settings and sending a test email, please refer to the **SMTP Settings** section.

    ![Hardware & Utilization page with the newly added rule in the Rule List, and the Notify List, Monitor Hardware Sensor List and Monitor Utilization List below](../../IMG/6-1_p16-1_rule-list-result.png)

## Editing an existing rule

1. Click on ![Edit icon](../../IMG/icon-edit_01.png) next to the rule you wish to edit.

    ![Edit icon highlighted next to a rule in the Rule List](../../IMG/6-1_p17-1_edit-rule-icon.png)

2. You can edit the rule name and select the hosts to apply the rule to. Click **Next**.

    ![Edit Rule step 1 showing the rule name and the selected hosts](../../IMG/6-1_p17-2_edit-step1.png)

3. Select conditions (type and status of hardware sensors or utilization) to send notifications, then click **Next**.

    > **NOTE:**
    >
    > - The checkbox checked when selecting the hardware sensor or utilization type and status will send notifications when the status shifts from the other two statuses to the status checked. For example, checking **Normal** will send notifications when the status changes from **Warning** or **Critical** to **Normal**.
    > - To set the status thresholds for the Utilization Type, please refer to the **Utilization** section.

    ![Edit Rule step 2 for selecting hardware sensor and utilization conditions](../../IMG/6-1_p18-1_edit-step2.png)

4. Select the notification method (multiple notification methods may be selected).

    > **NOTE:** For more details on the notification methods, please refer to the **Adding a new rule** section.

    ![Edit Rule step 3 for selecting notification methods, with the Update button highlighted](../../IMG/6-1_p19-1_edit-step3.png)

5. Click on **Update** once you have finished editing the rule.

## Deleting a notification rule

1. Click on ![Delete icon](../../IMG/icon-delete_02.png) next to the rule you wish to delete.

    ![Delete icon highlighted next to a rule in the Rule List](../../IMG/6-1_p20-1_delete-rule-icon.png)

2. Click **Next**, then **Next** again until you reach the following window, then click **Delete**.

    ![Edit Rule final step with the Delete button highlighted](../../IMG/6-1_p20-2_delete-step3.png)

3. Click **Delete** on the pop up window to delete the rule.

    ![Delete Rule confirmation pop-up with the Delete button highlighted](../../IMG/6-1_p21-1_delete-confirm.png)
