# Finals-Lab-Task-1
## Using MySQL Workbench to Create a Database: Sample screenshot and how it works depend of what he needs.

## Step by Step Process
1. Create the `employees` table:
   - Define `employee_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_name` as a VARCHAR (up to 255 characters), and make it not null.
   - Define `manager_id` as an integer, which will be a foreign key referencing `employee_id` from the same table.
# Screenshot and Structure sample:
[Image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20employee%20department.png)
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20employee%20department%20sample.png)

2. Create the `departments` table:
   - Define `department_id` as a unique integer, auto-increment, and primary key.
   - Define `department_name` as a VARCHAR (up to 255 characters), and make it not null.
# Screenshot and Structure sample:
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20statement.png)
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20table%20structure.png)

3. Create the `employee_departments` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `department_id` as an integer, which will be a foreign key referencing `department_id` in the `departments` table.
   - Set a composite primary key on the combination of `employee_id` and `department_id`.
# Screenshot and Structure sample:
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20query.png)
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20task%204%20sample.png)

4. Create the `employee_projects` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `project_name` as a VARCHAR (up to 255 characters), and make it not null.
# Screenshot and Structure sample:
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20task%204.png)
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20task%204%20sample.png)

5. Create the `managers` table:
   - Define `manager_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
# Screenshot and Structure sample:
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20task%205.png)
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20task%205%20sample.png)

#ER Diagram sample:
[image](https://github.com/chan-edm/README/blob/faae0d9b83620746282ee5a548409e3018306888/Images/final%201%20er%20diagram.png)

[BACK TO PORTFOLIO](https://chan-edm.github.io/README/)
