# veri-taban--4.-hafta<img width="1920" height="1080" alt="columns" src="https://github.com/user-attachments/assets/0a09c531-baa6-4dad-a006-a8138ea30d58" />
-create table Customer(
customer_id int primary key, customer_name nchar, customer_adress nchar)
-create table Collector(
collector_id int, collector_name nchar)
-create table LoanContract(
contract_id int primary key, Datecontractstars date, Datecontractends date, Interestrate int, Loanamount int, Loanpaymentamountdue int, Loanpaymentfrequency int, Loanpaymentduedate date)
-create table Payment(
payment_id int primary key, Dateofpayment date, amountofpayment int, remarks nchar)
acreate table Paymenttype(
payment_type_code int primary key, payment_type_description nchar)
malter table Payment
alter column remarks varchar (10);
aalter table LoanContract
add collectorID int add customerNumber int¿
-alter table Payment
add contractID, payment_type_code int;