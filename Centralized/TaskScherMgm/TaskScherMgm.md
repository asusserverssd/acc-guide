# Task Scheduler

Schedule tasks for managed devices using the Task Scheduler. The tasks set can be executed automatically at specific times, or set to repeat periodically, which allows you to schedule tasks before hand or periodic tasks such as periodic reboot of managed devices.

To access **Task Scheduler**, click ![Centralized menu icon](../../IMG/icon-centralized_05.png) > **Task Scheduler** in the left menu.

![Task Scheduler page showing the calendar view with scheduled tasks](../../IMG/4-5_p37-1_scheduler-page.png)

**Using the search bar and search options**

Refer to the **Search Options** and **Search and Filter Devices** sections of the **Monitor** chapter for more information.

## Task Scheduler Overview

Toggle between the different Task Scheduler views by clicking on the ![Calendar view icon](../../IMG/icon-calendar.png) / ![History view icon](../../IMG/icon-history.png) icon. You can click on any task displayed to view more details on the task.

- ![Calendar view icon](../../IMG/icon-calendar.png): Calendar view displays the tasks and the dates when they will be executed.

    ![Task Scheduler calendar view for April 2019](../../IMG/4-5_p38-1_calendar-view.png)

    You can switch the time period displayed in Calendar view by using the following:

    - ![Previous year button](../../IMG/icon-prev-year.png) View previous year
    - ![Next year button](../../IMG/icon-next-year.png) View next year
    - ![Previous month / week / day button](../../IMG/icon-prev-period.png) View previous month / week / day
    - ![Next month / week / day button](../../IMG/icon-next-period.png) View next month / week / day
    - ![Today button](../../IMG/icon-today.png) Move to the current day. The current day will be highlighted on the calendar.
    - ![Month view button](../../IMG/icon-month.png) Display month view

        ![Task Scheduler in month view](../../IMG/4-5_p38-2_month-view.png)

    - ![Week view button](../../IMG/icon-week.png) Display week view

        ![Task Scheduler in week view showing one week of tasks](../../IMG/4-5_p38-3_week-view.png)

    - ![Day view button](../../IMG/icon-day.png) Display day view

        ![Task Scheduler in day view showing one day](../../IMG/4-5_p39-1_day-view.png)

    - ![List view button](../../IMG/icon-list_01.png) Display list of all tasks in the selected month and year.

        ![Task Scheduler in list view showing all tasks in the selected month](../../IMG/4-5_p39-2_list-view.png)

- ![History view icon](../../IMG/icon-history.png): History list of all tasks, including Task Name, Start Date & Time, End Date & Time, Repeat, Number of Clients, Status, and Switch.

    ![Task Scheduler history list with task name, start and end date, repeat, number of clients, status and switch](../../IMG/4-5_p39-3_history-view.png)

## Adding a scheduled task

1. Click on **Add**.

    ![Task Scheduler with the Add button highlighted](../../IMG/4-5_p40-1_add-task-button.png)

2. Enter the **Taskset Name**, then select a **Start Date & Time**.

    ![Taskset Editor with the Taskset Name and Start Date & Time fields highlighted](../../IMG/4-5_p40-2_taskset-name.png)

3. Select **Windows** or **Linux** in the **Target OS** field to filter the target devices.

    ![Taskset Editor with the Target OS field highlighted and the device list below](../../IMG/4-5_p41-1_target-os.png)

4. (optional) If you want to repeat the task, check **Repeat** in the **Repetition Schedule** field, then select **Daily** to repeat the task daily, or **Weekly** to repeat the task weekly. When you select **Weekly**, remember to select which days of the week you wish to repeat the task.

    ![Taskset Editor with the Repeat checkbox and the Daily and Weekly options highlighted](../../IMG/4-5_p41-2_repeat-schedule.png)

5. (optional) You may select an end date and time.

    > **NOTE:** The **End Date & Time** option only appears when **Repeat** has been checked.

    ![Taskset Editor with the End Date & Time field highlighted](../../IMG/4-5_p42-1_end-date.png)

6. **Enabled Task Schedule** is enabled by default, if you wish to disable the task, uncheck **Enabled Task Schedule** in the **Activation** field.

    ![Taskset Editor with the Enabled Task Schedule checkbox highlighted](../../IMG/4-5_p42-2_enabled-schedule.png)

7. A list of all managed devices matching the **Target OS** selected will be displayed. Select the managed devices to apply the task to, then click **Next**.

    ![Target device list with devices checked and the Next button highlighted](../../IMG/4-5_p43-1_select-devices.png)

8. Click on **Add** in the middle-right of the screen to add a new task.

    ![Step 2 Schedule the tasks with the Add button highlighted](../../IMG/4-5_p43-2_add-task-step2.png)

9. Select an **Action Type**. Each action type contains different options, see below for a list of the action types and the options available.

    > **NOTE: Linux** only supports **Power Control** and **Security** action types.

    Power Control:

    ![Add Task pop-up with Action Type set to Power Control and the Power On, Power Off and Power Reboot options](../../IMG/4-5_p44-1_action-power.png)

    | Action Type | Options | Description |
    | --- | --- | --- |
    | **Power Control** | Power On | Power on the device. |
    | **Power Control** | Power Off | Power off the device. |
    | **Power Control** | Power Reboot | Reboot the device. |

    Service Control:

    ![Add Task pop-up with Action Type set to Service Control, a service name field and the Start, Stop and Restart options](../../IMG/4-5_p44-2_action-service.png)

    | Action Type | Options | Description |
    | --- | --- | --- |
    | **Service Control** | Service Name | Enter the name of the service. If you are unsure of the name of the service, refer to the **Software** section. |
    | **Service Control** | Start | Activate the service. |
    | **Service Control** | Stop | Stop the service. |
    | **Service Control** | Restart | Restart the service. |

    Software Dispatch:

    ![Add Task pop-up with Action Type set to Software Dispatch, with the Platform Type and Package Name fields highlighted](../../IMG/4-5_p45-1_action-swdispatch.png)

    | Action Type | Options | Description |
    | --- | --- | --- |
    | **Software Dispatch** | Platform Type | Select from **32Bit**, **64Bit**, or **32_64Bit** to filter the software options. |
    | **Software Dispatch** | Package Name | Select an item from the **Software Pool** to be installed. The options will vary according to the Bit type selected in **Platform Type**. |

    Security Control:

    ![Add Task pop-up with Action Type set to Security Control, with the Security Type and Status options highlighted](../../IMG/4-5_p45-2_action-security.png)

    | Action Type | Security Type | Options | Description |
    | --- | --- | --- | --- |
    | **Security Control** | USB Control | Enable Access | Allows USB ports to be accessed. |
    | **Security Control** | USB Control | Disable Access | Do not allow USB ports to be accessed. |
    | **Security Control** | USB Control | Read Only | Files on the USB storage device can only be read. |
    | **Security Control** | WatchDog Function | Enable | Enables Watchdog timer. |
    | **Security Control** | WatchDog Function | Disable | Disables Watchdog timer. |
    | **Security Control** | Registry Tool | Enable | Enable access to Regedit Tool. |
    | **Security Control** | Registry Tool | Disable | Disable access to Regedit Tool. |

10. Set the **Delay Time** (in minutes). This function is used to set a delay time before the task is executed.

    > **CAUTION:** When adding multiple tasks, ensure to set a Delay Time for each task to ensure the tasks are executed properly.

    ![Add Task pop-up with the Delay Time field highlighted](../../IMG/4-5_p46-1_delay-time.png)

11. Once you have finished with setting the task, click on **Save**. The newly added task will be displayed in a timeline, you may click and drag the items in the timeline to rearrange the scheduled tasks. Clicking on ![Delete task icon](../../IMG/icon-trash-red.png) will delete the task.
12. When you are finished, click on the **Save** at the bottom of the screen.

    ![Taskset Editor step 2 showing the added tasks in a timeline with the Save button highlighted](../../IMG/4-5_p46-2_task-timeline.png)

## Editing a scheduled task

1. Click on the task you wish to edit on the calendar in Calendar view.

    OR

    Click on the task you wish to edit from the list in History view.

2. Edit the details then click **Update** at the bottom of the screen when you have finished editing.

    > **NOTE:** You can refer to step 2 to 12 of the **Add Scheduled task** under the **Task Scheduler** section for the steps on editing a task; the steps are the same.

3. Click **Update** on the pop-up window to confirm the changes made.

    ![Update the Task Schedule confirmation pop-up with the Update button highlighted](../../IMG/4-5_p47-1_update-confirm.png)

## Deleting a scheduled task

1. Click on the task you wish to edit on the calendar in Calendar view.

    OR

    Click on the task you wish to edit from the list in History view.

2. Click **Delete** at the bottom of the screen, then click **Delete** on the pop-up window to delete the scheduled task.

    ![Delete the task schedule confirmation pop-up with the Delete button highlighted](../../IMG/4-5_p47-2_delete-confirm.png)
