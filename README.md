# Group B1 MIST4610 Group Project #1

## Team Name: 
Section 47114 Group B1

## Team Members & Roles:
1. Jacob Dillon [@JDillon](https://www.github.com/JDillon-MIS) - Group Leader
2. Jenjen Lin [@JLin](https://github.com/J2Lin) - SQL Writer
3. Graham Nash [@GNash](https://github.com/grahamenash) - Conceptual Modeler
4. Ved Cholleti [VCholleti](NoAccountProvided) - Database Designer/Data Wrangler

## Case Description:

For this case, we were tasked with modeling and creating a relational database for the Wilderness Exploration Society (WES) at Peachtree State University (Georgia) to help them manage their equipment rentals and trip registrations in accordance with their relevant procedures. After modeling the relational database, generating sample data for it, and populating it with said data, this database will allow us to run SQL queries on its data in order to recieve beneficial insights into the past and present activities of WES customers from the recorded equipment rental and trip registration operations within the Wilderness Exploration Society.
<br/> Since certain pieces of equipment and types of trips will likely be more desirable to customers during specific events and holidays, we decided to extend this project by adding the capability to track and apply deals to the rental prices of various types of equipment and the fees associated with the different types of trips the WES offers. This extension is modeled by our addition of the Deals entity and the associative entities EquipmentTypeDeal and TripTypeDeal.

## Data Model:

<img width="1515" height="1025" alt="image" src="https://github.com/user-attachments/assets/0c36c922-2df9-41d0-afec-af689506a093" />
<br/>

### Explanation of Entity Relationships:

<img width="1987" height="1705" alt="image" src="https://github.com/user-attachments/assets/991d9983-3353-44f4-91fc-44848201cb0e" />


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

<img width="1492" height="470" alt="image" src="https://github.com/user-attachments/assets/4c3c2459-7496-405a-80e1-5817c0e2e62c" />


## Ten Queries:

QUERY MATRIX:

<img width="492" height="363" alt="image" src="https://github.com/user-attachments/assets/d188fc19-c758-4882-92a9-5b92e5e5ee87" />



1. The condition of equipment items are rated on a scale from 1-4, with 1 being poor and 4 being great. Which equipment items are in poor condition?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/f7ae94c5-489f-4855-b258-22716b23ef31" />

Query 1 helps managers easily identify equipment items that will need to be repaired or replaced.

2. Which customers have a sponsor?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/ae9539e0-7c21-4d87-bd65-589b7a1f4466" />

Query 2 helps staff determine which customers qualify for the guest discount.

3. What is the average trip length of all trips that have a difficulty level of "Easy"?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/bafda13c-68bf-4585-98b2-58045b2c14e2" />

Query 3 helps management give customers an idea of how much of a time commitment an easy trip will be.

4. What is the name of the staff leader assigned to the scheduled trip with id 3?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/af38dc5e-8103-4ef8-b5f0-079473ec5424" />

Query 4 helps management identify who will be out of the office during the scheduled trip with id 3 so that they won't be assigned to another trip during that time.

5. Which trip types have the most total sign-ups?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/93318b11-6101-4e1b-99de-7ef090c36bae" />

Query 5 both helps management identify which trips are the most popular with customers, and tells them which trips they should focus their advertising on.

6. If qualification for the Loyalty Reward Deal is deemed by participation in 2 or more trips, then which customers would qualify? 

<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/995fb554-45cb-440c-8e3a-5d813aa4b76c" />

Query 6 helps management both identify which of their customers are eligible for the loyalty reward deal and determine if the number of trips required for said deal should be changed to adjust how many customers are eligible for it.

7. What is the total revenue generated from fees by each trip type?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/5ed883ba-2dc3-4fa9-954c-1179e3d004db" />

Query 7 helps management identify which trip types are thier most profitable so that they can prioritize offering more of them in their future schedules.

8. Which staff members are acting as assistant staff for three or more trips?

<img width="600" height="700" alt="image" src="https://github.com/user-attachments/assets/49f8c2dd-f6b4-48a8-97d0-9953d683399f" />

Query 8 helps management identify candidates that are due for promotion from staff assistant to staff leader after the trips have concluded.

9. Which deals have a discount amount that is greater than the average discount amount of all deals?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/fe914ff3-21af-4f9c-8373-2503795c16bd" />

Query 9 helps management find unusually generous deals so that they can determine if they are appropriate to keep.

10. Which customers have returned their equipment rentals late at least once?

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/344a4503-5d70-4e57-8823-64e555f3addc" />

Query 10 helps management identify which of their customers are returning rentals late and how many times they have done so. This can alsp help management decide if they need to start giving them reminders or adding penalties to their return policy.


## Database Information:

Database Name: mb_B1

Other Information: *All of the queries listed above are bookmarked in the database as stored procedures using the **GP_Q#** format*
