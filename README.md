# Team-4
MIST 4610, Team 4 Project

# TEAM NAME 21484Projects

# TEAM MEMBERS 

Ashley Park [Ashley Park](https://github.com/ap86129) <br/>
Izzie Paden [Izzie Paden](https://github.com/izziepaden) <br/>
Carter Kowalski [Carter Kowalski](https://github.com/carterkowalski1) <br/>
Bharat Gupta [Bharat Gupta](https://github.com/BG57387) <br/>


# **Problem Description**:<br/>
The project at hand is to conceptualize and develop a relational database for the dynamic operations of an Ostrich Racing Club. This database is structured around the central entity of the Ostrich table. Ostrich being each bird that is raced in the racing events hosted. In parallel, the Facility entity is crucial as it details each racing arena and training ground we maintain. Alongside these, we track the Visitor entity to log guests and bettors attending races, their interactions, and preferences. Critical associations include linking Ostriches to their Trainers, Races they participate in, and the Results they achieve
, as well as connecting Visitors to the Events they attend. The database will store comprehensive data on these entities and their attributes to simulate real-world scenarios. We aim to deploy advanced queries from the data, offering deep insights into club operations, visitor engagement, and other relationships occurring in the racing club.  The ultimate goal is to leverage this database to streamline all functions of the races and related events.

To create a coherent data model for an ostrich racing club, understanding the relationships between entities is crucial. Here's an outline of potential relationships within the given entities:<br/>
These relationships form the backbone of the database and dictate how data is interconnected. Properly defined relationships ensure the database is normalized, reducing redundancy and improving data integrity. For each Many-to-Many relationship, a junction (or associative) table is necessary to handle the associations between the entities effectively.

![Final](https://github.com/BG57387/Team-4/assets/150160324/6fbd90ff-535a-429e-a576-6954485976b3)



# **Data Model Explanation:**<br/>
Our data model is structured to mirror the vibrant ecosystem of an ostrich racing club, where the interplay between ostriches, jockeys, and trainers translates into a series of detailed and interconnected relationships. At the heart of this model is the Ostrich entity, signifying each racing bird housed within our club. Every ostrich is paired with a dedicated Jockey, establishing a one-to-many relationship as each jockey can ride multiple ostriches, but each ostrich is ridden by a single jockey in races.

The Ostriches are also linked to Training Sessions in a one-to-many relationship, indicating that each ostrich participates in numerous training activities designed to enhance their performance. Correspondingly, Trainers are connected to Training Sessions, as a single trainer may conduct multiple sessions for various ostriches, honing their skills for upcoming races.

As for the Races themselves, we see a many-to-many relationship with both Ostriches and Jockeys, as numerous ostriches can compete in multiple races, often ridden by different jockeys. Each race, a thrilling spectacle of speed and agility, yields numerous Race Results, depicted by a one-to-many relationship, capturing the outcome and statistics for each participating ostrich.

Visitors, vital to the club's vibrancy, partake in these races, manifesting a many-to-many relationship that highlights the dynamic interaction as visitors attend various races. Our Facilities play a pivotal role, with a one-to-many relationship to Races and Social Events, illustrating that a single facility may host numerous races and events, offering diverse experiences to our patrons.

Social Events, vibrant gatherings sponsored by business entities, showcase a one-to-many relationship with Sponsors, who support various events to enhance their visibility and engagement. These events also connect to Staff Members through a many-to-many relationship, reflecting the myriad of roles staff undertake during events, from coordination to execution.

Lastly, Staff Members' schedules are intricately managed, presenting a one-to-many relationship with Staff Schedules. Each staff member has a specific schedule, defining their roles, shifts, and duties. This comprehensive model is crafted to ensure a seamless and integrated operation of the club, ensuring a cohesive experience for all, from the ostrich races to the social events, all within our racing facilities.

# **Data Dictionary**

<img width="535" alt="Screenshot 2024-03-27 at 2 31 56 PM" src="https://github.com/BG57387/Team-4/assets/150160324/fd31a46e-b3f6-454a-8845-e7752660c564">

<img width="323" alt="Screenshot 2024-03-27 at 2 33 21 PM" src="https://github.com/BG57387/Team-4/assets/150160324/71d8937f-e04d-48e8-ada1-2d44eb1a934e">


# **Qureies**

Query 1 list out the number of races held at each location <br/>
<img width="809" alt="Screenshot 2024-03-27 at 11 09 25 AM" src="https://github.com/BG57387/Team-4/assets/150160324/a2cfa106-de51-46f4-b553-64e86982af0e">

Justification:<br/>
Managers in the racing industry benefit from knowing the frequency of races held at each facility as it allows for more efficient resource allocation, including staffing and equipment maintenance. This information also guides revenue generation strategies by focusing marketing efforts on locations with a higher number of races to maximize ticket sales and sponsorships. Additionally, analyzing race frequency aids in assessing customer engagement and optimizing facility utilization to improve overall profitability.



Query 2 list out the average age of ostriches participating in races <br/>
<img width="811" alt="Screenshot 2024-03-27 at 11 10 29 AM" src="https://github.com/BG57387/Team-4/assets/150160324/ccaa08a5-80e1-458a-9680-f208fef28ea4">

Justification:<br/>
Managers overseeing ostrich racing events or facilities would find the results of this query pertinent as it provides insights into the age demographics of participating ostriches. This information enables managers to ensure the welfare of the animals by assessing whether age distributions align with ethical standards and regulations. Additionally, understanding the average age aids in performance analysis, healthcare management, and strategic planning for breeding and recruitment to sustain the longevity and competitiveness of ostrich racing.


Query 3 list out the average attendance per race<br/> 
<img width="805" alt="Screenshot 2024-03-27 at 11 11 13 AM" src="https://github.com/BG57387/Team-4/assets/150160324/2111d6e9-cbc1-4e29-b172-aada45dd8d29">

Justification:<br/>
Managers in the racing industry find the results of this query crucial as it provides insights into the typical crowd size at racing events. This information aids in revenue forecasting by allowing managers to adjust pricing and marketing strategies accordingly. Additionally, it helps in facility management by informing decisions regarding seating arrangements, amenities, and overall event planning to enhance the spectator experience and ensure the efficient utilization of resources.


Query 4 list out the number of races won by each ostrich in a specfic year<br/>
<img width="815" alt="Screenshot 2024-03-27 at 11 12 13 AM" src="https://github.com/BG57387/Team-4/assets/150160324/8ff4e684-02b7-49a0-a4e8-7fa295b91aa2">

Justification:<br/>
Managers in the ostrich racing industry find this query relevant as it provides insights into the performance of individual ostriches by tracking their podium finishes in races within a specific year. This data enables managers to evaluate the competitiveness of ostriches, engage fans by highlighting successful performers, and make strategic decisions regarding breeding programs and resource allocation to nurture and train competitive racing ostriches. Ultimately, understanding podium finishes contributes to enhancing performance, fan engagement, and strategic planning for the long-term success of ostrich racing endeavors.


Query 5 write a query to list out the top performing trainers by win percentage <br>
<img width="805" alt="Screenshot 2024-03-27 at 11 13 26 AM" src="https://github.com/BG57387/Team-4/assets/150160324/6dd0aa17-12f4-45dc-965a-d0751bca53f5">

Justification:<br/>
Managers in the ostrich racing industry would find this query essential as it allows them to identify top-performing trainers based on win percentage, enabling evaluation of training effectiveness. By recognizing trainers who consistently produce winning ostriches, managers can allocate resources more effectively and replicate successful training methods. Additionally, this information can lead to opportunities for strategic partnerships, enhancing the competitiveness of racing teams and attracting sponsors.


Query 6 write a query to display the trainers who have trained male ostriches<br>
<img width="808" alt="Screenshot 2024-03-27 at 11 14 29 AM" src="https://github.com/BG57387/Team-4/assets/150160324/8988ecc3-1a3e-4f74-b4a0-1756568a67b9">

Justification:<br/>
Managers in the ostrich racing industry would be interested in this query as it provides a list of trainers who have trained male ostriches. Understanding which trainers specialize in training male ostriches can help managers in assigning trainers to specific birds based on their expertise and the specific needs of the racing stable. This information ensures that trainers are matched with ostriches in a way that maximizes training effectiveness and overall performance, contributing to the success of the racing team.


Query 7 Write a query to list out  staff member ID, name, and the date of their shift who worked a shift in 2015 in asecnding order<br>
<img width="816" alt="Screenshot 2024-03-27 at 11 15 17 AM" src="https://github.com/BG57387/Team-4/assets/150160324/f4c62696-5256-4bd5-854c-7107d9a4e9df">

Justification:<br/>
Managers in the racing industry would be interested in this query as it provides a record of staff members who worked shifts in 2015. Tracking employee attendance and performance is crucial for ensuring operational efficiency and compliance with labor regulations. Additionally, analyzing historical staffing data allows managers to identify trends, anticipate future staffing needs, and optimize workforce planning strategies.



Query 8 write a query to display the managers that were hired in 2015<br>
<img width="814" alt="Screenshot 2024-03-27 at 11 15 45 AM" src="https://github.com/BG57387/Team-4/assets/150160324/2c03d413-77e3-4495-8317-0fb2556d3cdf">

Justification:<br/>
Managers in the racing industry would be interested in this query as it provides a record of managers hired in 2015. Tracking new managerial hires allows for maintaining accurate personnel records and understanding changes in the organizational structure. Additionally, assessing turnover rates among managerial staff and evaluating the performance of newly appointed managers are crucial for leadership stability and organizational effectiveness.


Query 9 Write a query to list out the number of races that each ostrich has particpated in<br>
<img width="818" alt="Screenshot 2024-03-27 at 11 25 20 AM" src="https://github.com/BG57387/Team-4/assets/150160324/88771c15-c459-48a0-8e40-2da64d75974b">

Justification:<br/>
Managers in the racing industry would find this query valuable as it provides insights into the racing experience of individual ostriches. Understanding the number of races each ostrich has participated in allows for performance evaluation, targeted training programs, and effective resource allocation. By analyzing race participation data, managers can optimize the performance and welfare of their racing ostriches, ultimately enhancing the competitiveness and success of their racing operations.


Query 10 list out the sponosors along with the events that they have sponsored<br>
<img width="813" alt="Screenshot 2024-03-27 at 11 26 08 AM" src="https://github.com/BG57387/Team-4/assets/150160324/07bf9d3a-adea-4034-9e72-966dab725fed">

Justification:<br/>
Managers in the racing industry would find this query crucial as it provides insights into sponsorship relationships and their impact on events. By identifying sponsors and the events they have sponsored, managers can effectively track partnership agreements, assess the financial impact of sponsorships, and tailor event planning strategies to meet sponsor expectations. This data enables managers to optimize sponsorship revenue, enhance event promotion, and foster mutually beneficial partnerships that contribute to the success and profitability of racing events.

