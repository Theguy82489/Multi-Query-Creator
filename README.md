# Multi-Query-Creator
I recently finished a project that allows you to take data from an excel and create multiple SQL statements. This is used to transferring old excel data to a database.

### **Step 1**
***
Copy Excel data to notepad and save.

![](https://github.com/Theguy82489/Multi-Query-Creator/blob/master/Example%20-%20Step%201.png)

***

### **Step 2**
***
Select Browse and navigate to text file from step 1.

![](https://github.com/Theguy82489/Multi-Query-Creator/blob/master/Example%20-%20Step%202.png)

***

### **Step 3**
***
Copy the below query into the editor. Select Okay and choose file name and select Save.

**_Insert Into Customer (f_name, l_name, dob) Values ('@p1', '@p2', '@p3')_**

![](https://github.com/Theguy82489/Multi-Query-Creator/blob/master/Example%20-%20Step%203.png)

***

### **Step 4**
***
Copy rows to SQL New Query and then Excecute.
