# FCCU-SQL-Flex_funds
Flex_funds table from Payroll Eligibility status in SQL Server database


CREATE TABLE [Subscription_Payroll_Enrollment_Change_Log](
id INT NOT NULL,
Member_No_Before INT NOT NULL,
Member_No_After INT NOT NULL,
Individual_Id_Before INT NOT NULL,
Individual_Id_After INT NOT NULL, 
Status_Before INT NOT NULL,
Status_After INT NOT NULL,
Enroll_Date_Before DATETIME2 NOT NULL,
Enroll_Date_After DATETIME2 NOT NULL, 
Current_Advance_Date_Before DATETIME2 NOT NULL,
Current_Advance_Date_After DATETIME2 NOT NULL,
CurrentAdvAmt_Before INT NOT NULL, 
CurrentAdvAmt_After INT NOT NULL, 
Restricted_Before VARCHAR(50) NOT NULL,
Restricted_After VARCHAR(50) NOT NULL,
Unenroll_Date_Before DATETIME2 NOT NULL,
Unenroll_Date_After DATETIME2 NOT NULL,
Company_Name_Before VARCHAR(50) NOT NULL,
Company_Name_After VARCHAR(50) NOT NULL,
Run_Date_Time DATETIME2 NOT NULL, 
);
