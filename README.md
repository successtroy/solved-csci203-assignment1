Download Link: https://assignmentchef.com/product/solved-csci203-assignment1
<br>
<h1></h1>

<ul>

 <li>To apply queue data structure</li>

 <li>To be able to manipulate queue operations.</li>

 <li>To write the program to represent queue simulation</li>

</ul>

<h1>Problem</h1>

Your task for this assignment is to investigate some of the properties of queues and write programs which simulate the queuing and service of a set of requests using TWO (2) different strategies.

Each simulation should start at time 0 and run until all customers have been served.

The 2 queueing strategies are as follows:

<ol>

 <li>A single queue. Each server will take the next customer as soon as the server becomes available.</li>

 <li>A queue for each server. Customers will choose the server with the shortest queue on arrival and not allowed to jump queue thereafter.</li>

</ol>

Input consists of a set of service requests each consisting of an arrival time, service time and number of servers. (Note: the arrival times are sorted in ascending order).

Your program should read the name of the data file from standard input and then read the data in the named file into the simulation. Run the simulation for a 20 service requests.

The standard output for both the queuing process will consist of the following data:

<ul>

 <li>Average waiting time of a service request</li>

</ul>

<em>Average waiting time = </em>(Total time a service request waits in queue) / (Total number of service requests)

<ul>

 <li>Total idle time for each server.</li>

</ul>

Include appropriate validation and comments in your code.


