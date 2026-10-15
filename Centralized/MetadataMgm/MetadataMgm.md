# Metadata Management

The **Metadata Management** screen allows you to add metadata fields, and also enter the information for the newly added metadata fields for a single device or multiple devices. This allows you to manage your devices more efficiently by adding the information you need to each managed device, such as the department the managed device belongs to, or the extension line of the owner of the managed device.

To access **Metadata Management**, click ![Centralized menu icon](../../IMG/icon-centralized_02.png) > **Metadata Management** in the left menu.

![Metadata Management page with the host list and the Editor, Batch Update, Export and Options buttons](../../IMG/4-1_p02-1_metadata-page.png)

**Using the search bar and search options**

Refer to the **Search Options** and **Search and Filter Devices** sections of the **Monitor** chapter for more information.

## Adding metadata fields

You may add new metadata fields for managed devices using this function.

1. Click on **Editor** to open the Metadata Editor.

    ![Metadata Management page with the Editor button highlighted](../../IMG/4-1_p03-1_editor-button.png)

2. Enter the Field Name of the new metadata column and select the Field Type from the drop down menu (**String**, **Number**, **Date**, **Boolean**), then click **Add**.

    > **NOTE:**
    >
    > - **String:** The data in this field contains string variables.
    > - **Number:** The data in this field contains numerical values.
    > - **Date:** The data in this field are in date form.
    > - **Boolean:** The data in this field are either true or false.

    ![Metadata Editor with the Field Name and Field Type fields and the Add button highlighted](../../IMG/4-1_p03-2_add-field.png)

3. (optional) You may set or edit the default value of the new field by double-clicking in the **Default Value** cell and then entering the new default value.

    > **NOTE:** The default values will be restricted to the Field Type chosen.

    ![Metadata Editor with the Default Value column highlighted](../../IMG/4-1_p04-1_default-value.png)

4. Repeat steps 2 to 4 to add additional metadata fields.
5. Click on **Save** when you have finished adding or editing the metadata fields.

    ![Metadata Editor with a Done message and the Save button highlighted](../../IMG/4-1_p04-2_save-fields.png)

## Editing metadata fields

1. Click on **Editor** to open the Metadata Editor.

    ![Metadata Management page with the Editor button highlighted](../../IMG/4-1_p05-1_editor-button-edit.png)

2. You can edit the **Field Name** and **Default Value** of existing metadata fields. When you are finished editing, click on **Save** to save the changes made.

    ![Metadata Editor with the Field Name and Default Value columns and the Save button highlighted](../../IMG/4-1_p05-2_edit-fields.png)

## Deleting metadata fields

1. Click on **Editor** to open the Metadata Editor.

    ![Metadata Management page with the Editor button highlighted](../../IMG/4-1_p06-1_editor-button-delete.png)

2. Click on ![Delete icon](../../IMG/icon-trash-blue.png) next to the metadata field you wish to delete. Once you are finished, click on **Save** to save the changes made.

    ![Metadata Editor with the delete icons next to the fields and the Save button highlighted](../../IMG/4-1_p06-2_delete-field.png)

## Editing the metadata value of a single device

1. Double-click on a field you wish to edit and enter the new value.

    > **NOTE:**
    >
    > - Items in the **Host Name** field cannot be edited.
    > - Edited fields will have blue text.

2. Click on **Save** once you have finished making changes to the metadata.

    ![Metadata Management table with an edited row shown in blue text and the Save button highlighted](../../IMG/4-1_p07-1_edit-single-device.png)

## Editing the metadata value of multiple devices

1. Click on **Batch Update**.

    ![Metadata Management page with the Batch Update button highlighted](../../IMG/4-1_p08-1_batch-update-button.png)

2. Select a CSV file to import, then click **Open**.

    ![File open dialog with a CSV file selected and the Open button highlighted](../../IMG/4-1_p08-2_select-csv.png)

3. Select the metadata field columns to update to the server, then click **Batch Update**.

    ![Batch Update pop-up listing the metadata fields to import, with the Batch Update button highlighted](../../IMG/4-1_p09-1_select-columns.png)

4. A confirmation window should pop-up, click **OK**.

    ![Confirmation pop-up for importing the selected fields with the OK button highlighted](../../IMG/4-1_p09-2_confirm-import.png)

5. Next, another pop-up window will appear notifying you of which devices will be affected by the updated data. Click **OK** to confirm these changes, or click **Cancel** to cancel the batch update.

    ![Pop-up listing the hosts affected by the batch update, with the OK and Cancel buttons](../../IMG/4-1_p10-1_affected-hosts.png)

6. If you clicked **OK** in the previous step, click on **Save** to save the changes made.

    ![Metadata Management page with the Save button highlighted](../../IMG/4-1_p10-2_save-batch.png)

## Exporting the metadata value

Exporting the metadata to a CSV file allows you to edit multiple metadata fields together, then update them by importing it back into ASUS Control Center. To import the changes made to the metadata in the CSV file, refer to **Editing the metadata of multiple devices** under the **Metadata Management** section.

1. Click on **Export**.

    ![Metadata Management page with the Export button highlighted](../../IMG/4-1_p11-1_export-button.png)

2. Enter a filename for the CSV file, then click **OK**.

    > **NOTE:**
    >
    > - Use a text editor when editing the exported CSV file.
    > - Do not edit the **aswm_HostName** and **ClientGUID** fields.
    > - Only the existing data in the CSV file may be edited, adding new rows and columns to the CSV file may cause failure when importing to the ASUS Control Center.
