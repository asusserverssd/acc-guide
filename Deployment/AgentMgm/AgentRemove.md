# Remove Agents

The **Remove Agents** function will allow you to remove agents installed on managed devices using ASUS Control Center, or allow you to remove the managed devices from ASUS Control Center after you remove the clients manually from the managed devices.

![Remove Agents page dimmed behind a confirmation pop-up listing the devices to remove agents from, with the Cancel and Remove buttons](../../IMG/3-1_p19-1_remove-agents-confirm.png)

## Remove agents using ASUS Control Center

1. Check the devices you wish to remove agents from on the list.

    ![Remove Agents page with managed devices checked in the list](../../IMG/3-1_p19-2_remove-agents-page.png)

2. A pop-up window should appear, displaying the devices you wish to remove agents from. After confirming the correct managed devices are selected, click on **Remove**, then click on **OK**.

    > **NOTE:** If the target host(s) are offline, the agents on these host(s) will be removed once the host(s) are online.

    ![Deployment Management pop-up listing the devices to remove agents from, with the Remove button](../../IMG/3-1_p20-1_remove-confirm-list.png)

    ![Deployment Management pop-up stating the agent will be removed once the target host is online, with the OK button highlighted](../../IMG/3-1_p20-2_remove-ok.png)

## Remove Windows Agent from local device

You may choose to remove Agents from Windows systems manually.

1. To remove the Windows Agent manually on a managed device, click on **Control Panel > Programs and Features**.

    ![Windows Programs and Features window listing installed programs including ACC Windows Agent](../../IMG/3-1_p21-1_programs-features.png)

2. Select and uninstall **ACC Windows Agent** from the list of programs.

    ![Programs and Features with ACC Windows Agent selected and the Uninstall option highlighted](../../IMG/3-1_p21-2_uninstall-agent.png)

3. Ensure the applications shown in the pop-up window are closed, or you can check the **Automatically close applications and attempt to restart them after setup is complete** checkbox, then click **OK** to continue with the uninstallation process.

    ![ACC Windows Agent pop-up listing applications to close, with the automatically close applications option and the OK button highlighted](../../IMG/3-1_p22-1_close-apps.png)

4. Once **ACC Windows Agent** is uninstalled on the managed device, please navigate to the **Remove Agents** menu of your ASUS Control Center (**Deployment** > **Agent Management** > **Remove Agents**).
5. Select the managed device which you manually removed the agent from, the connection status for that managed device should be **Offline**, then click on **Remove** to remove the managed device from ASUS Control Center.

    ![Remove Agents page with the offline managed device selected and the Remove button highlighted](../../IMG/3-1_p22-2_remove-offline-device.png)

6. A pop-up window should appear, displaying the managed devices you wish to remove agents from. After confirming the correct devices are selected, click on **Remove**, then click on **OK**.

    ![Deployment Management pop-up listing the device to remove, with the Remove button](../../IMG/3-1_p23-1_remove-confirm-win.png)

    ![Deployment Management pop-up stating the agent will be removed once the target host is online, with the OK button highlighted](../../IMG/3-1_p23-2_remove-ok-win.png)

## Remove Linux Agent from local device

You may choose to remove Linux Agents from Linux systems manually.

1. (optional) If you are using a Windows OS, you may use a third-party SSH or telnet client such as PuTTY to connect to the managed Linux device.

    For this example we will be using PuTTY to log on to the managed Linux device and remove the Linux Agent.

    ![PuTTY Configuration window with the host name or IP address and the SSH connection type](../../IMG/3-1_p24-1_putty.png)

2. Enter the root account and password of the client Linux device.
3. Once you've logged in, execute `bash /root/uninstall.sh` to remove the Linux Agent from the managed device.
4. Once the Linux Agent is removed on the managed device, please navigate to the **Remove Agents** menu of your ASUS Control Center (**Deployment** > **Agent Management** > **Remove Agents**).
5. Select the managed device which you manually removed the agent from, the connection status for that managed device should be **Offline**, then click on **Remove** to remove the managed device from ASUS Control Center.

    ![Remove Agents page with the offline Linux managed device selected and the Remove button highlighted](../../IMG/3-1_p25-1_remove-offline-linux.png)

6. A pop-up window should appear, displaying the devices you wish to remove agents from. After confirming the correct devices are selected, click on **Remove**, then click on **OK**.

    ![Deployment Management pop-up listing the Linux device to remove, with the Remove button](../../IMG/3-1_p26-1_remove-confirm-linux.png)

    ![Deployment Management pop-up stating the agent will be removed once the target host is online, with the OK button highlighted](../../IMG/3-1_p26-2_remove-ok-linux.png)
