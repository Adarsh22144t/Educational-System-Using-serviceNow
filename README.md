# Educational Management System using ServiceNow

This project demonstrates the development of an Educational Management System on the ServiceNow platform. It streamlines key operations such as student admissions, academic progress tracking, and administrative management using ServiceNow capabilities like tables, forms, client scripts, workflows, and update sets.

---

## Project Setup and Implementation

### Step 1: Creating an Update Set

- Created an update set named **Educational Organization**.
- Captures and transports all ServiceNow customizations.

![image](https://github.com/user-attachments/assets/75690b28-3628-478e-9611-63bad1bc26c5)


---

### Step 2: Creating Tables

- **SalesForce Table**: Base table for records.
- **Admission Table** (extends SalesForce): For student admission data.
- **Student Progress Table** (extends SalesForce): For tracking academic performance.

![image](https://github.com/user-attachments/assets/fd820114-8058-4b27-b001-21feaa046b69)
  
![image](https://github.com/user-attachments/assets/e693bb82-a260-40d5-ac83-607c9f0445bc)
 
![image](https://github.com/user-attachments/assets/4c0aa8a0-1f07-48e9-a402-f033173e8045)


---

### Step 3: Form Layout Configuration

- Configured form layout for the **Student Progress Table**.
![image](https://github.com/user-attachments/assets/0c720dd3-54ec-46ce-ba4a-9c19f0d42350)


---

### Step 4: Form Design

Designed form layouts for each table to provide structured data entry:

- **SalesForce Table**

  ![image](https://github.com/user-attachments/assets/e2f3a207-33df-49cf-a183-596ea8142b18)


- **Admission Table**

![image](https://github.com/user-attachments/assets/c0f0db07-ba09-4cb5-8835-93c01480abd4)


- **Student Progress Table**

 ![image](https://github.com/user-attachments/assets/9861ccad-7a3c-453f-a3e3-87a2318ae2ac)


---

### Step 5: Number Maintenance

- Implemented auto-generation of **Admin Number** using number maintenance.

![image](https://github.com/user-attachments/assets/a4583f0d-d3e9-43ce-8c29-c8fe8c482df4)


---

### Step 6: Process Flow for Admissions

- Created a process flow for the Admission Table.
- Flow: `InProgress` → `Joined` → `Rejected` → `Rejoined` → `Closed` → `Cancelled`

![image](https://github.com/user-attachments/assets/26d9fb65-14bd-497a-975e-2383859bd8c5)


---

### Step 7: Client Scripts

Several client scripts were implemented to enhance interactivity:

1. **Auto Populate** – Prefills fields in the Admission Table  
   ![image](https://github.com/user-attachments/assets/da81e2dd-9123-48b6-b0b0-88c8fa8595b0)


2. **Pincode Update** – Updates fields based on pincode  
  ![image](https://github.com/user-attachments/assets/50076564-64c1-4407-baeb-45a2d8412021)


3. **Disable Fields** – Prevents edits on specific fields in Student Progress Table 

4. **Total Update** – Computes total marks 

5. **Result** – Calculates Pass/Fail

6. **Percentage** – Calculates percentage

---

## Results

The Educational Management System was successfully developed and deployed in the ServiceNow environment. All components worked as expected, including:

- Tables for storing and managing admission and student progress data.
- Customized forms and layouts to streamline data entry.
- Automated workflows for the admission process lifecycle.
- Client scripts that enhanced functionality such as field auto-fill, result computation, percentage calculation, and disabling inputs.

The system ensures seamless management of academic records and can be further extended for additional modules like attendance tracking or fee management.

![image](https://github.com/user-attachments/assets/a15c1456-b8fa-4887-97e4-46d92e1f55a3)
![image](https://github.com/user-attachments/assets/f08e681e-9710-4319-ac24-3d6077e051e9)
![image](https://github.com/user-attachments/assets/f5ab9e74-4ee8-4c63-a494-dfdab96b9ff7)
![image](https://github.com/user-attachments/assets/d40c64dd-670e-4d2b-b05d-22fba3f7e629)
![image](https://github.com/user-attachments/assets/df587abf-050a-4bda-9f57-de5f4294e005)







---

## Conclusion

The Educational Management System built on ServiceNow illustrates a practical use of platform capabilities beyond IT services. It enables educational institutions to digitize and automate their admission and academic processes efficiently. By integrating structured tables, process workflows, and intelligent scripts, this project offers a scalable, user-friendly administrative solution.
