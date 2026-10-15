# Initialize settings

Once your ASUS Control Center is installed successfully, you will need to initialize the ASUS Control Center settings such as time zone, account and password, and network settings.

## Initialize startup settings

Once ASUS Control Center has launched, follow the steps below to initialize startup settings:

> **NOTE:** The information entered in this section is for reference only.

1. Read through the end user license agreement, check **I accept**, then click **Next**.

    ![Terms of Use page of the ASUS Control Center welcome wizard with the I accept checkbox and the Next button](../IMG/1-3_p08-1_init-eula.png)

2. Carefully read through the Privacy Policy, check **I accept**, then click **Next**.

    ![Privacy Policy page of the welcome wizard with the I accept checkbox and the Next button](../IMG/1-3_p08-2_init-privacy.png)

3. Enter the **Company Name**, then select the **Time Zone**. Click on **Next** once you are finished.

    > **NOTE:** When setting the **Time Zone**, ensure that the time zone selected matches the time zone displayed on the physical device which has a hypervisor installed.

    ![General Setting page of the welcome wizard with the Company Name and Time zone fields](../IMG/1-3_p09-1_init-general-setting.png)

4. Enter and initialize the password, then click **Next**.

    > **NOTE:**
    >
    > - The default ASUS Control Center administrator account is **Administrator**.
    > - Your password should contain at least 8 characters, and consist of at least one lower case letter, one upper case letter, one digit, and a special character.

    ![Set up the Password page of the welcome wizard showing the Administrator account and the Password and Confirm Password fields](../IMG/1-3_p09-2_init-password.png)

5. Confirm if the LAN cable is plugged into the correct LAN port, then click **Next**.

    ![Confirm Network Interface page of the welcome wizard showing a photo of the device rear panel with LAN 1 marked in red](../IMG/1-3_p10-1_init-lan-port.png)

6. Set the network configurations and Host Name, then click **Submit** once you are finished with all the settings.

    > **NOTE:** If **Static** is selected, the IP Address and Subnet Mask should be filled in manually. If **DHCP** is selected, the IP Address and Subnet Mask will automatically be filled in.

    ![Set up the Network page of the welcome wizard with the Host Name, Address Assignment, IP Address, Subnet Mask, Default Gateway, and DNS fields and the Submit button](../IMG/1-3_p10-2_init-network.png)

## Logging into ASUS Control Center

![Diagram of a computer using a web browser as the management console, connected by a dashed line to the central server running ASUS Control Center](../IMG/1-3_p11-1_login-overview.png)

To log into ASUS Control Center:

1. Open a web browser and navigate to the main server URL:

    | Type | URL format |
    | --- | --- |
    | **Connecting using a hostname** | `https://<hostname>/ACC`<br>Example: `https://ACC-TUTOR/ACC` |
    | **Connecting using an IP address** | `https://<IP address>/ACC`<br>Example: `https://10.10.75.200/ACC` |

    > **NOTE:**
    >
    > - The *ACC* portion of the URL is case sensitive.
    > - Replace "ACC-TUTOR" or "10.10.75.200" with the correct hostname or IP address for your server environment.
    > - To connect via the HTTP protocol (less secure), replace "https://" with "http://" in the URL.
    > - File export and import functionality is disabled when using ACC through a virtual machine. For the optimal experience, connect using an Internet browser installed on the host system.

2. Enter your **Account** and **Password**, then click **Login** to log into ASUS Control Center.
3. If Multi-Factor Authentication (MFA) is enabled, enter the 6-digit passcode displayed in your authenticator app.

    > **NOTE:** Refer to the **Enabling Multi-Factor Authentication** section of the **Account Management** chapter for more information.

4. Activate or import a license key.

    > **NOTE:** Refer to the **Activating/Importing a License Key** section of the **License** chapter for more information.
