# BIOS Flash Task

The **BIOS Flash Task** function allows you to update the BIOS of multiple managed devices by uploading the BIOS cap file or selecting the BIOS cap file from a BIOS cache list.

![BIOS Flash Task page with the BIOS Flash Information block, the Target Host List and the Flash button](../../IMG/4-2_p15-1_flash-task-page.png)

## Manually uploading the BIOS cap file

1. Select **Manually Upload BIOS File** from the drop down menu in the **BIOS Flash Type** field.

    ![BIOS Flash Information with the BIOS Flash Type field set to Manually Upload BIOS File and highlighted](../../IMG/4-2_p15-2_flash-type-manual.png)

2. Drag and drop the BIOS cap file in the dotted square, or click on **Upload BIOS File** to select a BIOS cap file to upload.

    ![Upload BIOS area highlighted with a file open dialog for selecting a BIOS cap file](../../IMG/4-2_p16-1_upload-bios-file.png)

3. After selecting the BIOS cap file, the BIOS information, BIOS version, BIOS build date, as well as applicable managed devices should appear. Click on **Flash** to begin the BIOS Flash process.

    ![BIOS Flash Task page with the BIOS information, applicable managed devices and Flash button highlighted](../../IMG/4-2_p16-2_flash-ready.png)

4. Once the flash process is finished, a BIOS Flash Report should appear allowing you to check the BIOS Flash status and progress of all selected devices.

    ![BIOS Flash Report showing the completion rate, success and error counts, and the device list](../../IMG/4-2_p17-1_flash-report.png)

## Selecting the BIOS cap file from the BIOS cache

1. Select **Flash From BIOS Cache** from the drop down menu in the **BIOS Flash Type** field.

    ![BIOS Flash Type field set to Flash From BIOS Cache and highlighted](../../IMG/4-2_p18-1_flash-type-cache.png)

2. Select a **BIOS Cache List**.

    ![BIOS Cache List drop-down menu showing the cached BIOS files grouped by model](../../IMG/4-2_p18-2_bios-cache-dropdown.png)

3. After selecting the BIOS cap file, the BIOS information, BIOS version, BIOS build date, as well as applicable managed devices should appear. Click on **Flash** to begin the BIOS Flash process.

    ![BIOS Flash Task page with the BIOS information, applicable managed devices and Flash button highlighted](../../IMG/4-2_p19-1_flash-ready-cache.png)

4. Once the flash process is finished, a BIOS Flash Report should appear allowing you to check the BIOS Flash status and progress of all selected devices.

    > **NOTE:** If the device is using Windows 11 or Server 2022 and the BIOS flash is failing, please navigate to **Start** > **Settings** > **Update & Security** > **Windows Security** > **Device Security**, then select **Core Isolation details** and set **Memory integrity** to **Off** on the device.

    ![BIOS Flash Report showing the completion rate, success and error counts, and the device list](../../IMG/4-2_p19-2_flash-report-cache.png)
