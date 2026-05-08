# Polycystic Ovary Syndrome System

**DESCRIPTION:**  
The Polycystic Ovary Syndrome (PCOS) problem is well-suited for solving using Object-Oriented Programming (OOP), as it involves different types of data and processes that can be organized into classes. OOP allows structuring the program in a modular, reusable, and easy-to-maintain project, which facilitates the analysis and prediction of the probability of a woman having PCOS.
The purpose of this program is to develop a tool capable of making an approximate prediction of the probability that a woman has PCOS, based on the analysis of certain data provided by the user. It also aims to generate and display representative statistics from the collected records, allowing for the identification of possible patterns, trends, and factors associated with its condition.
  
<br/>
<br/>
    
**USE:**  
The program allows to analyze hormonal data and clinical characteristics of a patient to estimate the probability of having Polycystic Ovary Syndrome (PCOS). To use the system, the user enters or loads key information such as age, hormone levels (LH, FSH, AMH, TSH, PRL), and clinical measurements.
The workflow consists of entering the data, storing it, and running the comparison and prediction methods to obtain useful clinical analyses regarding the probability of PCOS.

<br/>

The user can do the following:
1. Register new patients by creating objects of the Paciente class:
	- Enter the selection number (1).
    - Enter the patient's data.
    - Wait for the confirmation message that the patient was added successfully.

 <br/>
 
2. Save the records in BaseDatosPacientes, which functions as the system's database. From here, two options are presented:
	- Filter:
		- Enter the selection number (2).
		- Enter the name of the patient being searched for.
		- Wait for the data to be printed.

	- Delete:
		- Enter the selection number (3).
		- Enter the name of the patient to be deleted.
		- Wait for the confirmation message that the patient was successfully deleted.

<br/>

3. Apply the prediction method contained in the PacienteSOP subclass to obtain an approximate probability of PCOS:
	- Enter the selection number (4).
	- Enter the patient's name.
	- Wait for the results indicating whether or not there is a probability of having PCOS.

<br/>

4. Generate hormonal statistics to identify differences between the analyzed groups:
	- Enter the selection number (5).
	- Select the group to analyze:
		- Group with PCOS:
			- Enter the selection number (1).
			- Wait for the results showing the number of patients with PCOS.

		- Group without PCOS:
			- Enter the selection number (2).
			- Wait for the results showing the number of patients without PCOS.

<br/>


*Enter the selection number (6) to exit the program.*
