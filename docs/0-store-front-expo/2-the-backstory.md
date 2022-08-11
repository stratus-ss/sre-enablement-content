##  A Little Bit Backstory

Red Hat is an software company that creates epic productivity and platform software...

Nat Clicks, the new CEO, wants to shake things up a bit and bring Red Hat's online store into the 21st century. Spurred on by the mobile experience and a nice, icon driven experience, Nat has comissioned the creation of a new micro-services first approach to bring Red Hat's software catalog to life! After some initial dev work, the store offers a shopping cart, a payment processor, a product catalog as well as a recommendations engine and a shipping service if the client orders swag.

There is a lot going on, and the microservices architecture makes it an ideal candidate for deployment on OpenShift with ServiceMesh. On top of that, this project involves 5 different programming languages, each chosen for the optimization of their specific service.


<img src="images/Red_Hat_Gallery_Traffic_Flow.png" >

Nat's gamble on a mobile friendly interface really paid off! The website has started getting wide attention with folks coming from all over the web just to see what the store has to offer. Hopefully, the increased traffic will translate into more revenue for Red Hat. 

In order to support the increased workload, Red Hat mandates the creation of a new group in charge of not only developing the application, but also the delivery and maintanence throughout the production life cycle. Fortunately, Red Hat has some initial training on hand: [Introduction to Pragmatic Site Reliability Engineering](https://www.redhat.com/en/services/training/tl112-pragmatic-introduction-site-reliability-engineering-implementation-devops). 

The new group has been armed with some initial knowledge and is eager to put the SRE methodology into practice.

<img src="images/discovery.png" >


## Overwhelming Demand Overwhelms Core Group

The new portal leads to the development team starting to have a hard time keeping up with the feature requests or bugs reports while maintaining the app on production. Incidents started to occur due to unexpected high load, lack of high availability or scalability. They needed to figure out things like security, scalability, operability, reliability to match with their external and internal end users needs!
