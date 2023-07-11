# Cloud Security Principles and Frameworks

From: [AWS Architecture Blog - Compute Abstractions on AWS: A Visual Story](https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/) (accessed by Benjamin Hobbs on 7/9/2023)

## Cloud Security Principles

* Cloud computing generally follows different levels of needs for consumers.
* Even though vendors may address these levels differently with their products, they still follow this fairly closely.


### Separation of Duties
* In a cloud environment, there's the inherent question...Who's responsible for what? 
   * The AWS model apporaches this with a shared responsibility model.

     * Basically, the assertion here is: There is some stuff that AWS is responsible for, and there is some stuff that the consumer is responsible for.

### Abstraction levels

* Physical Server
  * Bare Metal 

* Instance (VM)
  * AWS Lightsail
  * AWS EC2

* Container
  * ECS
  * EKS

* Function
  * Lambda


![AWS Compute Abstractions Visual Narrative](https://github.com/benjamin-s-hobbs/reading-notes/blob/main/401readings/AWSAbstraction8-1024x575.png)



## Questions for Understanding

1. Explain the levels of abstraction in AWS to someone without a technical background.

* Levels of abstraction can really be explained with Pizza as a Service (aka Homemade Vs Eating Out
)
* At the lowest levels of abstraction, you are going to do everything yourself, much like making a pizza from scratch. You need to pay for the ingredients, all of the equipment to put them together, the oven to make it, etc. You also need to provide flatware, napkins, drinks, and place to eat, and someone to serve the meal. At the end, you'll need to clean up and put things away.
  * With the next level of abstraction (Take and Bake), you don't need to grab the ingredients, put them together, or all of the equipment. Just grab it, heat it, and eat it. There's still clean up.
  * At the Pizza Delivery level, Just grab it, eat it, and clean up.
  * At the Dine-out level, just order, eat, and leave (no clean up). This would be the highest level of abstraction where the most work has been outsourced, and it is the most expensive...yet it saves the most time.

2. What are the control plane and data plane responsible for in container abstraction?

* The control layer is responsible for exposing the API and interfaces to define, deploy, and lifecycle containers.

* The data plane is responsible for providing capacity for the container can run and connect to a network 

3. Where does AWS Lambda fall in the layers of abstraction and what makes it so special? 

* Lambda is at the highest level of abstraction. It is an execution environment that allows a customer to run a single function. Lambda's event-driven model is what makes it special. Using the Amazon API Gateway-Lambda can be accessed directly as well. 

## What more do I want to know? 

## Additional Materials

Bookmark and Review
* [13 Compliance Frameworks for Cloud-based Orgs]()
* [Cloud Security Alliance (CSA)]()
* [Cloud Controls Matrix (CCM)]()
* [CSA Security Guidance for Cloud Computing]()