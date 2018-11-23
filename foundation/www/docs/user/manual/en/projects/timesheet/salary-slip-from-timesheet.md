<!-- add-breadcrumbs -->
# Salary Slip from Timesheet

If the salary/wages for your one or all of your employees are calculated based on the number of hours worked, you can use the `Timesheet` to track the actual hours worked, and create the Salary Slip based on that.

#### Employee creates Timesheet

To track the actual hours an employee has worked for, create Timesheet for each Employee. It's a good concept to create a Timesheet based on a payment period. For example, if you are paying employee on a weekly basis, create one Timesheet for an Employee for one week. If you pay on a monthly basis create a Timesheet for one month per Employee. 
However, you can also create multiple Timesheets per Employee, and create a Salary Slip based on those multiple Timesheets.

<img class="screenshot" alt="Sales Invoice" src="{{docs_base_url}}/assets/img/project/timesheet/timesheet-salary-slip-1.png">

#### Salary Structure for the Employee

To calculate the Salary based on hours worked you need to check the "Salary Slip Based on Timesheet" box in the `Salary Structure` of the Employee. Upon checking this box, you see the fields "Salary Component" and "Hour Rate". 
The amount for that Salary Component (let's say "Basic") will be calculated based on:

<div class=well> Total Timesheet Hours *  Hour Rate </div>

The Amount for other Salary Components (eg: House Rent Allowance, Phone Allowance, etc.) can be defined directly. When a Salary Slip is being created from such a Salary Strucure tmount for these Salary Component will be fetched as it is defined in the Salary Structure.

<div>
<img class="screenshot" alt="Sales Invoice" src="{{docs_base_url}}/assets/img/project/timesheet/timesheet-salary-slip-2.png">
</div>

#### Create Salary Slip from Timesheet(s)

To create a Salary Slip against Timesheet, open Timesheet and click on "Salary Slip".

<img class="screenshot" alt="Sales Invoice" src="{{docs_base_url}}/assets/img/project/timesheet/timesheet-salary-slip-3.png">

In the Salary Slip, Timesheet ID will be updated. You can select more Timesheet to be paid via this Salary Slip. Based on the Timesheets selected, Total Working Hours will be calculated.

<img class="screenshot" alt="Sales Invoice" src="{{docs_base_url}}/assets/img/project/timesheet/timesheet-salary-slip-4.gif">

Hour Rate will be fetched from the Salary Structure of an Employee. Based on Total Working Hours and Hour Rate, Amount will be calculated for the Salary Component based on actual hours worked.<br>

#### Save and Submit Salary Slip

On Submission of Salary Slip the Timesheet's status will be updated to "Payslip".

<img class="screenshot" alt="Sales Invoice" src="{{docs_base_url}}/assets/img/project/timesheet/timesheet-salary-slip-5.png">

<div class=well> 

Creating Salary Slip based on Timesheet will allow you to manage payment for the overtime.
	<ol>
		<li>Employee created Timesheet for the overtime.</li>
		<li>In the Salary Structure of an Employee, set Overtime as a Salary Component to be calculated based on hourly basis.</li>
		<li>When creating Salary Structure for an Employee, pull Timesheet when overtime details are tracked.</li>
	</ol>
</div>
