# DBExpose Configuration

The **DBExpose Configuration** allows you to set an account and password which allows users to use third-party software, such as MySQL Workbench to access data on ASUS Control Center, such as device information or metadata. This information is read-only and cannot be edited.

To access **DBExpose Configuration**, click ![Options icon](../../IMG/icon-options_02.png) in the left menu, then click on **DBExpose Configuration**.

![DBExpose Configuration page with the slider at the top right turned off](../../IMG/8-8_p32-1_dbexpose-page.png)

## To set the DBExpose account and password

1. Click on the slide button on the top right of the main screen.

    ![Slider at the top right of the DBExpose Configuration block highlighted](../../IMG/8-8_p32-2_dbexpose-toggle.png)

2. Enter an account and password, then enter a port (between 7000-7999) which is not being used. Once you have finished entered the required fields, click on **Save**.

    ![DBExpose Configuration pop-up with the Account, Password, and Port fields and the Save button highlighted](../../IMG/8-8_p33-1_dbexpose-dialog.png)

## To edit the DBExpose account information

Edit the account, password, and port information then click on **Update** to save the changes made.

![DBExpose Configuration page with the account details shown and the Update button highlighted](../../IMG/8-8_p33-2_dbexpose-update.png)

![Message stating that the DBExpose account has been updated](../../IMG/8-8_p33-3_dbexpose-updated-message.png)

## To delete the DBExpose account information

Click on the slide button on the top right to disable and delete the DBExposure Configuration settings.

![Slider at the top right of the DBExpose Configuration block highlighted to disable and delete the settings](../../IMG/8-8_p34-1_dbexpose-disable.png)

![Message stating that the DBExpose account has been removed](../../IMG/8-8_p34-2_dbexpose-removed-message.png)

## Access ASUS Control Center with third-party software

> **NOTE:** The example in this section is for reference only.

You can use a third-party software such as **MySQL Workbench** to access information such as the metadata and device information of your ASUS Control Center.

1. Load MySQL Workbench, then set up a new connection and enter the required information.
2. Enter the ip and port of the ASUS Control Center server into the **Hostname** and **Port** field.
3. Next, enter the DBExposure account created into the **Username** field.
4. Click on **Store in Vault...** then enter the DBExposure password you created into the password field and click **OK**.

    ![MySQL Workbench Setup New Connection window with the connection name, hostname, port, and username fields highlighted, and the Store in Vault password window open](../../IMG/8-8_p35-1_mysql-new-connection.png)

5. Click on **Test Connection** to test if the connection to ASUS Control Center was successfully created.

    ![MySQL Workbench Test Connection button highlighted and a message confirming that the connection was made successfully](../../IMG/8-8_p36-1_mysql-test-connection.png)

6. Save the connection settings, now when using MySQL Workbench, you should be able to access some of the data on ASUS Control Center.

    > **NOTE:** The screenshot below is an example of accessing the metadata of ASUS Control Center.

    ![MySQL Workbench showing the ASUS Control Center client metadata table returned by a query](../../IMG/8-8_p36-2_mysql-metadata-query.png)
