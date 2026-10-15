# Service Report

**Service Report** allows you to view the services currently running on all managed devices, and also allows you to view the managed devices running a specific service.

> **NOTE:** To export the information of a block click the **Export** button in that block, enter a filename, then click **OK**.

![Service Report page with the Service Information list and the Device List](../../IMG/5-1_p15-1_service-page.png)

## Search for services using keywords

Entering keywords into the search bar will display all services which contain the keywords entered, allowing you to pinpoint certain services and help you keep track of the amount of devices these services are available on as well as view these devices.

1. Enter the keywords you wish to search for using the following methods:

    - Directly entering the keywords

        Enter the keyword(s) you wish to search with into the search bar and press `<Enter>`. Click on ![Search operator toggle icon](../../IMG/icon-search-mode_02.png) to toggle between searching with the **AND** operator or **OR** operator. Searching using **AND** will search for items which contain all keywords entered, whilst searching using **OR** will search for items which contain at least one of the keywords entered.

        ![Service Report page with the search bar and the AND / OR toggle highlighted](../../IMG/5-1_p16-1_service-search-bar.png)

    - Importing multiple keywords from a .csv file

        - **a.** Click on ![Search condition icon](../../IMG/icon-edit-box.png) to bring up the search condition pop-up window.

            ![Service Report page with the search condition icon highlighted next to the search bar](../../IMG/5-1_p17-1_service-search-condition-open.png)

        - **b.** Select the operator you wish to use. **AND** will search for items which contain all the keywords entered, whilst **OR** will search for items which contain at least one of the keywords entered.

            ![Search with OR operator pop-up with the Operator buttons and the Full string compare switch](../../IMG/5-1_p17-2_service-search-operator.png)

        - **c.** Enter the keyword(s) you wish to search with into the **Keywords** field and press `<Enter>`.

            ![Search with OR operator pop-up with the Keywords field highlighted](../../IMG/5-1_p18-1_service-search-keywords.png)

            Import multiple keywords using a .csv file by click on **Import**, selecting the .csv file you wish to import, and then selecting the column in the .csv file you would like to import.

            ![Search with OR operator pop-up with the Import button highlighted](../../IMG/5-1_p18-2_service-import-csv.png)

            ![Import pop-up for selecting the field to import from the CSV file, with the field drop-down highlighted](../../IMG/5-1_p18-3_service-import-field.png)

        - **d.** Click on **Save** once you have finished setting the search conditions.

            ![Search with OR operator pop-up with the Save button highlighted](../../IMG/5-1_p19-1_service-search-save.png)

2. If you wish to view the devices a service is available on, check the service, then click on **Show Device**. The list of devices the selected service is available on should be displayed in the **Device List** window.

    > **NOTE:** You can also click on ![Deselect filter icon](../../IMG/icon-deselect.png) to quickly deselect services already selected.

    ![Service Report with a service checked, the Show Device button highlighted and the matching devices in the Device List](../../IMG/5-1_p19-2_service-show-device.png)

3. (optional) You may filter through the devices by clicking on the tags next to the Device List title, or filter by **Installed** or **Not Installed** by clicking on the drop down menu next to the search bar.

    ![Device List with the Installed and Not Installed drop-down menu highlighted](../../IMG/5-1_p20-1_service-device-filter.png)

4. (optional) Clicking on ![Device Information icon](../../IMG/icon-list_04.png) next to each device in the **Device List** will allow you to view all services on the selected device.

    ![Pop-up listing all services on the selected device](../../IMG/5-1_p20-2_service-list-on-device.png)

## Starting, stopping or restarting a service

You can start, stop, or restart a selected service on a device by selecting the device in the Device List and clicking on the **Action** drop down menu to select your action.

![Device List with the Action drop-down menu open showing the Stop, Start and Restart options](../../IMG/5-1_p21-1_service-action.png)

Starting, stopping or restarting the service may take up to two minutes to be completed. Once the process is completed, check if the count is correct, if not, you can click the **Refetch** button to refetch the service information.
