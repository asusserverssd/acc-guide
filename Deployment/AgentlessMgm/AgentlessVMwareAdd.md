# Add vSphere

The **Add vSphere** function allows you to add vSphere you wish to manage. You can enter a single vSphere, or multiple vSpheres to be scanned, and then add the scanned vSpheres you wish to manage to ASUS Control Center.

> **NOTE:** Ensure to register the License keys before adding the vSphere you wish to manage to ASUS Control Center. For more information on registering license keys, please refer to the **License** chapter.

![Add VMware vSphere Host page with the vSphere Host List and the Scan Result Information block](../../IMG/3-2_p35-1_add-vsphere-page.png)

## Adding managed vSphere

1. Click on **Add**.

    ![Add VMware vSphere Host page with the Add button highlighted](../../IMG/3-2_p35-2_vsphere-add.png)

2. Enter the **IP Address**, **Account**, and **Password** of the vSphere, then click **Save**.

    ![Add Target Host pop-up with the IP Address, Account and Password fields and the Save button highlighted](../../IMG/3-2_p36-1_vsphere-target.png)

3. Repeat steps 1 and 2 to add additional vSpheres to be scanned, or refer to the **Add vSphere from CSV file** section to import a list of vSpheres.
4. Once you have added all the vSpheres you wish to scan, click on **Scan**.

    ![vSphere Host List with the Scan button highlighted](../../IMG/3-2_p36-2_vsphere-scan.png)

5. The scanned results will be displayed in the **Scan Result Information** block. Select the vSpheres you wish to manage then click **Add to Monitor**. The vSpheres added should appear in the **Devices List** on the **System Overview** screen.

    > **NOTE:**
    >
    > - Unavailable vSpheres will be listed as **Not Support**. You may click on the vSpheres to view details on why it is unavailable.
    > - vSpheres added may take a few minutes before they are displayed in the overview.

    ![Scan Result Information with the supported vSphere checked and the Add to Monitor button highlighted](../../IMG/3-2_p37-1_vsphere-add-monitor.png)

## Add vSphere from CSV file

1. Click on **Import**.

    ![Add VMware vSphere Host page with the Import button highlighted](../../IMG/3-2_p38-1_vsphere-import.png)

2. Select the CSV file to import and click **Open**.
3. Once the CSV file is successfully imported, click on **Scan**.

    > **NOTE:** You may edit items added by clicking on it before scanning.

4. The scanned results will be displayed in the **Scan Result Information** block. Select the vSpheres you wish to manage then click **Add to Monitor**. The vSpheres added should appear in the **Devices List** on the **System Overview** screen.

    > **NOTE:**
    >
    > - Unavailable vSpheres will be listed as **Not Support**. You may click on the vSpheres to view details on why it is unavailable.
    > - vSpheres added may take a few minutes before they are displayed in the overview.

    ![Scan Result Information with the supported vSphere checked and the Add to Monitor button highlighted](../../IMG/3-2_p38-2_vsphere-csv-result.png)

## Exporting VMware vSphere Host List

You can export the list of vSpheres added to the **VMware vSphere Host List** to a CSV file by clicking on **Export**. You can edit the exported CSV file using a text editor.

![Add VMware vSphere Host page with the Export button highlighted](../../IMG/3-2_p39-1_vsphere-export.png)
