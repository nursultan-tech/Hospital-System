## Creating the UNF table

<br>
You can see the queries for creating the unformed table and inserting all of the values that we created here!
<br><br>
  
   ``` sql
    CREATE TABLE Hospital_Patient_Record (
    patient_tc_no VARCHAR(11) NOT NULL,
    patient_first_name VARCHAR(30) NOT NULL,
    patient_last_name VARCHAR(30) NOT NULL,
    patient_dob date NOT NULL,
    patient_sex VARCHAR(6) NOT NULL,
    patient_mail VARCHAR(45) DEFAULT NULL,
    patient_phone VARCHAR(10) DEFAULT NULL,
    patient_address_building_no VARCHAR(20) NOT NULL,
    patient_address_street VARCHAR(20) NOT NULL,
    patient_address_neighbourhood VARCHAR(20) NOT NULL,
    patient_address_district VARCHAR(20) NOT NULL,
    patient_blood VARCHAR(3) NOT NULL,
    patient_allergies VARCHAR(50) DEFAULT 'no allergies',
    doctor_id INT NOT NULL,
    doctor_first_name VARCHAR(30) NOT NULL,
    doctor_last_name VARCHAR(30) NOT NULL,
    doctor_sex VARCHAR(6) NOT NULL,
    doctor_phone VARCHAR(10) DEFAULT NULL,
    doctor_mail VARCHAR(45) DEFAULT NULL,
    doctor_clinic VARCHAR(30) NOT NULL,
    doctor_working_days VARCHAR(9) NOT NULL,
    nurse_id INT DEFAULT NULL,
    nurse_first_name VARCHAR(30) DEFAULT NULL,
    nurse_last_name VARCHAR(30) DEFAULT NULL,
    nurse_sex VARCHAR(6) DEFAULT NULL,
    nurse_phone VARCHAR(10) DEFAULT NULL,
    nurse_mail VARCHAR(45) DEFAULT NULL,
    nurse_clinic VARCHAR(30) DEFAULT NULL,
    diagnosed_disease VARCHAR(30) DEFAULT NULL,
    doctor_comment TEXT DEFAULT NULL,
    recommended_medicine VARCHAR(30) DEFAULT NULL,
    allergenic_ingridient VARCHAR(30) DEFAULT NULL,
    check_date DATETIME DEFAULT NULL,
    rest_room_block VARCHAR(5) DEFAULT NULL,
    rest_room_floor VARCHAR(3) DEFAULT NULL,
    rest_room_no VARCHAR(5) DEFAULT NULL,
    analysis_type VARCHAR(30) DEFAULT NULL,
    analysis_result TEXT DEFAULT NULL,
    next_appointment DATETIME DEFAULT NULL
    );

    
