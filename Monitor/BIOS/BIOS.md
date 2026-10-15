# BIOS

This item allows you to update the BIOS of a managed device by uploading a BIOS cap file or selecting a BIOS cap file from the BIOS Cache, view and adjust BIOS settings, and view the Desktop Management Interface Information.

> **NOTE:** The functions available in this item may vary according to managed device.

![BIOS 畫面](../../IMG/2-5_p64-1_bios.png)

## BIOS Flash

The **BIOS Flash** tab allows you to flash the BIOS of the device by manually uploading a BIOS cap file or selecting a BIOS cap file from the BIOS Cache.

> **IMPORTANT:** Flashing the BIOS using ASUS Control Center is only supported on managed devices that are ASUS products.

1. You can upload or select your BIOS cap file using the following methods:
    - **Manually uploading BIOS cap file**
        - **a.** Select **Manually Upload BIOS File** in the **BIOS Flash Type** field.

            ![選擇 Manually Upload BIOS File](../../IMG/2-5_p65-1_flash-manual.png)

        - **b.** Click on **Upload BIOS File** to select a BIOS cap file, or drag the BIOS cap file into the dotted square.

            > **NOTE:** The uploaded BIOS cap file will automatically be added to the **BIOS Cache**.

            ![選擇 BIOS cap 檔案](../../IMG/2-5_p65-2_flash-upload.png)

    - **Selecting BIOS cap file from the BIOS Cache**
        - **a.** Select **Flash From BIOS Cache** in the **BIOS Flash Type** field.

            ![選擇 Flash From BIOS Cache](../../IMG/2-6_p66-1_flash-cache.png)

        - **b.** Select a BIOS cap file to use from the **BIOS Cache List** drop down menu.

            ![從 BIOS Cache List 選擇檔案](../../IMG/2-6_p66-2_flash-cache-list.png)

2. (optional) You may check the **Reboot after BIOS Flash** checkbox in the **Automatic Reboot** field to automatically reboot the device after BIOS has been flashed.

    ![Automatic Reboot 選項](../../IMG/2-6_p67-1_auto-reboot.png)

3. (optional) You may check the **Turn On (BMC only)** checkbox in the Locator LED field to turn on the Locator LED once BIOS Flash is completed.

    > **NOTE:** BMC is required for this option to work properly.

    ![Locator LED 選項](../../IMG/2-6_p67-2_locator-led.png)

4. Click **Flash** to begin the BIOS flash, then wait for the BIOS flash to be completed.

    ![Flash 按鈕](../../IMG/2-6_p68-1_flash-button.png)

    ![BIOS 更新進度](../../IMG/2-6_p68-2_flash-progress.png)

5. Once the BIOS flash has been completed, a pop-up window will appear, prompting you to reboot the system, click **OK**. You can also view this message in the **Device Information** screen and **Mission Center**.

    ![Device Information 的重新開機提示](../../IMG/2-6_p69-1_reboot-notice.png)

    ![Mission Center 的重新開機訊息](../../IMG/2-6_p69-2_mission-center.png)

6. Reboot the device to complete the BIOS flash.

## BIOS Setting

> **IMPORTANT:** The **BIOS Setting** tab is only available on specific ASUS products such as an ASUS commercial notebook PC. For more information on ASUS products that support ASUS Control Center, please refer to https://asuscontrolcenter.asus.com.

The **BIOS Setting** tab allows you to view and adjust the BIOS **Advanced**, **Monitor**, **Boot**, and **Security** settings of the device, providing you with a quick way of adjusting BIOS settings without having to enter the BIOS menu of the device.

> **NOTE:** The BIOS settings may differ between devices. Please refer to the device’s motherboard user manual for more information about the BIOS settings.

![BIOS Setting 分頁](../../IMG/2-6_p70-1_bios-setting.png)

## DMI Info

Under the SMBIOS standard, the **DMI Info** tab allows you to view details on certain items such as manufacturer name and hardware component information of the device without a hardware controller.

![DMI Info 分頁](../../IMG/2-6_p71-1_dmi-info.png)
