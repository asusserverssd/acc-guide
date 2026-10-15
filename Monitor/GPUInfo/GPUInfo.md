# GPU

This item allows you to view the GPU Load, Fan, Temperature, Power, and Memory details on GPU cards installed on the device, and also view the timeline chart of these items. For more details on a GPU device click on ![GPU 詳細資訊圖示](../../IMG/icon-gpu-detail.png) next to the GPU device.

![GPU 畫面](../../IMG/2-7_p78-1_gpu.png)

![GPU 詳細資訊視窗](../../IMG/2-7_p78-2_gpu-detail.png)

## Filtering the GPU devices

By clicking on a status block you can filter the GPU devices shown in the GPU information block according to the status selected

![依狀態區塊篩選 GPU 裝置](../../IMG/2-7_p79-1_gpu-filter.png)

## Toggling the Chart View for GPU devices

You can view the timeline charts for GPU Load, Fan Utilization, Temperature, Power Utilization, Power Usage, Memory Utilization, and Memory Usage by scrolling down on the GPU page.

By default the timeline charts display the Average values, but you may select to view only selected GPU devices by checking the device in the GPU Information block, or by clicking on the GPU device(s) in the timeline chart legend.

> **NOTE:** Any changes made, such as selecting a device to view on a timeline chart will be applied to all other timeline charts, for example selecting GPU0 in the timeline chart legend of GPU Load timeline chart will cause all other timeline charts on this page to display information on GPU0 only.

![時間軸圖表圖例](../../IMG/2-7_p80-1_gpu-legend.png)

### Chart Quick Buttons

| Icon | Description |
| --- | --- |
| ![放大圖示](../../IMG/icon-zoom-in_01.png) | Click to zoom in on the timeline of the chart. |
| ![縮小圖示](../../IMG/icon-zoom-out_01.png) | Click to zoom out on the timeline of the chart. |
| ![還原圖表圖示](../../IMG/icon-zoom-reset_01.png) | Click to restore the chart to its default view. |

You can customize the timeline chart by selecting the period of time you wish to view for the timeline charts, then selecting the frequency for which the sensor should return data. This will be applied to the timeline charts for all the sensors shown on this page.

![時間區間與頻率選單](../../IMG/2-7_p81-1_gpu-period.png)

| Period of time | Frequency |
| --- | --- |
| **1D** | 1m, 10m, 20m, 30m, 1h |
| **7D** | 10m, 20m, 30m, 1h, 3h, 6h, 12h |
| **30D** | 30m, 1h, 3h, 6h, 12h, 1d |
| **6M** | 3h, 6h, 12h, 1d, 7d, 14d |
| **1Y** | 6h, 12h, 1d, 7d, 14d, 30d |

Additionally, by clicking on the ![設定圖示](../../IMG/icon-gear_01.png) icon, you can customize the data you wish to view on the timeline.

![圖表選項選單](../../IMG/2-7_p82-1_gpu-chart-menu.png)

| Item | Description |
| --- | --- |
| **Chart Options** | Allows you to check the items you wish to display on the timeline charts such as **Threshold Markline** and **Fill Line Area**, or set a **Fixed Y-axis** for the timeline chart. |
| **Data Sampling** | Allows you to select whether the **Maximum** values, **Minimum** values, or **Average** values should be displayed on the timeline chart. |

## Configuring the GPU layout

You can freely rearrange and resize the different blocks on the GPU page to change  the layout of this page to your preference.

1. Click on the ![設定圖示](../../IMG/icon-gear_01.png) icon, then select **Custom Layout**.

    ![選擇 Custom Layout](../../IMG/2-7_p83-1_gpu-custom-layout.png)

2. You can now rearrange or resize each of the blocks on this page. Please refer to the following for instructions on resizing or rearranging the blocks.

    ![編輯 GPU 版面配置](../../IMG/2-7_p83-2_gpu-layout-edit.png)

    - **To resize the block:**

        Hover the mouse over the edges of the block you wish to resize until the resize arrows appear, then click and drag to resize the block.

    - **To expand the block to its maximum size:**

        Click on ![展開區塊至最大圖示](../../IMG/icon-maximize-block.png) to expand the block to its maximum size.

    - **To minimize the block to its minimum size:**

        Click on ![縮小區塊至最小圖示](../../IMG/icon-minimize-block-min.png) to minimize the block to its minimum size.

    - **To rearrange the blocks:**

        Click and hold inside the block you would like to rearrange, then drag the block to rearrange it.

    - **To remove a block:**

        Click on ![移除區塊圖示](../../IMG/icon-remove-block.png) to remove the block, or click on ![Widget Option 按鈕](../../IMG/icon-widget-option.png) and uncheck the block you wish to remove.

    - **To add a block:**

        Click on ![Widget Option 按鈕](../../IMG/icon-widget-option.png) and check the block you wish to add.

    - **To reset to default layout:**

        Click on ![Reset 按鈕](../../IMG/icon-reset.png) to reset the GPU page to its default layout.

3. Once you are finished rearranging and resizing the blocks, click on **Save** to save the changes made to this page.

## Editing the threshold valuesx

You can edit the critical and warning threshold values for **GPU** items.

1. Click on the ![設定圖示](../../IMG/icon-gear_01.png) icon, then select **Threshold**.

    ![選擇 Threshold](../../IMG/2-7_p85-1_gpu-threshold-menu.png)

2. Adjust the thresholds for the sensors by sliding the **Normal** (green), **Warning** (yellow) and **Critical** (red) sliders for the **High Alert** and **Low Alert**. You can also disable or enable **High Alert** and/or **Low Alert** by checking/unchecking **High Alert** and/or **Low Alert**.

    > **NOTE:** Click on **Reset** to reset the threshold settings to default settings.

    ![GPU Threshold 視窗](../../IMG/2-7_p86-1_gpu-threshold.png)

3. Once you have finished adjusting the thresholds, click on **Save** to save the changes made.
