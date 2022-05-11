The following programme is a hands on implementation of the ER diagram provided.
This programme shows the operations of a hospital where the various staff and patients,
how they interact with each other and perform receptionist and staff operations.

The database Has been designed using SQLite3 and SQL code and the user interaction has been written in python.
In the database, there are seven tables created And their structure has been demonstrated as follows.

TABLE STRUCTURE
    ->The first table patient and keeps track of all the patients in the hospital.
    
    ->The patient's table keeps track of all the patients, names, addresses and phone numbers
    
    ->the appointments table keeps track of all the patients and their doctors appointments. 
    
    ->The healthcare table is a table to keep a record of all the doctors and nurses,
      and they can either be occupied or unoccupied.
    
    ->Now all the healthcare staffs can either be doctors and nurses. So there are separate tables created for them as well.


    ->The prescription table consists of the prescriptions assigned 
        by the doctor to the patient. And once the prescription gets assigned, 
        their reference will be updated into the appointment schedule table.


PYTHON CODE
    ->The program follows object oriented principles and uses respective classes for respective operations.
    
    ->The programme also handles errors properly and they have been labelled so that the user can enter the proper inputs.
    
    ->There are three classes, the patient class, the staff class and the display class
        and their role is to perform various operations on the type of class they belong.


PROGRAM WORKFLOW

Let's discuss the work flow:

    ->Initially, there is a dashboard asking Either to 
    
    ->log in or create account or view the doctors and the nurses
    
    ->One can create a stop account. One can create a patience account. 
    
    ->The database is initially empty.
    
    ->To get an appointment, we need to create a patient account. 
    
    ->And also, there should be a doctor available in the health care department. 
    
    ->If there is no doctor and appointment cannot be assigned.
    
    ->after the patient books for an appointment, 
    
    ->the state of staff is marked as occupied and unless the staff gives 
    
    ->the prescription to the patient, the staff shall not be free.
    
    ->Both the patients and the staff can view their previous appointments, 
    
    ->considering the fact that those have been completed.
    
    ->A patient may even cancel the appointment.


HOW TO RUN THE CODE
    ->Medical Hospital Database Console Based Application

    ->in the console, type  'python hospital.py'

    ->Non prompting static Python app(App will quit on completion of a task)
    
    ->Loops are not used to avoid call stack errors
    
    ->One will need to re - run the application for each task
    
    ->Error Handling is done optimally 
    
    ->And If invalid inputs are entered by the user 
    
    ->The respective error codes will be displayed or a message would be shown stopping the application
