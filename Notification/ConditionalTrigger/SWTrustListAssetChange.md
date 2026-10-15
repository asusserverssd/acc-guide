# Trust Software Asset

This function allows you to send notifications when the following events occur:

- Applications not in the Trust Software Asset are installed on managed devices

These notifications will be sent immediately to the owner of the managed device and their superior. Below is an example of a notification sent when an application not in the Trust Software Asset is installed on the managed device.

![Example notification email titled Trust Software Asset, listing the host name, logon user, IP address, and the installed applications that are not on the Trust Software Asset](../../IMG/6-1_p03-1_trust-notification-example.png)

To enable Trust Software Asset:

1. Click on the button to configure and enable Software Asset Changes notifications.

    ![Slider highlighted in the Software Asset Changes block of the Trust Software Asset page](../../IMG/6-1_p03-2_trust-toggle.png)

2. Select softwares from the software list to be applied as a Trust Software Asset. Notifications will be sent when new software is installed on managed devices which do not appear on the Trust Software Asset.

    > **NOTE:** For more information on Software List, please refer to the **Software List** section of this manual.

3. Select the Compare feature fields **Software Name** and **Publisher**, as these two compare feature fields are required. **Version** and **Installed Date** are optional.
4. Enter the recipients of the notification email.
5. Click on **Save** after composing the title and content of the notification email.

    > **NOTE:** Ensure SMTP settings have been set and that a test email can be successfully sent to ensure notifications can be properly sent and received. For more information on SMTP settings and sending a test email, please refer to the **SMTP Settings** section.

    ![Trust Software Asset settings page with the software list, compare feature fields, recipients, and mail title and content highlighted, and the Save button highlighted](../../IMG/6-1_p04-1_trust-settings.png)
