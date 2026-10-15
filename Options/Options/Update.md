# Update

The **Update Task** screen will display available updates for the Linux Agent, Windows Agent, and Main Server, you may manually refresh the updates screen by clicking on **Check for updates**.

> **NOTE:**
>
> - Ensure to add asuscontrolcenter.asus.com/* to your firewall exceptions list to enable update checks.
> - Ensure you have a stable Internet connection.

![Update Task page showing the Update Information blocks for the Linux Agent, Main Server, and Windows Agent, the Available Agent Devices list, and the Check for updates button highlighted](../../IMG/8-9_p37-1_update-page.png)

## Updating ASUS Control Center main server

1. When an update is available for the main server, it will be displayed under **Update Information** and the **Main Server** block will be displayed in green. Click on ![Download icon](../../IMG/icon-download.png) in the **Main Server** block to download the update files.

    ![Main Server block displayed in green with its download button highlighted](../../IMG/8-9_p38-1_update-main-download.png)

2. Once the update files are successfully downloaded, the **Main Server** block should be displayed in orange. Now click on ![Update icon](../../IMG/icon-update.png) to update the ASUS Control Center main server. You will also be logged out of ASUS Control Center when the main server is updating.

    ![Main Server block displayed in orange with its update button highlighted](../../IMG/8-9_p38-2_update-main-install.png)

3. Log into ASUS Control Center again after the update is completed.

## Updating Windows and Linux agents

1. When an update is available for Linux and/or Windows Agents it will be displayed under **Update Information**, and the **Linux Agent** and/or **Windows Agent** block will be displayed in green.
2. Click on ![Download icon](../../IMG/icon-download.png) in the **Linux Agent** and/or **Windows Agent** block to download the agent. Once the download is complete, the **Linux Agent** and/or **Windows Agent** block will be displayed in blue.
3. Select the device(s) you wish to update agents for in the **Available Agent Devices** list.
4. Click on **Update**.

    ![Linux Agent and Windows Agent blocks with their download buttons highlighted, devices selected in the Available Agent Devices list, and the Update button highlighted](../../IMG/8-9_p39-1_update-agents.png)

5. Click **Update** on the confirmation pop-up window to start the update process.

    > **NOTE:** You do not need to uninstall the agents on the selected devices before updating.

    ![Update Task confirmation pop-up listing the selected devices, with the Update button](../../IMG/8-9_p40-1_update-agents-confirm.png)

6. After the agent updates have been completed, you will be redirected to the Agent Update Report screen.

    > **NOTE:** For more details on the Agent Update Report, refer to the **Agent Update Report** section.

    ![Agent Update Report page showing the number of successful, failed, and processing updates, the completion rate, and the device list](../../IMG/8-9_p41-1_update-report.png)
