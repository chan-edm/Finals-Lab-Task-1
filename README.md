# Finals-Lab-Task-1
## Using MySQL Workbench to Create a Database: Sample screenshot and how it works depend of what he needs.

## Step by Step Process
1. Create the `employees` table:
   - Define `employee_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_name` as a VARCHAR (up to 255 characters), and make it not null.
   - Define `manager_id` as an integer, which will be a foreign key referencing `employee_id` from the same table.
# Screenshot and Structure sample:
![Image](https://github.com/user-attachments/assets/7f3b8940-dc80-44f7-b6c7-3b32b861a71a)
![Image](https://github.com/user-attachments/assets/73e062da-4488-4a52-9b55-8a7cf042d3ff)
2. Create the `departments` table:
   - Define `department_id` as a unique integer, auto-increment, and primary key.
   - Define `department_name` as a VARCHAR (up to 255 characters), and make it not null.
# Screenshot and Structure sample:
![Image](https://github.com/user-attachments/assets/639ffd7b-5e58-46ef-9b86-b82b1ce88c66)
![Image](https://github.com/user-attachments/assets/82c1077d-e135-48e1-8dc4-bf5663b8782e)

3. Create the `employee_departments` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `department_id` as an integer, which will be a foreign key referencing `department_id` in the `departments` table.
   - Set a composite primary key on the combination of `employee_id` and `department_id`.
# Screenshot and Structure sample:
![Image](https://github.com/user-attachments/assets/3b14d862-54fe-4b53-80a5-c4c4cbe80dda)
![Image](https://github.com/user-attachments/assets/78408b8b-c1fc-49c1-89d9-7414087f5a3a)

4. Create the `employee_projects` table:
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
   - Define `project_name` as a VARCHAR (up to 255 characters), and make it not null.
# Screenshot and Structure sample:
![Image](https://github.com/user-attachments/assets/72416c32-b9c9-42a4-8bb3-f87d55e4ea6b)
![Image](https://github.com/user-attachments/assets/a168f6f5-9b5e-4498-9229-a0d3809c56a3)

5. Create the `managers` table:
   - Define `manager_id` as a unique integer, auto-increment, and primary key.
   - Define `employee_id` as an integer, which will be a foreign key referencing `employee_id` in the `employees` table.
# Screenshot and Structure sample:
![Image](https://github.com/user-attachments/assets/2068d41a-242d-4ab8-a5c7-c2ffa7098a92)
![Image](https://github.com/user-attachments/assets/8e1a3bf3-a368-4a41-b889-ffc09f969755)

# ER Diagram sample:
![Image](https://github.com/user-attachments/assets/def7db96-e570-4294-8b63-3c93ef340e97)

[BACK TO PORTFOLIO](https://chan-edm.github.io/README/)
