# PADDLE-BOAT-QUEUING-SYSTEM

## PROJECT SYNOPSIS 
As the title of the project suggest, this project is to ease the paddle boat business to manage their paddle boat reservation by applying the queuing system, such that in a bank where customer will get a number and wait for their turn to be entertained at the counter. The same concept is applied in this project. It basically means that the reservation system would be a “First Come First Serve” basis. With the ever growing popularity of the paddle boat activity, especially amongst students, it is also logical for this type of system to be applied.
## CLASSES TO BE USED
For this project, we will be using 2 class, namely:
1. Boat
2. Customer

For the **Boat** class, it will apply the stack concept. This class will store the paddle boat information, which including the boat number. The boats that are available are couple-boat (2 persons), family-boat (4 persons) and deluxe-family-boat (6 persons). The boats will be stored in dock by stacking, where the first boat to enter the dock will be last one to leave the dock, defined as “First In Last Out”.
As for the **Customer** class, it will apply the queue concept where it will generate the waiting number for each customer who wants to ride the boat. The customer will be queued, whose line up first will be prior served to get their boat early, defined as “First In First Out”.
## EXTRA INFORMATION
This project is to test the understanding of owner on data storage type such as stack, queue and tree structure 
