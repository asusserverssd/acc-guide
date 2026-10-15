# Security Configuration

> **NOTE:** This function is only available for Windows® OS managed devices.

The **Security Configuration** allows you to set a password as a method to prevent users from removing the agents themselves. This enables a more centralized control over all managed Windows® devices.

This password is separate from the agent uninstall password on individual devices (**Device Information** > **Configuration**), and setting this password will not override the individual agent uninstall passwords.

To access **Security Configuration**, click ![Options icon](../../IMG/icon-options_02.png) in the left menu, then click on **Security Configuration**.

![Security Configuration page showing the Agent Uninstall Password block and the BIOS Setting Password block](../../IMG/8-4_p10-1_security-config-page.png)

## Agent Uninstall Password

### Setting a new password

1. Toggle the slider to bring up the pop-up window to set the Administrator’s Agent Uninstall Password.

    ![Slider at the top right of the Agent Uninstall Password block highlighted](../../IMG/8-4-1_p11-1_uninstall-pwd-toggle.png)

2. Enter the password you wish to set as the Administrator’s Agent Uninstall Password, then click **Save** to set the new password.

    ![Agent Uninstall Password pop-up with the password field and the Save button highlighted](../../IMG/8-4-1_p11-2_uninstall-pwd-dialog.png)

### Editing the password

Click on the **Update** button, then re-enter your new password and click on **Save** to save your new password.

![Update button highlighted in the Agent Uninstall Password block](../../IMG/8-4-1_p12-1_uninstall-pwd-update.png)

### Disabling the password

Click on the button located at the top right to disable the Administrator’s Agent Uninstall Password.

![Slider at the top right of the Agent Uninstall Password block highlighted to disable the password](../../IMG/8-4-1_p12-2_uninstall-pwd-disable.png)

## BIOS Setting Password

When an agent is installed onto a device without a BIOS password, ASUS Control Center will automatically enable BIOS Password Protection and set a BIOS password that meets complexity requirements. In such cases, the client’s BIOS password protection status will be defined as “ACC Protected”.

BIOS Password Protection cannot be automatically enabled if the device has an existing BIOS password. In such cases, the client’s BIOS password protection status will be defined as “Manually Protected”.

### Viewing the BIOS password protection status

Click **Support List** to view the BIOS password protection status for all devices.

![Support List button highlighted in the BIOS Setting Password block](../../IMG/8-4-2_p13-1_bios-pwd-support-list-button.png)

![BIOS Setting Password support list window showing devices grouped as ACC Protected and Manually Protected](../../IMG/8-4-2_p13-2_bios-pwd-support-list.png)

### Updating ACC Protected BIOS passwords

Click on the **Update** button to open a list of ACC Protected devices, then click **Update** in the popup window to update the BIOS password.

![Update button highlighted in the BIOS Setting Password block](../../IMG/8-4-2_p14-1_bios-pwd-update-button.png)

![Pop-up listing the ACC Protected devices with the Update button highlighted](../../IMG/8-4-2_p14-2_bios-pwd-update-dialog.png)

### Updating manually protected BIOS passwords

1. Click **Please update it here** to open a list of manually protected devices.

    ![Please update it here link highlighted in the BIOS Setting Password block](../../IMG/8-4-2_p15-1_bios-pwd-manual-link.png)

2. Enter the device’s existing BIOS password, then click **Update** to update the BIOS password. BIOS Password Protection will automatically be enabled and the device’s status will change to “ACC Protected”.

    > **NOTE:** For security reasons, the existing BIOS password is required to make any changes. This protects the client devices from malicious attacks that may compromise the BIOS.

    ![Pop-up listing the manually protected devices with the existing BIOS password field and the Update button highlighted](../../IMG/8-4-2_p15-2_bios-pwd-manual-dialog.png)
