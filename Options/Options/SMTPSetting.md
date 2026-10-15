# SMTP Settings

> **NOTE:** The information entered in this section is for reference only.

Set up the SMTP (Simple Mail Transfer Protocol) for ASUS Control Center to allow feedback on system failures and alerts to be sent via email to the system administrator.

To access **Software Report**, click ![Notification icon](../../IMG/icon-notification_03.png) in the left menu, then click on **SMTP Settings**.

![SMTP Settings page showing the Display Name, SMTP Server, SMTP Port, Sender Address, Sender Password, Enable SSL, and Send From fields](../../IMG/8-5_p16-1_smtp-page.png)

## To set up the SMTP Server:

1. Fill in or check the following fields:

    | Item | Description |
    | --- | --- |
    | **Display Name** | The name of this SMTP setting. The display name will not appear on sent emails. |
    | **SMTP Server** | The SMTP server responsible for collecting and sending emails |
    | **SMTP Port** | Service port for SMTP. Common ports used are 25 (SMTP former default port), 465 (encrypted SMTP), and 587 (new SMTP default) |
    | **Sender Address** | The email of the ACC notification sender. This email address must exist within the SMTP Server service |
    | **Sender Password** | The password for the ACC notification email sender |
    | **Enable SSL** | Enables mail sent or forwarded through this SMTP server are SSL encrypted |
    | **Send by Server**\* | When there are issues with managed devices whilst within the same domain as ACC, ACC will send emails using the SMTP server |
    | **Send by Client**\* | When there are issues with managed devices whilst not in the same domain as ACC, the managed device will send emails using the SMTP server |

    > **NOTE:** Refer to the flow chart for more details on the difference between Send by Server and Send by Client.

    ![Send From options on the SMTP Settings page, each linked to a flow chart. With Send by Server, the managed device reports to ASUS Control Center, which sends the email through the SMTP server. With Send by Client, the managed device sends the email directly through the SMTP server.](../../IMG/8-5_p17-1_smtp-send-flow.png)

2. (optional) Click on **Send Test Mail**, then enter an email and click **Send** to receive the test mail to check the status of the SMTP. If the SMTP is functioning properly, you should receive an email.

    ![Send Test Mail pop-up with the email address field and the Send button highlighted](../../IMG/8-5_p18-1_smtp-test-mail-dialog.png)

    ![Example of the SMTP test mail received in an email inbox](../../IMG/8-5_p18-2_smtp-test-mail-received.png)

3. Click **Save** to save the changes made.

    ![Confirmation message after saving the SMTP settings, with the Save button highlighted](../../IMG/8-5_p19-1_smtp-saved.png)
