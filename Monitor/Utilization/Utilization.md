# Utilization

This item allows you to view real time data and set the utilization threshold value for the CPU, DIMM, Partition, and Network.

> **NOTE:** The Disk Partition block naming may differ between Windows ® and Linux systems. The Disk Partition block is titled **Partition** for Windows ® systems, and **File System** for Linux systems.

![Utilization 畫面](../../IMG/2-2_p34-1_utilization.png)

## Quick Buttons

| Icon | Description |
| --- | --- |
| ![Current 分頁圖示](../../IMG/icon-tab-current_02.png) | Click to switch to the Current tab. |
| ![History 分頁圖示](../../IMG/icon-tab-history_02.png) | Click to switch to the History tab. |
| ![展開所有區塊圖示](../../IMG/icon-expand-all_02.png) | Click to expand all blocks. |
| ![最小化所有區塊圖示](../../IMG/icon-minimize-all_02.png) | Click to minimize all blocks. |
| ![展開此區塊圖示](../../IMG/icon-expand-block_03.png) | Click to expand this block. |
| ![最小化此區塊圖示](../../IMG/icon-minimize-block_03.png) | Click to minimize this block. |

## Toggling between tabs

You can switch between different **Utilization** tabs by clicking the tabs in the top bar.

- ![Current 分頁圖示](../../IMG/icon-tab-current_02.png) **Current tab (default)**

    ![Utilization 的 Current 分頁](../../IMG/2-2_p35-1_tab-current.png)

- ![History 分頁圖示](../../IMG/icon-tab-history_02.png) **History tab**

    ![Utilization 的 History 分頁](../../IMG/2-2_p35-2_tab-history.png)

## Editing the threshold values

You can edit the critical and warning threshold values for **Utilization** items.

1. Click on a item to adjust the threshold values:
    - High Critical: When the value exceeds this threshold value, the sensor will display **Critical**.
    - High Warning: When the value exceeds this threshold value, the sensor will display **Warning**.

    > **NOTE:** The threshold options for each item may vary.

2. Click on **Save** once you have finished adjusting the threshold values of the item.

    ![Memory Utilization Threshold 視窗](../../IMG/2-2_p36-1_threshold-edit.png)

## Customizing the Utilization history tab

You can customize the history tab which displays historical data for the CPU, DIMM, Partition, and Network sensor events according to different periods of time.

![Utilization 歷史分頁](../../IMG/2-2_p37-1_history-tab.png)

### Quick Buttons

| Icon | Description |
| --- | --- |
| ![展開所有區塊圖示](../../IMG/icon-expand-all_02.png) | Click to expand all blocks. |
| ![最小化所有區塊圖示](../../IMG/icon-minimize-all_02.png) | Click to minimize all blocks. |
| ![展開此區塊圖示](../../IMG/icon-expand-block_03.png) | Click to expand this block. |
| ![最小化此區塊圖示](../../IMG/icon-minimize-block_03.png) | Click to minimize this block. |

### Chart Quick Buttons

| Icon | Description |
| --- | --- |
| ![下載圖表圖示](../../IMG/icon-chart-download_02.png) | Click to download an image of the chart as a .png file. |
| ![放大圖示](../../IMG/icon-zoom-in_03.png) | Click to zoom in on the timeline of the chart. |
| ![縮小圖示](../../IMG/icon-zoom-out_03.png) | Click to zoom out on the timeline of the chart. |
| ![還原圖表圖示](../../IMG/icon-zoom-reset_03.png) | Click to restore the chart to its default view. |

You can customize the charts by selecting the period of time you wish to view for the charts, then selecting the frequency for which the sensors should return data. This will be applied to the charts for all the sensors shown on this page.

![時間區間下拉選單](../../IMG/2-2_p38-1_period-menu.png)

![頻率下拉選單](../../IMG/2-2_p38-2_frequency-menu.png)

| Period of time | Frequency |
| --- | --- |
| **Last day** | 1 minute, 10 minutes, 20 minutes, 30 minutes, 1 hour |
| **Last week** | 10 minutes, 20 minutes, 30 minutes, 1 hour, 3 hours, 6 hours, 12 hours |
| **Last month** | 30 minutes, 1 hour, 3 hours, 6 hours, 12 hours, 1 day |
| **Last 6 months** | 3 hours, 6 hours, 12 hours, 1 day, 7 days, 14 days |
| **Last year** | 6 hours, 12 hours, 1 day, 7 days, 14 days, 30 days |

Additionally, by clicking on the ![圖表選單圖示](../../IMG/icon-chart-menu_02.png) icon, you can customize the data you wish to view on the chart.

![圖表選項選單](../../IMG/2-2_p39-1_chart-menu.png)

| Item | Description |
| --- | --- |
| **Refetch** | Allows you to trigger a refetch of device data. |
| **Chart Options** | Allows you to select whether the **Threshold** should be displayed on the chart. |
| **Data Sampling** | Allows you to select whether the **Maximum** values, **Average** values, or **Minimum** values should be displayed on the charts. |
