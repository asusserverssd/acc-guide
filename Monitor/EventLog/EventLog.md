# Event Log

This item displays the event logs for the **ASUS Control Center**, **Application**, **System**, **Security**, and **Power**. You may view each event log by clicking on the tabs and switch between **Logs** view or **Log Analysis** view within each tab. Click on an event to view more details about the event.

> **NOTE:**
>
> - To export the Event Log click the **Export** button, enter a filename, then click **OK**.
> - Linux systems only support the **ASUS Control Center** tab.

**For Windows ® system:**

![Windows 系統的 Event Log 畫面](../../IMG/2-2_p51-1_eventlog-win.png)

**For Linux system:**

![Linux 系統的 Event Log 畫面](../../IMG/2-2_p51-2_eventlog-linux.png)

## Switching to Log Analysis view

Click on **Log Analysis** to view the event log as a bar chart and timeline chart, allowing you to view the amount of **Normal**, **Warning**, and **Critical** events.

> **NOTE:** Click on **Logs** to switch back to the list view of the event log.

![Log Analysis 檢視](../../IMG/2-2_p52-1_log-analysis.png)

You can click on a item on either chart key to hide that item on both charts.

![隱藏圖例項目後的圖表](../../IMG/2-2_p52-2_log-analysis-hide.png)

## ASUS Control Center tab

![ASUS Control Center 分頁](../../IMG/2-2_p53-1_acc-tab.png)

## Application tab (Windows only)

![Application 分頁](../../IMG/2-2_p53-2_application-tab.png)

## System tab (Windows only)

![System 分頁](../../IMG/2-2_p54-1_system-tab.png)

## Security tab (Windows only)

![Security 分頁](../../IMG/2-2_p54-2_security-tab.png)

## Power tab (Windows only)

This tab will display the power on, power off, and restart event logs for the managed device. You can select to view the power event log events of different periods of time.

![Power 分頁](../../IMG/2-2_p55-1_power-tab.png)

**7 Days (Log Analysis):**

![7 Days 的 Log Analysis](../../IMG/2-2_p55-2_power-7days.png)

**30 Days (Log Analysis):**

![30 Days 的 Log Analysis](../../IMG/2-2_p56-1_power-30days.png)

**6 Months (Log Analysis):**

![6 Months 的 Log Analysis](../../IMG/2-2_p56-2_power-6months.png)

**1 Year (Log Analysis):**

![1 Year 的 Log Analysis](../../IMG/2-2_p57-1_power-1year.png)

## Filtering the event log using advanced search

1. Click on **Advance**.
2. Select the **Filter Type**.
    - **Filter by total records**: Filters according to the number of records.
    - **Filter by Timestamp**: Filters according to the set time period.
3. Select the **Level Type**(s) you wish to filter
4. The **Conditions** may vary depending on the **Filter Type** selected.
    - **Filter by total records**: Set the amount of records to show. This amounts increments by 100 and ranges from 100 to 5000 records.

        ![Advanced Search 視窗（依總筆數篩選）](../../IMG/2-2_p58-1_advanced-records.png)

    - **Filter by Timestamp**: Select a time period to show records, or set a custom time frame to show records within the set time frame.

        ![Advanced Search 視窗（依時間戳記篩選）](../../IMG/2-2_p59-1_advanced-timestamp.png)

        When you select **Custom Time Period**, you can select a **Start Date & Time**, and **End Date & Time**.

        ![自訂時間區間的日期選擇器](../../IMG/2-2_p59-2_advanced-custom.png)

5. Click **Action** to start filtering the Event Log.

    > **NOTE:** This function will replace the Event Log list with the new results, and searching / filtering using the Search toolbar will only perform a search / filter on the new Event Log list.

    Filter example of **Warning** Level Type of **Filter by total records**:

    ![Warning 等級的篩選結果](../../IMG/2-3_p60-1_filter-warning.png)

    Filter example of **Critical** Level Type **Filter by Timestamp**:

    ![Critical 等級的篩選結果](../../IMG/2-3_p60-2_filter-critical.png)

## Filtering the Power event log

Click on ![電源事件篩選圖示](../../IMG/icon-power-filter.png), then select the criteria to filter.

> **NOTE:**
>
> - Selecting **All** will display all power event log items.
> - Selecting **Power** will only display power related events.
> - Selecting **Connection** will only display online/offline events.

![電源事件記錄的篩選選單](../../IMG/2-3_p61-1_power-filter-menu.png)

![篩選後的電源事件記錄](../../IMG/2-3_p61-2_power-filter-result.png)
