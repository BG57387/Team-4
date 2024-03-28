# Team Name 21484 Project
MIST 4610, Team 4 Project #1
<br/>
<br/>

# Team Members 

1. Ashley Park [Ashley Park](https://github.com/ap86129) <br/>
2. Izzie Paden [Izzie Paden](https://github.com/izziepaden) <br/>
3. Carter Kowalski [Carter Kowalski](https://github.com/carterkowalski1) <br/>
4. Bharat Gupta [Bharat Gupta](https://github.com/BG57387) <br/>

<br/>

# **Problem Description**<br/>
The project at hand is to conceptualize and develop a relational database for the dynamic operations of an Ostrich Racing Club. This database is structured around the central entity of the Ostrich table. Ostrich being each bird that is raced in the racing events hosted. In parallel, the Facility entity is crucial as it details each racing arena and training ground we maintain. Alongside these, we track the Visitor entity to log guests and bettors attending races, their interactions, and preferences. Critical associations include linking Ostriches to their Trainers, Races they participate in, and the Results they achieve
, as well as connecting Visitors to the Events they attend. The database will store comprehensive data on these entities and their attributes to simulate real-world scenarios. We aim to deploy advanced queries from the data, offering deep insights into club operations, visitor engagement, and other relationships occurring in the racing club.  The ultimate goal is to leverage this database to streamline all functions of the races and related events.

To create a coherent data model for an ostrich racing club, understanding the relationships between entities is crucial. Here's an outline of potential relationships within the given entities:<br/>
These relationships form the backbone of the database and dictate how data is interconnected. Properly defined relationships ensure the database is normalized, reducing redundancy and improving data integrity. For each Many-to-Many relationship, a junction (or associative) table is necessary to handle the associations between the entities effectively.
<br/>
<br/>

# **Data Model**

![Final](https://github.com/BG57387/Team-4/assets/150160324/6fbd90ff-535a-429e-a576-6954485976b3)

<br/>
<br/>


# **Data Model Explanation**<br/>
Our data model is structured to mirror the vibrant ecosystem of an ostrich racing club, where the interplay between ostriches, jockeys, and trainers translates into a series of detailed and interconnected relationships. At the heart of this model is the Ostrich entity, signifying each racing bird housed within our club. Every ostrich is paired with a dedicated Jockey, establishing a one-to-many relationship as each jockey can ride multiple ostriches, but each ostrich is ridden by a single jockey in races.

The Ostriches are also linked to Training Sessions in a one-to-many relationship, indicating that each ostrich participates in numerous training activities designed to enhance their performance. Correspondingly, Trainers are connected to Training Sessions, as a single trainer may conduct multiple sessions for various ostriches, honing their skills for upcoming races.

As for the Races themselves, we see a many-to-many relationship with both Ostriches and Jockeys, as numerous ostriches can compete in multiple races, often ridden by different jockeys. Each race, a thrilling spectacle of speed and agility, yields numerous Race Results, depicted by a one-to-many relationship, capturing the outcome and statistics for each participating ostrich.

Visitors, vital to the club's vibrancy, partake in these races, manifesting a many-to-many relationship that highlights the dynamic interaction as visitors attend various races. Our Facilities play a pivotal role, with a one-to-many relationship to Races and Social Events, illustrating that a single facility may host numerous races and events, offering diverse experiences to our patrons.

Social Events, vibrant gatherings sponsored by business entities, showcase a one-to-many relationship with Sponsors, who support various events to enhance their visibility and engagement. These events also connect to Staff Members through a many-to-many relationship, reflecting the myriad of roles staff undertake during events, from coordination to execution.

Lastly, Staff Members' schedules are intricately managed, presenting a one-to-many relationship with Staff Schedules. Each staff member has a specific schedule, defining their roles, shifts, and duties. This comprehensive model is crafted to ensure a seamless and integrated operation of the club, ensuring a cohesive experience for all, from the ostrich races to the social events, all within our racing facilities.
<br/>
<br/>

# **Data Dictionary**
<img width="742" alt="Screenshot 2024-03-27 at 4 12 11 PM" src="https://github.com/BG57387/Team-4/assets/141380431/56bb40fa-c172-4efd-921b-b1e84654019d">
<br/>
<br/>
<img width="756" alt="Screenshot 2024-03-27 at 4 12 24 PM" src="https://github.com/BG57387/Team-4/assets/141380431/1573ca92-8f70-4b7f-a482-1ae48bb27d32">
<br/>
<br/>
<img width="757" alt="Screenshot 2024-03-27 at 4 12 40 PM" src="https://github.com/BG57387/Team-4/assets/141380431/499d6274-4778-480d-8df7-a43fa150782f">
<br/>
<br/>
<img width="745" alt="Screenshot 2024-03-27 at 4 12 58 PM" src="https://github.com/BG57387/Team-4/assets/141380431/1addd1e0-feb1-4aa2-a718-4d38f6328ce0">
<br/>
<br/>
<img width="757" alt="Screenshot 2024-03-27 at 4 13 12 PM" src="https://github.com/BG57387/Team-4/assets/141380431/47646687-3027-4212-94cc-6a89b266babf">
<br/>
<br/>
<img width="745" alt="Screenshot 2024-03-27 at 4 13 24 PM" src="https://github.com/BG57387/Team-4/assets/141380431/5903b6cd-ad2b-4983-94cd-f9cf336120f9">
<br/>
<br/>
<img width="746" alt="Screenshot 2024-03-27 at 4 13 36 PM" src="https://github.com/BG57387/Team-4/assets/141380431/8f83e6c2-7e84-4a6d-8aeb-b7be1a4f593d">
<br/>
<br/>
<img width="747" alt="Screenshot 2024-03-27 at 4 13 48 PM" src="https://github.com/BG57387/Team-4/assets/141380431/e58ca9d4-67a3-4df0-bc2f-52261f8029d7">
<br/>
<br/>
<img width="719" alt="Screenshot 2024-03-27 at 4 13 58 PM" src="https://github.com/BG57387/Team-4/assets/141380431/f84294cc-422e-4c83-864d-00ed1c74f469">
<br/>
<br/>
<img width="737" alt="Screenshot 2024-03-27 at 4 15 48 PM" src="https://github.com/BG57387/Team-4/assets/141380431/a4a03b3e-39eb-404b-9608-3f3556d64781">
<br/>
<br/>
<img width="737" alt="Screenshot 2024-03-27 at 4 15 58 PM" src="https://github.com/BG57387/Team-4/assets/141380431/257715d7-2bc2-495a-9d94-5e908e3effdc">
<br/>
<br/>
<img width="735" alt="Screenshot 2024-03-27 at 4 16 11 PM" src="https://github.com/BG57387/Team-4/assets/141380431/a24f8c85-ddf8-4897-acd3-522dfa73d102">
<br/>
<br/>






# **Queries**
<img width="722" alt="Screenshot 2024-03-27 at 4 16 25 PM" src="https://github.com/BG57387/Team-4/assets/141380431/3e2964c7-8037-4f7b-981b-86df774566f0">
<br/>
<br/>

<br/>
<b>Query 1:</b> Write a query to list out the number of races held at each location in descending order. 

This SQL query joins the "Races" and "Facilities" tables based on the facility ID, calculates the total number of races for each facility, and orders the result set by the total number of races in descending order. It provides a breakdown of race counts for each facility, allowing for easy identification of locations with the most races conducted. <br/>
<img width="809" alt="Screenshot 2024-03-27 at 11 09 25 AM" src="https://github.com/BG57387/Team-4/assets/150160324/a2cfa106-de51-46f4-b553-64e86982af0e">

Justification:
Managers in the racing industry benefit from knowing the frequency of races held at each facility as it allows for more efficient resource allocation, including staffing and equipment maintenance. This information also guides revenue generation strategies by focusing marketing efforts on locations with a higher number of races to maximize ticket sales and sponsorships. Additionally, analyzing race frequency aids in assessing customer engagement and optimizing facility utilization to improve overall profitability.



<br/>
<b>Query 2:</b> Write a query to list out the average age of ostriches participating in races. 

This SQL query calculates the average age of ostriches that have participated in races. It achieves this by selecting the average value of the "ostrichAge" column from the "Ostriches" table, filtered by the condition that there exists a corresponding record in the "Ostriches_has_Races" table where the ostrich ID matches. In essence, it computes the average age of ostriches that have been involved in races.<br/>
<img width="811" alt="Screenshot 2024-03-27 at 11 10 29 AM" src="https://github.com/BG57387/Team-4/assets/150160324/ccaa08a5-80e1-458a-9680-f208fef28ea4">

Justification:
Managers overseeing ostrich racing events or facilities would find the results of this query pertinent as it provides insights into the age demographics of participating ostriches. This information enables managers to ensure the welfare of the animals by assessing whether age distributions align with ethical standards and regulations. Additionally, understanding the average age aids in performance analysis, healthcare management, and strategic planning for breeding and recruitment to sustain the longevity and competitiveness of ostrich racing.


<br/>
<b>Query 3:</b> Write a query to list out the average attendance per race.

This SQL query calculates the average attendance across all races. It selects the average value of the "attendance" column from the "Races" table and aliases it as "AverageAttendance". Essentially, it provides the mean attendance figure for all recorded races in the database.<br/> 
<img width="805" alt="Screenshot 2024-03-27 at 11 11 13 AM" src="https://github.com/BG57387/Team-4/assets/150160324/2111d6e9-cbc1-4e29-b172-aada45dd8d29">

Justification:
Managers in the racing industry find the results of this query crucial as it provides insights into the typical crowd size at racing events. This information aids in revenue forecasting by allowing managers to adjust pricing and marketing strategies accordingly. Additionally, it helps in facility management by informing decisions regarding seating arrangements, amenities, and overall event planning to enhance the spectator experience and ensure the efficient utilization of resources.


<br/>
<b>Query 4:</b> Write a query to list out the number of races won by each ostrich in a specfic year.

This SQL query retrieves the total number of podium finishes for each ostrich, considering only those ostriches that have achieved at least one podium finish. It accomplishes this by joining the "Ostriches," "Ostriches_has_Races," "Races," and "Race_Results" tables, linking ostriches to their race participation and race results. The query then calculates the sum of podium finishes (1st, 2nd, and 3rd positions) for each ostrich, groups the results by ostrich ID and name, filters out ostriches with no podium finishes, and finally sorts the results in descending order based on the total number of podium finishes. Essentially, it provides a ranking of ostriches based on their success in achieving podium positions in races.<br/>
<img width="815" alt="Screenshot 2024-03-27 at 11 12 13 AM" src="https://github.com/BG57387/Team-4/assets/150160324/8ff4e684-02b7-49a0-a4e8-7fa295b91aa2">

Justification:
Managers in the ostrich racing industry find this query relevant as it provides insights into the performance of individual ostriches by tracking their podium finishes in races within a specific year. This data enables managers to evaluate the competitiveness of ostriches, engage fans by highlighting successful performers, and make strategic decisions regarding breeding programs and resource allocation to nurture and train competitive racing ostriches. Ultimately, understanding podium finishes contributes to enhancing performance, fan engagement, and strategic planning for the long-term success of ostrich racing endeavors.


<br/>
<b>Query 5:</b> Write a query to list out the top performing trainers by win percentage.

This SQL query calculates the win percentage for each trainer based on their performance in races. It first constructs a subquery to count the total number of wins and total races for each trainer, grouping the results by trainer ID, first name, and last name. The win percentage is calculated by dividing the total number of wins by the total number of races, accounting for the possibility of division by zero. The query then selects the trainer ID, concatenates the first and last names to form the trainer's full name, and computes the win percentage. Finally, the results are ordered in descending order based on the win percentage, providing a ranking of trainers by their success rate in races. <br/>
<img width="805" alt="Screenshot 2024-03-27 at 11 13 26 AM" src="https://github.com/BG57387/Team-4/assets/150160324/6dd0aa17-12f4-45dc-965a-d0751bca53f5">

Justification:
Managers in the ostrich racing industry would find this query essential as it allows them to identify top-performing trainers based on win percentage, enabling evaluation of training effectiveness. By recognizing trainers who consistently produce winning ostriches, managers can allocate resources more effectively and replicate successful training methods. Additionally, this information can lead to opportunities for strategic partnerships, enhancing the competitiveness of racing teams and attracting sponsors.


<br/>
<b>Query 6:</b> Write a query to display the trainers who have trained male ostriches.

This SQL query retrieves the first and last names of trainers who have conducted training sessions for male ostriches. It performs an inner join between the "Trainers" table and the "Training_Sessions" table based on the trainer ID, and another inner join with the "Ostriches" table on the ostrich ID. The query filters the results to include only male ostriches (ostrichSex = "M") and groups the output by trainer ID, first name, and last name. Essentially, it provides a list of trainers who have conducted training sessions specifically for male ostriches.<br/>
<img width="807" alt="Screenshot 2024-03-27 at 3 54 04 PM" src="https://github.com/BG57387/Team-4/assets/150160324/ea9a764f-2080-45b2-bdf9-3a2cf02a40e3">


Justification:
Managers in the ostrich racing industry would be interested in this query as it provides a list of trainers who have trained male ostriches. Understanding which trainers specialize in training male ostriches can help managers in assigning trainers to specific birds based on their expertise and the specific needs of the racing stable. This information ensures that trainers are matched with ostriches in a way that maximizes training effectiveness and overall performance, contributing to the success of the racing team.


<br/>
<b>Query 7:</b> Write a query to list out  staff member ID, name, and the date of their shift who worked a shift in 2015 in asecnding order.

This SQL query retrieves information about staff members and their schedules for the year 2015. It first selects all columns from the "Staff_Schedules" table to provide an overview of all staff schedules. Then, it selects specific columns - staff member ID, staff member name, and schedule date - from the "Staff_Members" and "Staff_Schedules" tables, respectively, joined on the staff member ID. The query filters the results to include only schedules with dates falling within the year 2015 using a regular expression pattern matching (REGEXP '2015'), and finally, it orders the output by the schedule date. Essentially, it presents a list of staff members and their schedules specifically for the year 2015.
<br/>
<img width="816" alt="Screenshot 2024-03-27 at 11 15 17 AM" src="https://github.com/BG57387/Team-4/assets/150160324/f4c62696-5256-4bd5-854c-7107d9a4e9df">

Justification:
Managers in the racing industry would be interested in this query as it provides a record of staff members who worked shifts in 2015. Tracking employee attendance and performance is crucial for ensuring operational efficiency and compliance with labor regulations. Additionally, analyzing historical staffing data allows managers to identify trends, anticipate future staffing needs, and optimize workforce planning strategies.



<br/>
<b>Query 8:</b> Write a query to display the managers that were hired in 2015.

This SQL query selects the names, roles, contact information, and hire dates of staff members who hold the role of 'manager' and were hired in the year 2015. It retrieves this information from the "Staff_Members" table, filtering the results to include only staff members with the specified role and hire date falling within the year 2015 using regular expression pattern matching (REGEXP '2015'). Essentially, it provides a list of managers hired in the year 2015 along with their relevant details.<br/>
<img width="814" alt="Screenshot 2024-03-27 at 11 15 45 AM" src="https://github.com/BG57387/Team-4/assets/150160324/2c03d413-77e3-4495-8317-0fb2556d3cdf">

Justification:
Managers in the racing industry would be interested in this query as it provides a record of managers hired in 2015.Tracking new managerial hires allows for maintaining accurate personnel records and understanding changes in the organizational structure. Additionally, assessing turnover rates among managerial staff and evaluating the performance of newly appointed managers are crucial for leadership stability and organizational effectiveness.


<br/>
<b>Query 9:</b> Write a query to list out the number of races that each ostrich has particpated in.

This SQL query retrieves the names of ostriches along with the count of races they have participated in. It performs a left join between the "Ostriches" table and the "Ostriches_has_Races" table based on the ostrich ID, linking ostriches to their race participation records. The results are grouped by ostrich name, and the count of race participation is calculated for each ostrich. The output is then ordered in descending order based on the number of races each ostrich has participated in. Essentially, it provides a ranking of ostriches by their level of race participation. <br/>
<img width="818" alt="Screenshot 2024-03-27 at 11 25 20 AM" src="https://github.com/BG57387/Team-4/assets/150160324/88771c15-c459-48a0-8e40-2da64d75974b">

Justification:
Managers in the racing industry would find this query valuable as it provides insights into the racing experience of individual ostriches. Understanding the number of races each ostrich has participated in allows for performance evaluation, targeted training programs, and effective resource allocation. By analyzing race participation data, managers can optimize the performance and welfare of their racing ostriches, ultimately enhancing the competitiveness and success of their racing operations.

<br/>
<b>Query 10:</b> Write a query to list out the sponosors along with the events that they have sponsored.

This SQL query retrieves information about sponsors and the social events they have sponsored. It selects the sponsor ID, sponsor name, contract duration, and the name of the event they sponsored. This information is obtained by joining the "Sponsors" table with the "Social_Events" table based on the event ID. The query ensures that only sponsors with corresponding events are included by using an EXISTS subquery to check for matching event IDs between the "Sponsors" and "Social_Events" tables. Essentially, it provides a list of sponsors along with the social events they have sponsored, ensuring that only valid sponsor-event relationships are considered.<br/>
<img width="813" alt="Screenshot 2024-03-27 at 11 26 08 AM" src="https://github.com/BG57387/Team-4/assets/150160324/07bf9d3a-adea-4034-9e72-966dab725fed">

Justification:
Managers in the racing industry would find this query crucial as it provides insights into sponsorship relationships and their impact on events. By identifying sponsors and the events they have sponsored, managers can effectively track partnership agreements, assess the financial impact of sponsorships, and tailor event planning strategies to meet sponsor expectations. This data enables managers to optimize sponsorship revenue, enhance event promotion, and foster mutually beneficial partnerships that contribute to the success and profitability of racing events.
<br/>
<br/>

# **Database Information**

Name of the database: ns_Sp24_21484_Group4

Additional information: Each query listed above is marked in the database using Stored Procedures which can be called using the following format: CALL TP_Q1();

