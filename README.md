# Smart Planner With Budgets - Excel.
# Project Planner: Automatic Date Calculation, Gantt Chart, and Budget Control

A dynamic project management tool designed to automate date calculations, visualise project timelines, and monitor budget performance.

## Key Features

- **Automatic Date Calculation**
  - Project plan dates update automatically, taking into account weekends, bank holidays, staff holidays, dependencies, task reference numbers, and previous task assignments.
  - Accurate date calculation requires each day to be specified for precise determination of start and end dates.

- **Dynamic Gantt Chart**
  - The Gantt chart updates automatically based on changes in the project plan.
  - Users must specify the Task Name and Effort, and ensure the Percentage Completed is set to 0% or above (not "N/A").

- **Project Summary Drill Down**
  - Users can drill down into specific months to view start dates, end dates, and the count of different task statuses.
  - End dates take priority over start dates for calculating the number of statuses in a given month.

- **Applying Holidays**
  - **Bank holidays** are applied to all staff.
  - **Staff holidays** are only applied to the individual staff member assigned to a specific task.
  - **Staff holiday reflection:** Staff holidays appear in the holiday count field. This table can also capture additional delays for an assignee, including a reason and notes—useful for project reviews and retrospectives.
  - **Holiday impact on task start dates:** If a holiday coincides with a task’s start date, the system shifts the start date to the next available working day. Note: this automatic shift is not reflected in the holiday count field; only holidays after a task’s start date are included in the count.

- **Budget Control**
  - Compare estimated versus actual costs by department and assignee.

## How to Use

1. **Set Up Static Data**
   - **Resources:** Add all relevant staff or team members who will be assigned to tasks.
   - **Budgets:** Enter estimated costs and budgets for each department and assignee.
   - **Holidays:**  
     - **Bank Holidays:** Specify all bank holidays that affect the entire team.
     - **Employee Holidays:** Record individual staff holidays; these will only affect the assigned staff member.

2. **Enter Project Tasks**
   - **Task Name:** Assign a clear name to each task.
   - **Effort:** Estimate the effort required for each task.
   - **Assignee:** Select the staff member responsible for the task.

3. **Specify Dependencies and Reference Numbers**
   - **Dependencies:** Indicate any tasks that must be completed before others can start.
   - **Reference Numbers:** Assign unique reference numbers to each task for tracking.

4. **Update Task Status**
   - **Percentage Completed:** Set to 0% or above (not "N/A") for accurate Gantt chart updates.

5. **Review Project Summary**
   - **Drill Down:** View start and end dates, and task status counts for specific months.
   - **End Date Priority:** End dates are used to calculate the number of statuses in each month.

6. **Monitor Budget**
   - **Compare Costs:** Track estimated versus actual costs by department and assignee.

---
Watch our video https://youtu.be/9KqgWq56Izs
If you have any questions visit our site www.smarterworker.co.uk/#contact and complete the form with your questions.

