                                                         Readme file
														 
Arunav Dutta : MT18156
Bandana prasad: MT18158
Sagar Gupta : MT18174							 						 
		

There are basically 9 classes in our program that are mentioned below:

1. Doctor_registration
2. patient_registration
3. Register
4. Patient_login
5. Doctor_login
6. Admin
7. Support_staff
8. Hospital
9. Department

Each classes contain different methods and having various attributes that are necessary for proper functioning of the entire program.

1. Doctor_registration :
 
  This class contain various attributes like name, email_id, phone_no, address, schedule, age,password,position,department,specialization,surgeon,timings  etc. 
  
  Methods of Doctor_registration class is :
    
     1. Save_doctor()

2. Patient_registration :
 
   This class contains various attributes like name, patient_ID , age, email, password, phone, requirement, location, assigned_doctor,visiting_date
                                               discharging_date, prescribed_medicine,test , disease_identified etc. 
        			 
	Methods of Patient_registration class is :

     1. get_getails()
     2. save_patients()
     3. Patient_reg()
     4. check_patient()
	 
3. 	Register :

    This class contain various attributes like name, age, phone, email_id , password etc.
	
4. Patient_login :

   This class contains attributes like name and id.
   
   Methods of Patient_login class is :
    
	 1. patient_chk()
	 
5. Doctor_login :
 
    This class contain various attributes like dr_login_name and dr_email_id.
	
	Methods of Patient_login class is :
	
	 1. dr_chk()
	 
6. Admin :

    This class contain various attributes like name, email_id, password etc.

7. Support_staff :
    
    This class contain various attributes like name, age, phone_no, position etc.
	
8. Hospital :

    This class contain various attributes like department_list, doctors_list, patient_list etc.	
	
9. Department :

    This class contain various attributes like name, id, no_of_doctors, HOD, list_of_doctors etc.	
	
	
	
	ASSUMPTIONS :
	
1. Both doctors and patients have access to the patient database..
2. On the basis of symptoms mentioned by the patient, they will be alloted doctors.
3. On the basis of their doctor's department, unique-id will be alloted to the patients.	
4. The timings(in and discharge) will be entered by the Doctor.
5. The slot booking is done immediately once the patient got registered.
6. The patient registration number will be the first four letter of the department and the serial number.
7. The doctor is at work for all seven days.
8. All the dates are in the form dd/mm/yyyy.
9. The timing are in the form of 3/ 4 digit number , e.g 1700 for 5 pm.
10. The allotment of patient registration number is to done before the slot booking.

     
	
  
      
	 
	
	
	
	
	
	
	
	


	
	
     
  
      

     
  	 