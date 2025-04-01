**BAKERY QUEUE SIMULATION - SINGLE-SERVER QUEUING MODEL**

***Introduction:***

A Single-Server Queuing Model is a mathematical model used to represent situations where customers arrive at a service point and are served one by one in the order of their arrival. This type of queuing model is commonly used in various fields, such as retail, banking, and customer service, to simulate real-life scenarios and analyze the behavior of queues.

In this project, we simulate a bakery queue using the Single-Server Queuing Model. The bakery has only one server (the baker), and customers arrive at the bakery, waiting for service in a line. As the customers wait, the server serves them one by one. This simulation is visualized using HTML, CSS, and JavaScript, providing an interactive experience.

***Objective:***

The objective of this project is to demonstrate the behavior of a Single-Server Queuing Model by simulating customers arriving at the bakery, waiting in line, and being served one at a time by the server.

***Key Features:***

Add customers to the queue.

Serve customers one by one.

Display status updates such as "Waiting for customers", "Customers waiting", "Serving customer", and "No customers in queue".

Animation effects for customers arriving, waiting in line, and being served.

***What is a Single-Server Queuing Model?***

In a Single-Server Queuing Model, there is only one service point (in this case, the baker), and customers arrive in random intervals. They are served in the order of their arrival, one at a time. This model is typically denoted as M/M/1 in queuing theory, where:

M stands for Markovian (memoryless) arrival process (Poisson process).

M stands for Markovian (memoryless) service process (Exponential distribution).

1 indicates there is only one server.

The goal of using this model is to understand how the system behaves in terms of waiting times, service times, and the overall efficiency of the system.

***Example:***

Imagine a bakery where there is only one baker serving customers. Customers arrive one by one, and the baker serves them as they come. If the bakery is busy, new customers have to wait in line until the baker is free. The Single-Server Queuing Model simulates this scenario.

*How the Simulation Works*

![Image](https://github.com/user-attachments/assets/6ed8eaeb-ff32-4e9b-b869-e42041dd0cd9)

***Customer Arrival:***

Customers can be added to the queue by pressing the "Add Customer" button.

Each customer is represented by an image and is placed outside the queue to move into their position.

![Image](https://github.com/user-attachments/assets/4dc62943-44b5-43db-b290-484ec00be2e3)

***Customer Service:***

When the "Start Service" button is clicked, the first customer in the queue is served.

The customer is removed from the queue after they are served, and the server status updates accordingly.

![Image](https://github.com/user-attachments/assets/07e54ed9-2008-4ae8-96f0-27f30c23fadc)

***Queue Updates:***

The queue updates dynamically as customers arrive and are served.

An animation is applied to each customer to make them appear and move smoothly in the queue.

A firework effect is shown after a customer is served to indicate successful service.

**Getting Started**<br>

***Prerequisites:***<br>

A modern web browser (Chrome, Firefox, Edge, etc.)
Basic understanding of HTML, CSS, and JavaScript.<br>

<ins>Steps to Run the Project</ins><br>
<br>
***Clone the repository:***<br>

You can clone the repository to your local machine using the following command:<br>

git clone https://github.com/your-username/bakery-queue-simulation.git

***Navigate to the project directory:***

Open the project folder using a code editor (e.g., VS Code) or simply double-click the index.html file to open it in your web browser.

***Run the project:***<br>
Once you have the project files opened in your browser, the Bakery Queue Simulation will be live. You can interact with the simulation by adding customers and starting the service.

**Features**<br>
*1. Add Customer:*<br>
Adds a new customer to the queue.

The customer image moves into the queue, and their arrival is displayed.

*2. Start Service:*<br>
Starts serving the first customer in the queue.

After the service is completed, the customer leaves the queue, and a "firework" animation is shown as an effect.

*3. Queue Updates:*<br>
Status updates show real-time information about the queue:

"Waiting for customers..."

"Customers waiting..."

"Serving customer..."

"No customers in queue."

***Game Flow***<br>
https://github.com/user-attachments/assets/22d6b8e3-f682-4e6a-948c-f624d4ef14f2<br>

***Technologies Used:***<br>

*HTML* for structure.

*CSS* for styling and animations.

*JavaScript* for logic and interactivity.

***Conclusion:***<br>

This project demonstrates a basic Single-Server Queuing Model by simulating a bakery scenario where customers wait in line for service. The goal is to visualize how a queue behaves in real-time and to give users a clear understanding of queuing theory concepts.

***License:***<br>

This project is licensed under the MIT License - see the LICENSE file for details.

***Image Credits and Attribution:***<br>

All images used in this project belong to their respective owners. No copyright infringement is intended. If you own any of the images and would like them to be removed or credited differently, please contact us.
