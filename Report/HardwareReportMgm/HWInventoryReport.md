# Hardware Inventory

**Hardware Inventory** allows you to view the count for models, displays, processor, memory, or storage hardware components of all managed devices or filter through managed devices or hardware component.

Checking a component, then clicking on the **Show Device** button will display devices which have the selected components in the **Devices List**, allowing you to quickly locate managed devices with expensive hardware components or components which need to be replaced.

> **NOTE:** To export the information of a block click the **Export** button in that block, enter a filename, then click **OK**.

![Hardware Inventory page with the Model component list, the Show Device button and the Device List](../../IMG/5-2_p27-1_hw-inventory-model.png)

## View Model component type and count

![Hardware Inventory page with the Model category selected and the component list highlighted](../../IMG/5-2_p27-2_hw-model-view.png)

## View Display component type and count

![Hardware Inventory page with the Display category selected and the component list highlighted](../../IMG/5-2_p28-1_hw-display-view.png)

## View Processor component type and count

![Hardware Inventory page with the Processor category selected and the component list highlighted](../../IMG/5-2_p28-2_hw-processor-view.png)

## View Memory component type and count

![Hardware Inventory page with the Memory category selected and the component list highlighted](../../IMG/5-2_p28-3_hw-memory-view.png)

## View Storage component type and count

![Hardware Inventory page with the Storage category selected and the component list highlighted](../../IMG/5-2_p29-1_hw-storage-view.png)

## Refetch hardware component

Click on **Refetch** to request agents to return an immediate update the list of Model, Processor, Memory, or Storage components of all managed devices depending on the component category selected, making sure all hardware components, including newly added hardware components are counted for.

![Hardware Inventory page with the Refetch button highlighted](../../IMG/5-2_p29-2_hw-refetch.png)

## Filter by component name

You can filter the components by the selected components.

1. Check the components you want to filter by then click on ![Filter button](../../IMG/icon-filter.png).

    ![Hardware Inventory Processor list with a component checked and the filter button highlighted](../../IMG/5-2_p30-1_hw-filter-select.png)

2. Confirm that the components displayed match the ones you checked, then click **Update**.

    ![Hardware Inventory pop-up listing the selected components, with the Update button highlighted](../../IMG/5-2_p30-2_hw-filter-confirm.png)

3. The component list should only display the selected components.

## Search for components using keywords

Entering keywords into the search bar will display all components which contain the keywords entered, allowing you to pinpoint certain hardware components and help you keep track of the amount of devices these hardware components are installed on.

1. Enter the keywords you wish to search for using the following methods:

    - Directly entering the keywords

        Enter the keyword(s) you wish to search with into the search bar and press `<Enter>`. Click on ![Search operator toggle icon](../../IMG/icon-search-mode_01.png) to toggle between searching with **Search with 'AND' operator** or **Search with 'OR' operator**. **Search with 'AND' operator** will search for items which contain all keywords entered, whilst **Search with 'OR' operator** will search for items which contain at least one of the keywords entered.

        Checking the **Full string compare** option will only return search results of items which have a string with an exact match to the keywords, and can be applied to any of the above search operators selected.

        ![Hardware Inventory search bar with the operator drop-down open showing Search with AND operator, Search with OR operator and Full string compare](../../IMG/5-2_p31-1_hw-search-operator.png)

    - Importing multiple keywords from a .csv file

        - **a.** Click on ![Search condition icon](../../IMG/icon-edit-small.png) to bring up the search condition pop-up window.

            ![Hardware Inventory page with the search condition icon highlighted next to the search bar](../../IMG/5-2_p32-1_hw-search-condition-open.png)

        - **b.** Select the operator you wish to use. **AND** will search for items which contain all the keywords entered, whilst **OR** will search for items which contain at least one of the keywords entered.

            Enabling the **Full string compare** option will only return search results of items which have a string with an exact match to the keywords, and can be applied to any of the above search operators selected.

            ![Search with OR operator pop-up with the Operator buttons and the Full String Compare switch highlighted](../../IMG/5-2_p32-2_hw-search-operator-pop.png)

        - **c.** Enter the keyword(s) you wish to search with into the **Keywords** field and press `<Enter>`. You may also Import multiple keywords using a .csv file by clicking on **Import**, selecting the .csv file you wish to import, and then selecting the field in the .csv file you would like to import.

            ![Search with OR operator pop-up with the Keywords field and the Import button highlighted](../../IMG/5-2_p33-1_hw-search-import.png)

            ![Import pop-up for selecting the field to import from the CSV file, with the field drop-down highlighted](../../IMG/5-2_p33-2_hw-import-field.png)

        - **d.** Click on **Save** once you have finished setting the search conditions.

            ![Search with OR operator pop-up with the Save button highlighted](../../IMG/5-2_p33-3_hw-search-save.png)

2. If you wish to view the devices a hardware component is installed on, check the application, then click on **Show Device**. The list of devices the selected application is installed on should be displayed in the **Device List** window

    ![Hardware Inventory page with a component checked, the Show Device button highlighted and the Device List highlighted](../../IMG/5-2_p34-1_hw-show-device.png)

3. (optional) Clicking on ![Device Information icon](../../IMG/icon-list2.png) next to each device in the **Device List** will allow you to view the Device Information.

    ![Device Information page of a managed device with the Hardware Sensor, Utilization, Inventory, BMC, Software, Event Log, BIOS, Security and Configuration tiles](../../IMG/5-2_p34-2_hw-device-info.png)
