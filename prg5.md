5. Problem Statement: Missing Information Detection in Flight Booking
A travel booking system collects flight details from customers through natural-
language messages. Before processing a booking, the system must verify whether
all mandatory information has been provided.
Your task is to design a prompt that extracts the available information, identifies
missing fields, and asks the customer to provide the missing details.
Required Fields:
 Passenger Name
 Departure City
 Destination City
 Travel Date
 Number of Passengers
 Travel Class
Input:
&quot;I am Rahul. I want to book a flight from Bengaluru to Delhi.&quot;
Expected Output:
Passenger Name: Rahul
Departure City: Bengaluru
Destination City: Delhi
Travel Date: Missing
Number of Passengers: Missing
Travel Class: Missing

Please provide the following missing information:
1. What is your preferred travel date?
2. How many passengers will be travelling?
3. Which travel class do you prefer: Economy, Premium Economy, Business, or First
Class?

Additional Requirements:

1. Extract all information explicitly provided by the customer.
2. Never assume or invent missing information.
3. Identify every missing mandatory field.
4. Ask clear, relevant questions to collect the missing information.
5. If all mandatory fields are provided, respond: All required information has been
provided.
6. Do not ask the customer to repeat information already provided.
Objective: Create a prompt that acts as an intelligent data-collection assistant,
ensuring all mandatory information is available before proceeding with a booking.
