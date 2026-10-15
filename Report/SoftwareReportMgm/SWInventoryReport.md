# Software Inventory

Through **Software Inventory** you may view all the installed applications on all managed devices or filter through the applications installed on managed devices, providing you with a quick way to periodically keep track of new applications installed and the devices they are installed on.

> **NOTE:** To export the information of a block click the **Export** button in that block, enter a filename, then click **OK**.

## Refetch Application

Click on **Refetch** to request agents to return an immediate update the list of installed applications on all managed devices, making sure all the information displayed is up to date.

![Software Inventory page showing the time period filters, the Application Information list and the Device List](../../IMG/5-1_p03-1_refetch.png)

## Filter newly installed applications

To quickly filter newly installed applications within a time period, click on the **Today**, **Last 7 Days**, **Last 14 Days**, **Last 30 Days**, **Last 90 Days** or **All** time period filters located on the left of the screen. This will help you in periodically reviewing the applications installed within a selected time period.

![Software Inventory page with the Last 30 Days filter selected and the matching applications listed](../../IMG/5-1_p03-2_filter-30-days.png)

## Search for applications using keywords

Entering keywords into the search bar will display all installed applications which contain the keywords entered, allowing you to pinpoint certain applications and help you keep track of the amount of devices these applications are installed on as well as view which devices the applications are installed on. You may also view the device information as well as view all applications on the device to make sure your application information is correct.

1. Enter the keywords you wish to search for using the following methods:

    - Directly entering the keywords

        Enter the keyword(s) you wish to search with into the search bar and press `<Enter>`. Click on ![Search operator toggle icon](../../IMG/icon-search-mode_02.png) to toggle between searching with the **AND** operator or **OR** operator. Searching using **AND** will search for items which contain all keywords entered, whilst searching using **OR** will search for items which contain at least one of the keywords entered.

        ![Software Inventory page with the search bar and the AND / OR toggle highlighted](../../IMG/5-1_p04-1_search-bar.png)

    - Importing multiple keywords from a .csv file

        - **a.** Click on ![Search condition icon](../../IMG/icon-expand_03.png) to bring up the search condition pop-up window.

            ![Software Inventory page with the search condition icon highlighted next to the search bar](../../IMG/5-1_p05-1_search-condition-open.png)

        - **b.** Select the operator you wish to use. **AND** will search for items which contain all the keywords entered, whilst **OR** will search for items which contain at least one of the keywords entered.

            ![Search with AND operator pop-up with the Operator buttons highlighted and the keywords Office and Licensing](../../IMG/5-1_p05-2_search-operator.png)

        - **c.** Enter the keyword(s) you wish to search with into the **Keywords** field and press `<Enter>`.

            ![Search with AND operator pop-up with the Keywords field highlighted](../../IMG/5-1_p06-1_search-keywords.png)

            Import multiple keywords using a .csv file by click on **Import**, selecting the .csv file you wish to import, and then selecting the column in the .csv file you would like to import.

            ![Search condition pop-up with the Import button highlighted and a file open dialog with a CSV file selected](../../IMG/5-1_p06-2_import-csv.png)

            ![Import pop-up for selecting the field to import from the CSV file, with the field drop-down highlighted](../../IMG/5-1_p06-3_import-field.png)

        - **d.** Click on **Save** once you have finished setting the search conditions.

            ![Search with AND operator pop-up with the Save button highlighted](../../IMG/5-1_p07-1_search-save.png)

2. If you wish to view the devices an application is installed on, check the application, then click on **Show Device**. The list of devices the selected application is installed on should be displayed in the **Device List** window

    ![Software Inventory page with an application checked, the Show Device button highlighted and the Device List below](../../IMG/5-1_p07-2_show-device.png)

3. (optional) Clicking on ![Device Information icon](../../IMG/icon-list_04.png) next to each device in the **Device List** will allow you to view the Device Information.

    ![Device Information page of a managed device with the Hardware Sensor, Utilization, Inventory, BMC, Software, Event Log, BIOS, Security and Configuration tiles](../../IMG/5-1_p08-1_device-info.png)

4. (optional) Clicking on the device will display all applications on the selected device.

    ![Pop-up listing all applications installed on the selected device](../../IMG/5-1_p08-2_device-applications.png)
