# VRPTW
<b>
A take on Modified Vehicle Routing Problem with Time Windows and its applications on Logistics, Supply Chain and the Indian Railways.
</b>
<br>
<br>
This project was created as an end-term submission for course : Operations Research Lab at IIT Kharagpur during second year of undergraduation.
<h2>Abstract</h2>
The project looks at the attempt to present an optimized method of freight transportation over a large scale. Several assumptions have been made which are enlisted in the contents of the repository. The mathematical formulation is provided, and the code has been executed through the IBM CPLEX Solver. The implementation of Modified-Vehicle Routing Problem with Time Windows (MVRP-TW) methodology in optimizing freight transportation routes within Indian Railways. 
<br>
<br>
Through strategic planning and algorithmic application, this approach orchestrates the movement of multiple vehicles to serve customers efficiently while adhering to time constraints and optimizing route efficiency. The mathematical model has been thoroughly discussed along with the assumptions and notations used. The report mentions the references and code snippets towards the end for the viewers’ reference.

<h2>Introduction</h2>
Indian Railways, a vast railway network, faces significant hurdles in optimizing transportation operations, particularly in route and schedule management for efficient goods delivery. This project delves into solving the Modified Vehicle Routing Problem (MVRP), customized for Indian Railways' freight logistics, with a key modification reflecting real-life railway scenarios. 
<br>
<br>
Traditionally, in vehicle routing problems, the input and output nodes are typically the same. However, to better mimic real-world railway operations, we've introduced a distinction between the initial depot, where goods are loaded onto trains, and the final depot, where trains conclude their service after completing deliveries across the network. This adjustment mirrors the operational reality of railways, enhancing the problem's relevance to freight logistics.
<br>
<br>
Leveraging IBM CPLEX Solver, we've implemented an algorithm to tackle this intricate problem within Indian Railways' expansive network.

<h2>Problem Statement</h2>
For Indian Railways' freight operations, we address the Modified Vehicle Routing Problem (MVRP) to optimize freight transportation. The task involves visiting n + 2 nodes: the first and last nodes represent the initial and final depots, respectively, while the other n nodes are delivery destinations with specific demands and time windows
<br>
<br>
Each delivery destination requires a certain quantity of goods and specifies a preferable time window for delivery. Importantly, each station should be visited by only one train to meet its demand adequately.
<br>
<br>
Our objective is to devise an efficient routing and scheduling strategy for freight trains, ensuring timely delivery of goods and minimizing transportation costs. Through algorithmic solutions tailored to these constraints, we aim to enhance the efficiency of Indian Railways' freight logistics management.

<h2>Installation</h2>
To access the codes of the project and run with other datasets, install IBM CPLEX, login, and open the files as a new OPL project.

<h2>Procedure and Result</h2>
In this project, optimization techniques with CPLEX Optimizer were utilized to increase the efficiency and plan optimized routes for transport. Through the use of CPLEX, the most efficient solution was determined, resulting in reduced delays for the given data.
<br>
<br>
In conclusion, the application of Modified-Vehicle Routing Problem with Time Windows (MVRP-TW) methodology for optimizing freight transportation routes signifies a significant advancement in enhancing efficiency and effectiveness within our logistics operations.
Through strategic planning and implementation of MVRP-TW algorithms, we have successfully orchestrated the movement of multiple vehicles to serve our customers while adhering to time constraints and optimizing route efficiency.
<br>
<br>
This optimization endeavour has yielded substantial benefits, including minimized travel times and improved overall operational performance. By efficiently allocating resources and optimizing routes for multiple vehicles, we have streamlined our logistics processes, ensuring timely deliveries and enhancing customer satisfaction. In summary, the optimization of freight transportation routes using MVRP-TW represents a strategic investment in any company's future, ensuring that they remain agile, efficient, and sustainable in a rapidly evolving marketplace.

<h2>Repository Guide</h2>
<ul>
<li><b>Project_PPT: </b>This file contains a description used for presentation purposes. It provides a thorough overview of the project's key aspects, including the problem statement, methodology, and results.</li><br>
<li><b>Project_Report: </b>This file contains a brief summary of the project including the references, and procedure. It gives a detailed description for better understanding.</li><br>
<li><b>Project_MOD: </b>This file contains the code for the project, defining the optimization model using the Programming Framework.</li><br>
<li><b>Project_DAT: </b>This file contains the test data required for the model.</li>
</ul>

<h2>Future Work</h2>
Future work on this project may include:
<ul>
<li>Incorporating real-world data to validate and improve the model's accuracy.</li>
<li>Expanding the application of the optimization techniques to other scenarios.</li>
<li>Utilizing more data points and exploring edge cases to further validate the code's robustness and effectiveness.</li>
</ul>
Contributions and enhancements to the project are welcome. Feel free to open issues or submit pull requests to help improve this project.

<h2>License</h2>
This project is licensed and all rights reserved.

<h2>Acknowledgements</h2>
Special thanks to the contributors who have worked on the project.