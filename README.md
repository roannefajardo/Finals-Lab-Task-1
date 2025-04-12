# [Finals-Lab-Task-1](https://github.com/user-attachments/files/19719335/FajardoFLT1.docx)
This portfolio demonstrates foundational MySQL skills using a multi-tiered company database. It covers writing SQL queries, designing table structures, and creating an ER diagram or relational schema. The portfolio also includes SQL scripts for the database and its tables, showcasing the setup and structure.

## Step-by-Step Instructions

1. **Create the `employees` table:**
   - `employee_id`: Integer, auto-incremented, primary key.
   - `employee_name`: VARCHAR(255), not null.
   - `manager_id`: Integer, foreign key referencing `employee_id` in the same table.

2. **Create the `departments` table:**
   - `department_id`: Integer, auto-incremented, primary key.
   - `department_name`: VARCHAR(255), not null.

3. **Create the `employee_departments` table:**
   - `employee_id`: Integer, foreign key referencing `employees.employee_id`.
   - `department_id`: Integer, foreign key referencing `departments.department_id`.
   - Composite primary key: (`employee_id`, `department_id`).

4. **Create the `employee_projects` table:**
   - `employee_id`: Integer, foreign key referencing `employees.employee_id`.
   - `project_name`: VARCHAR(255), not null.

5. **Create the `managers` table:**
   - `manager_id`: Integer, auto-incremented, primary key.
   - `employee_id`: Integer, foreign key referencing `employees.employee_id`.

# Screenshots

## SQL Query Outputs

1. **Employees Table**  
- ![Image](https://github.com/user-attachments/assets/aa194064-c90b-445f-9dbe-b1c457283db7)
2. **Departments Table**  
- ![Image](https://github.com/user-attachments/assets/2e58fea6-4f4b-4573-8c9e-5c781342e4ea)
3. **Employee-Department Table**  
- ![Image](https://github.com/user-attachments/assets/190c28f6-c19b-4ca7-855b-a3f7084ffdfe)
4. **Employee Projects Table**  
- ![Image](https://github.com/user-attachments/assets/2601769d-bd67-499c-9dca-cb54c5995868)
5. **Managers Table**  
- ![Image](https://github.com/user-attachments/assets/2acd1297-2b8a-4dbc-b37a-9b0e21f17107)

## Table Structure

1. **Employees Table**  
- ![Image](https://github.com/user-attachments/assets/17c8a746-843a-4ac5-841a-253749f7aea2)
2. **Departments Table**  
- ![Image](https://github.com/user-attachments/assets/d7ffa8ae-1e6d-42a6-8870-7b2e02f54a84)

3. **Employee-Department Table**  
- ![Image](https://github.com/user-attachments/assets/71dc899d-4fec-4a00-8d52-8ad1dc91b376)

4. **Employee Projects Table**  
- ![Image](https://github.com/user-attachments/assets/adceae29-432c-461f-b158-d78cd44062ca)
5. **Managers Table**  
- ![Image](https://github.com/user-attachments/assets/e48696ef-b012-4232-9b2c-08336c64b3e5)

## EER Diagram
- ![Image](https://github.com/user-attachments/assets/8cc1be07-19ee-4e7f-bfa7-f46d97f7b2fa)
