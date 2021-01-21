# Healthcare-Analytics
<img src = 'image/healthcare.jpg'>

# Problem Statement
Recent Covid-19 Pandemic has raised alarms over one of the most overlooked area to focus: Healthcare Management. While healthcare management has various use cases for using data science, patient length of stay is one critical parameter to observe and predict if one wants to improve the efficiency of the healthcare management in a hospital.
This parameter helps hospitals to identify patients of high LOS risk (patients who will stay longer) at the time of admission. Once identified, patients with high LOS risk can have their treatment plan optimized to miminize LOS and lower the chance of staff/visitor infection. Also, prior knowledge of LOS can aid in logistics such as room and bed allocation planning.
Suppose you have been hired as Data Scientist of HealthMan – a not for profit organization dedicated to manage the functioning of Hospitals in a professional and optimal manner.
The task is to accurately predict the Length of Stay for each patient on case by case basis so that the Hospitals can use this information for optimal resource allocation and better functioning. The length of stay is divided into 11 different classes ranging from 0-10 days to more than 100 days.

# Data Description
traindata.csv – File containing features related to patient, hospital and Length of stay on case basis 
traindata_dictonary.csv – File containing the information of the features in train file

The training dataset consists of data corresponding to 318438 customers and the test dataset consists of 137000 customers. Following are the features of the dataset

   - case_id	- Case_ID registered in Hospital
   - Hospital_code - Unique code for the Hospital
   - Hospital_type_code - Unique code for the type of Hospital
   - City_Code_Hospital - City Code of the Hospital
   - Hospital_region_code -	Region Code of the Hospital
   - Available Extra Rooms in Hospital - Number of Extra rooms available in the Hospital
   - Department	Department - overlooking the case
   - Ward_Type - Code for the Ward type
 - Ward_Facility_Code - Code for the Ward Facility
 - Bed Grade - Condition of Bed in the Ward
 - patientid - Unique Patient Id
 - City_Code_Patient - City Code for the patient
 - Type of Admission - Admission Type registered by the Hospital
 - Severity of Illness - Severity of the illness recorded at the time of admission
 - Visitors with Patient - Number of Visitors with the patient
 - Age - Age of the patient
 - Admission_Deposit - Deposit at the Admission Time
 - Stay -	Stay Days by the patient (Target)



Predict how long patient is going to stay in hospital as per severity of illness
