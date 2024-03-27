# Team-4
MIST 4610, Team 4 Project

TEAM NAME 21484Projects

TEAM MEMBERS 

[Ashley Park](https://github.com/ap86129) <br/>
[Izzie Paden](https://github.com/izziepaden) <br/>
[Carter Kowalski](https://github.com/carterkowalski1) <br/>
[Bharat Gupta](https://github.com/BG57387) <br/>


**Problem Description**:<br/>
The project at hand is to conceptualize and develop a relational database for the dynamic operations of an Ostrich Racing Club. This database is structured around the central entity of the Ostrich table. Ostrich being each bird that is raced in the racing events hosted. In parallel, the Facility entity is crucial as it details each racing arena and training ground we maintain. Alongside these, we track the Visitor entity to log guests and bettors attending races, their interactions, and preferences. Critical associations include linking Ostriches to their Trainers, Races they participate in, and the Results they achieve, as well as connecting Visitors to the Events they attend. The database will store comprehensive data on these entities and their attributes to simulate real-world scenarios. We aim to deploy advanced queries from the data, offering deep insights into club operations, visitor engagement, and other relationships occurring in the racing club.  The ultimate goal is to leverage this database to streamline all functions of the races and related events.

To create a coherent data model for an ostrich racing club, understanding the relationships between entities is crucial. Here's an outline of potential relationships within the given entities:<br/>
These relationships form the backbone of the database and dictate how data is interconnected. Properly defined relationships ensure the database is normalized, reducing redundancy and improving data integrity. For each Many-to-Many relationship, a junction (or associative) table is necessary to handle the associations between the entities effectively.

![Final](https://github.com/BG57387/Team-4/assets/150160324/6fbd90ff-535a-429e-a576-6954485976b3)



**Data Model Explanation:**<br/>
Our data model is structured to mirror the vibrant ecosystem of an ostrich racing club, where the interplay between ostriches, jockeys, and trainers translates into a series of detailed and interconnected relationships. At the heart of this model is the Ostrich entity, signifying each racing bird housed within our club. Every ostrich is paired with a dedicated Jockey, establishing a one-to-many relationship as each jockey can ride multiple ostriches, but each ostrich is ridden by a single jockey in races.

The Ostriches are also linked to Training Sessions in a one-to-many relationship, indicating that each ostrich participates in numerous training activities designed to enhance their performance. Correspondingly, Trainers are connected to Training Sessions, as a single trainer may conduct multiple sessions for various ostriches, honing their skills for upcoming races.

As for the Races themselves, we see a many-to-many relationship with both Ostriches and Jockeys, as numerous ostriches can compete in multiple races, often ridden by different jockeys. Each race, a thrilling spectacle of speed and agility, yields numerous Race Results, depicted by a one-to-many relationship, capturing the outcome and statistics for each participating ostrich.

Visitors, vital to the club's vibrancy, partake in these races, manifesting a many-to-many relationship that highlights the dynamic interaction as visitors attend various races. Our Facilities play a pivotal role, with a one-to-many relationship to Races and Social Events, illustrating that a single facility may host numerous races and events, offering diverse experiences to our patrons.

Social Events, vibrant gatherings sponsored by business entities, showcase a one-to-many relationship with Sponsors, who support various events to enhance their visibility and engagement. These events also connect to Staff Members through a many-to-many relationship, reflecting the myriad of roles staff undertake during events, from coordination to execution.

Lastly, Staff Members' schedules are intricately managed, presenting a one-to-many relationship with Staff Schedules. Each staff member has a specific schedule, defining their roles, shifts, and duties. This comprehensive model is crafted to ensure a seamless and integrated operation of the club, ensuring a cohesive experience for all, from the ostrich races to the social events, all within our racing facilities.


Query 1<br>
<img width="809" alt="Screenshot 2024-03-27 at 11 09 25 AM" src="https://github.com/BG57387/Team-4/assets/150160324/a2cfa106-de51-46f4-b553-64e86982af0e">

