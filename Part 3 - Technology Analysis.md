# Part 3: Technology Analysis #

## Used Technologies and some limits ##

Most of carpooling systems could be described as static carpooling systems. The implementation of the concept is usually made through a simple website which can only save and display the available offers. The only advantage of this solution is the simplicity of implementation. A registration is required from potential users to have access to the full functionalities of the website. But unfortunately, the provided functionalities consists only in adding or consulting the offers with different options like the type of the car that don’t change anything to the transportation problematics. For those websites, a data base is necessary to save the uploaded offers and answer the consultation requests. The only technological aspect that is important to deal with is the storage capacity which is absolutely not a problem nowadays. Indeed the management of those databases is very simple.

The websites like Blablacar is included in this category. The consultation of the offers is public but all other functionalities are accessible after a registration. After accessing the result of research on the database, the user can exchange some messages with the driver for the details. All the communications are made publicly and on the website. The carpoolers can have access the personal contact of each other only after buying and finalizing the transaction. Other website, with nonprofit objective, can give access to the personal contacts directly on the offer to reduce the number of operations made on the website. 

The success of those systems doesn’t guarantee a stability for those companies. Indeed, regarding the development of new technologies and the evolution of people’s habits, the existing websites are becoming obsolete and a modification of the technologies seems to be a must.


## Technologies to boost the market ##
### Dynamic and flexible system ###
This is a new concept in the area of carpooling and transportation in general. It consists on managing a continuous access to the carpooling available offers. A real time access is provided through a continuous updating of the offers and the demands. The development simultaneous development of this new “Smart” concept and the new technologies is not a coincidence. Indeed with the popularization of smartphones, tablets, connected devices (particularly for the cars), free access to the Wifi, GPS, 3G, 4G… the ‘in real time” became totally possible and accessible for all people. This evolution is directly relevant to the carpooling industry in the way that it is going to transform and change this industry by giving more solutions to solve the problem of flexibility.

This is a new concept in the area of carpooling and transportation in general. It consists on managing a continuous access to the carpooling available offers. A real time access is provided through a continuous updating of the offers and the demands. The development simultaneous development of this new “Smart” concept and the new technologies is not a coincidence. Indeed with the popularization of smartphones, tablets, connected devices (particularly for the cars), free access to the Wifi, GPS, 3G, 4G… the ‘in real time” became totally possible and accessible for all people. This evolution is directly relevant to the carpooling industry in the way that it is going to transform and change this industry by giving more solutions to solve the problem of flexibility.
But even if the access to these technologies is a big opportunity for all the companies in the transportation industry, the all potential of this situation is not exploited. The major part of the startup projects have been failed due to security problems, automation of the procedure and optimization in the process of offers association. But all the concepts developed are based on one unique technology which is the recuperation of GPS position in real time and sharing it with all the users.

#### A distributed system for more flexibility ####
Solving the problem of flexibility of carpooling is a major challenge for all the companies in this industry. Regarding the dynamic aspect of carpooling environment, a good carpooling system has to be adapted to this evolving environment. Indeed the variation speed of the inputs are a major obstacle for the development of reliable system. The collection of data is made through a large area and large number of users. The prediction of evolution of those data (like the position of cars, the time that people need to carpool…) through statistical methods become impossible. The only solution is making a dynamic model of the network with decentralized decision making. It means that the decision of association a user to a car must be done autonomously.

This aspect could be implemented by decentralized systems like Multi-Agent Systems (MAS) or Blockchain. The objective of these Agents is to successfully associate the different users through an optimization process subjected to several, complex and variable constraints. The choice of using MAS is directly related to the variation, the increase and the distribution of information sources. Indeed, in the classic systems, when the size of the network increases the complexity of the medialization became high and the limits of the systems are revealed. But with the MAS, the size of network increases the relevance of the solution. Indeed, managing a high number of data sources is not a constraint anymore. Then, the system become interesting because it offers more possible solutions. 

Furthermore, the robustness of the proposed solution is depending on the quality of the optimization process. The complexity of this optimization problem is exponential. For this, the distribution process consists on executing simultaneously and in parallel several tasks with lower complexity.

#### Optimization in the association of vehicles ####
The optimization is a key point for our analysis. Since the development of IT, people started studying optimization applied to different areas. We can easily use the large number of studies about optimization in transportation and specifically in transportation by taxi as a start point for our carpooling problem. Indeed, we can easily identify similarities between a taxi network and a carpool network especially for travels home – work.

In the carpooling industry, some optimization algorithms have been developed but not in order to make the system more flexible. Those algorithms focus more about associate rides after collecting static data. Indeed, two limitations can be listed.

-	The first one is the limitation of geographic area. Indeed, if we look to carpooling websites that use optimization concept, we can notice that the geographic area is limited to one company, one university or one small organization.
-	The second one is the problem of flexibility. The results that have been applied don’t take in consideration the dynamic aspect of problem. After making the combinations and association of drivers and passengers, the system will not be able to adapt to other situation like an introduction on a new user (driver or passenger), modification of location of one of them….

If we assume that the taxi optimization problem is a good starting point, we have to emphasis an important point which is specific to the carpooling system. Indeed, for the taxi problem, we need to associate clients to drivers. For this we consider the current positions of the taxi, the initial and the final positions of the clients. In the carpooling system, the driver and the client have two different objective. It means that the driver has his own itinerary and we should consider whether a deviation from the initial itinerary is acceptable or not. It means in the carpooling system, we should introduce a concept of tolerance that is going to quantify to what extent the deviation is importance.

More globally, the notion of optimization is not related only to those kind of details. The most recent studies proposed to set a function which is related to the satisfaction of the users. Thus, we are not optimizing one criteria but something more complex that is usually directly given by the users. Indeed, the user satisfaction is the key point for this market to grow. But each user will have his own criteria, and defining a fixed objective function is not adapted to the carpooling industry. Indeed, this industry is preferable with a customizable service. This multiplication of criteria like the total duration of the trip, the number of different cars before arriving to the destination, cost… will increase the complexity of the problem. The optimization became complicated due to the exponential formulation of that problem.

To solve this problem, an innovative model was proposed by the studies. This model is based on the distributed architecture of the program. It means using architecture like blockchain, we are able to separate the initial problem on several others with the objective of reducing the exponential complexity. The different small problems are solved in parallel after this decentralization.

The studies proposed to model the problem with 3 different distributed graphs. The first one is representing the network with nodes and arcs, the second one is representing the demands and the last one the offers.

Basically, the nodes are representing the stating position of users and the arcs are the itinerary that can be token. These two kind information are automatically updated using GPS localization module. For this part of technology, there is nothing innovative and a lot of applications like Uber are already using this.

The second graph is built by collecting the information, the constraints and the preferences of users. It is built with the initial position, the final position, the number of people and the total duration of the trip. This last variable is calculated using an adapted function and including other parameters like the late time admitted, the tolerance about distance and all constraints that are considered as relevant.

With a similar way, we can build the last graph about the offers. We will build it using the initial position of cars, the destination of cars, the number of available sits, the duration of the trip and also one more parameter which consist in a vector of intermediate destinations. Indeed, to simplify the resolution of the problem, it is better to create a vector that groups all the information about the points that are possible to serve. Doing this, we can easily check if a user’s destination can be served by comparing this final destination of the user to the intermediate points of cars. 

When this basic concept if developed, we need to develop a strategy of treating the data. For this we are going to use 5 major steps.

    `Graph process`

- Step 1: acquisition of the demands

For this step we need to receive all the demands for carpooling and treat them in parallel. For this, the time is one of most important parameters. Each interval of time t, we refresh the entering data and build the new matrix containing the information for the graph of demands.
In this part we need to use 3 major technologies. The first one is the internal clock of the system with a precision of a few seconds or less. Then we need to use GPS inside user’s device. If the device doesn’t contain any GPS technology, other solutions are possible like using Wi-Fi signal or 3G/4G localization system. Then the last one is the communication protocol. Indeed, to send all these data from a device to another, we need build first a communication protocol which is going to guarantee in one hand, the transmission without any loss of information and in the other hand, the security of users by the cryptography algorithms.

- Step 2: acquisition of the offers

During this step, we are going to perform the same tasks than last part. Also in this part we need to update the data in “continuous” flow. For this we are going to setup a time t before each new acquisition. The technology that we are going to use is the same. But, as we are talking about cars moving, we need to use better quality technology to have accurate data processing. Indeed, if for the users, a simple GPS in the smartphone is adapted, for the car we need to use the integrated GPS with more precision and high frequency of updates.

- Step 3: building the graphs

This step is totally virtual and doesn’t use any real hardware technology. But even if only algorithms are involved for this step, it is a critical step. Indeed, for the 2 previous steps we defines the way to collect and to store data in Matrix. Then using theories coming from “Graph theory”, we are able to build a Graph. Here graph refers to mathematical concept of graphs.



- Step 4: Decomposition of the process

This step is also a virtual one. It consists on grouping the users and the cars in small geographic areas. In order to simplify the calculations and the then reduce the complexity, different studies agreed to group the data within circular areas.
The method that is used is called “hierarchical clustering”

    http://en.wikipedia.org/wiki/Hierarchical_clustering

- Step 5: Optimization

Considering the definition of the problem, the multiple objective optimization seems to be a must. Indeed, more and more problems can’t be solved by optimizing one function. Our problem is one of them. The distributed modeling that we choose imposed to use this kind of optimization.
Many possible algorithms and methods can be used to solve this kind of problems. In the literature, and for the multiple objective optimization problems, we can find the following algorithms.
Simulated Annealing using Metropolis algorithm which is based on the research on an equilibria inside the system, Tabu Search for the problems where we need to record the different tries, Evolutionary algorithms and Ant colony which are the most flexible, robust, and decentralized algorithms that we have developed. The only obstacle is the evolution of the research in this area. Indeed, even if the concept is developed, the application on real cases are difficult. Maybe this algorithm will be the future of this industry, but for the moment, the specialists agree to say that the most adapted algorithm for carpooling is the “Dijkstra's algorithm”

    http://en.wikipedia.org/wiki/Dijkstra%27s_algorithm



### Security for carpooling users ###
The security is one of the most important part in the carpooling system. The users will be encouraged to use carpooling only if the security is guaranteed. The drivers also pay attention to the solutions that are developed to protect themselves. The objective of this part is to show these possible solutions.

Even if the management of the transportation offers is a big issue for all the companies in this industry, from the point of view of users, the security and the traceability is the most important aspect and obstacle for the development of dynamic carpooling. The development of systems as “eNotions” in Germany, “EasyRider” for Amsterdam and “T.écovoiturage” in France haven’t solved those problems.

When you use a distributed network, you can also use it to share the information. It is easy to share the GPS data in the distributed system. It could be a problem to use smartphones as for the distributed network. Due to the design of smartphones and tablets, some technical problems could be faced. Solving those problems will be easier if the market is already using the technology. For this, some studies proposed to start building the distributed network using computers. Then the users will setup there account with the computer and then synchronize the data with the tablet or smartphone. Of course this solution is less secure that using directly smartphones for the network. But it is a good start point to encourage people to improve this situation.

Having a distributed network for data is coherent with the distributed architecture that we introduced in the previous part. Indeed, it develops the idea of autonomy that is needed and also the vision of “operations as close as possible to the users”.

But the crypto-graphic challenges are not the only issues that worry people. Indeed, the major obstacle for them in using carpooling is the security of their life. Usually a user is worried if the driver that is going to drive him is an honest person and if the driver drives safely. The two things could be easily solved by the distributed network. Using Blockchain, the users can evaluate the drivers and comment about the quality of the service. Then a ranking system can easily put grades and the user can know there driver before accepting or refusing him. Then the users will be more confident when they use carpooling. So the market will be boosted by this security solution.

But we should also think about the drivers. They need to have guaranties that make them confident about the users that they drive. If it is easy to filter the drivers and push the bad ones out of the system, filtering the users is hard due to the size of the network. For this we propose to rank the users with the same kind of algorithms. Then drivers can decide if they want to go and pick the user or not. Because it happens a lot that the driver will drive and look for the user but this last one had already moved and fined another transportation way.

Then the last issue that we need to secure is the transaction. In this case bitcoin and blockchain are the first solution that we need to use. Using digital transaction will solve all the problems. Then drivers will be automatically paid when the user will be at his destination place. Then the driver will be paid if he accomplish his task and the user will arrive at the right place.
A total decentralized solution is also possible and proposed by “LaZooz”. This system is totally automated and decentralized and it use its own coins. It is the most recent technology that we can present about this subject. It is going to start around the 6th of June 2015.	