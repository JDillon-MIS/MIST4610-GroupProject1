# Group B1 MIST4610 Group Project #1

## Team Name: 
Section 47114 Group B1

## Team Members & Roles:
1. Jacob Dillon [@JDillon](https://www.github.com/JDillon-MIS) - Group Leader
2. Jenjen Lin [@JLin](https://github.com/J2Lin) - SQL Writer
3. Graham Nash [@GNash](https://github.com/grahamenash) - Conceptual Modeler
4. Ved Cholleti ... - Database Designer/Data Wrangler

## Case Description:

For this case, we were tasked with modeling and creating a relational database for the Wilderness Exploration Society (WES) at Peachtree State University (Georgia) to help them manage their equipment rentals and trip registrations in accordance with their relevant procedures. Along with modeling the relational database, generating sample data for it, and populating it with said data we extended the project by adding in the capability to track and apply different deals to the different types of equipment that customers are likely to rent during a given event or holiday. Ultimately, this populated database will permit us to run SQL queries on its data in order to recieve beneficial insights into the past and present activities of WES customers from their recorded equipment rental and trip registration operations with the Wilderness Exploration Society.

## Data Model:

<img width="1910" height="1715" alt="4610_GP1_Model1" src="https://github.com/user-attachments/assets/4b583c41-9b34-4c26-be0d-756891dd44ef" />

<br/> Explanation of Entity Relationship:

<img width="2002" height="1535" alt="image" src="https://github.com/user-attachments/assets/f9fabdc3-7ee9-424d-afc5-e0b30c6df5fa" />



## Data Dictionary:

<img width="1215" height="932" alt="GP1_DataDict_1" src="https://github.com/user-attachments/assets/e584bd6d-6f84-4242-a196-a0bd24d5e9db" />

<img width="1205" height="522" alt="GP1_DataDict_2" src="https://github.com/user-attachments/assets/fbf35bc7-b0d3-4d31-be35-21fae4f88975" />

<img width="1212" height="915" alt="GP1_DataDict_3" src="https://github.com/user-attachments/assets/ad6aa4cc-ba9c-4f4f-ab4e-c992f7d26745" />

<img width="1210" height="565" alt="GP1_DataDict_4" src="https://github.com/user-attachments/assets/1789c5d8-0b3d-4712-b6ba-851ac143b363" />

<img width="1207" height="730" alt="GP1_DataDict_5" src="https://github.com/user-attachments/assets/8cdbf59b-2f00-4fb1-8cb5-9fd8ffea71cf" />

<img width="1210" height="610" alt="GP1_DataDict_6" src="https://github.com/user-attachments/assets/4ae1b66e-216d-4e02-8d3a-39dbe3e012ee" />

<img width="1215" height="890" alt="GP1_DataDict_7" src="https://github.com/user-attachments/assets/0a2e19bc-8638-4d15-b32a-3f5c208d1859" />

<img width="1215" height="345" alt="GP1_DataDict_8" src="https://github.com/user-attachments/assets/0bbf6dd8-dfca-48d9-84c4-ad8da2648806" />

<img width="1205" height="595" alt="GP1_DataDict_9" src="https://github.com/user-attachments/assets/717eca19-63e3-478d-9acb-337006c5e731" />

<img width="1202" height="430" alt="GP1_DataDict_10" src="https://github.com/user-attachments/assets/5d753b92-6370-4182-b959-d7e4a07dec9f" />

<img width="1220" height="720" alt="GP1_DataDict_11" src="https://github.com/user-attachments/assets/33e65898-7ddd-4b14-a2b3-b9c3633477cd" />

<img width="1230" height="620" alt="GP1_DataDict_12" src="https://github.com/user-attachments/assets/1427f0fc-a919-4ddb-ba1a-33d51472e0d6" />


## Ten Queries:

Insert Screenshot of matrix here.

1. The condition of equipment items are rated on a scale from 1-4, with 1 being poor and 4 being great. Which equipment items are in poor condition?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/f7ae94c5-489f-4855-b258-22716b23ef31" />

Query 1 helps managers easily identify equipment items that will need to be repaired or replaced.

2. Which customers have a sponsor?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/ae9539e0-7c21-4d87-bd65-589b7a1f4466" />

Query 2 helps staff determine which customers qualify for the guest discount.

3. What is the average trip length?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/55f9d507-3a79-4dba-a55e-7bfa1996d5c3" />

Query 3 helps management determine whether the current staffing numbers are sufficient or additional staff needs to be hired for trips.


4. What is the name of the staff leader assigned to the scheduled trip with id 3?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/af38dc5e-8103-4ef8-b5f0-079473ec5424" />

Query 4 helps management identify who will be out of the office during the scheduled trip with id 3 so that they won't be assigned to another trip during that time.


5. 

...

Query 5 helps...

**WIP** - *For each query, provide: 
      a question & its managerial justification,
      the relevant SQL code & its results, 
      and a matrix indicating which features it covers*


## Database Information:

Database Name: mb_B1

Other Information: *All of the queries listed above are bookmarked in the database as stored procedures using the **GP_Q#** format*
