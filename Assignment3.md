# CS410/560 - Software Engineering
## Assignment 3 G AN
## Group members : Yi Ren (002269013), Wentao Lu (002276355)
## Requirements Engineering


### 1.List and discuss major drawbacks of using natural language for specifying requirements.
(1)Natural language description requires it's readers to know a lot of tacit knowledge. If not, it's hard for readers to understand the description.  
(2)In practice the natural language description may be out of date, like software documentation, their validity tends to deteriorate with time.
    In this way, natural language descriptions are always used at the beginning of the objective-oriented analysis.
<p align="right">[1,page 219]</p>

### 2. For an office information system, identify different types of stakeholders. Can you think of ways in which the requirements of these stakeholders might conflict?
(1)The stakeholder of the information system may include
    the boss who pays for the system,
    managers and employees who use the system for their daily work.

(2)For the boss or the employer, they may concern about the cost and effect of the system, in other words, their main requirement is a system that can improve productivity at an affordable price.
    For the managers, they don't care how much the system cost, all that they concern about is productivity, or to say the KPI of the employee in the department.
    For the employee, their main requirement for the system is convenience. The office information system may simplify their working process and do some easy jobs automatically. They don't care about the price or the overall KPI.
<p align="right">[1,page 202,204,207]</p>

### 3. Discuss the pros and cons of the following descriptive means for a requirements specification: full natural language, constrained natural language, a pictorial language like UML.
(1)Full natural language: Easier for users to describe their needs because users are more familiar
with natural language. Also it is is very readable and understandable to the user and other non-professionals involved.
On the other hand, it's relatively hard for developers to understand the requirement, considering that the natural language
may be ambiguous and misleading, so it will take more time to negotiate about the requirement.  
(2)Constrained natural language(CNL), with a constrained vocabulary, natural language can be used to specify a more accurate requirement. However, the users are required to have some basic knowledge for CNL to determine if the requirement has satisfied their real needs.   
(3)Pictorial language, which is a straightforward and accurate method for developers to recognize the requirement.
It will increase efficiency, because it allows us to use tools in analyzing the requirements, however, it will spend more time to specify the requirement.
<p align="right">[1,page 243-244]</p>

### 4. Which of the descriptive means mentioned in the previous exercise would you favor for describing the requirements of an office automation system? Justify your answers.
In my point of view, what method should to choose depends on the scale and complexity of the project.
An office automation system is obviously a complex project which may need several teams to work together. So a pictorial language like UML could be better than other means. Because it will ease the requirement management and also make developers thoroughly understand the requirement without ambiguities.

## Requirements Engineering
We are interested in an express home delivery company. Customer service receives customers every day who want delivery in France or abroad. This service manages two categories of packages:  
Light packages or letters whose weight is? at 2 kg,  
Heavy packages or packages weighing> 2 kg.  

The price is calculated according to the weight of the package and its destination with a flat rate of 10 Euros if the customer chooses a shipment with acknowledgment of receipt. The Customer Service then records the references of the customer packages (sender + recipient contact details, weight, etc.) on a computer and prints out a receipt for the customer. The invoicing of light packets or destined for France is also managed by this service. Once the payment has been made, the service forwards the package to the Logistics department for delivery.  

Heavy packages, for international destinations, must comply with customs regulations and must be subject to heavier procedures that end their delivery time by at least 48 hours and are over-invoiced by 10%. In particular, the customer must complete and sign a transport package that specifies the nature and the value of the content of the package (s) to be transported. The package, accompanied by this document, is sent to the company's Export department.  

Packages weighing more than 20 kg or, the content of which is listed in a list of goods well defined by customs regulations, must undergo formalities with French customs, in conjunction with the Export service. The package cannot be forwarded before customs agreement which is materialized by a slip with the references of the package to be forwarded and the amount of the tax charged to the customer. The export department of the company then transmits the information to the billing department. The latter then issue the final invoice to the customer. After payment, the Export department is informed and transmits the package with the customs slip to the Logistics service which takes care of the delivery.

### WORK TO DO:
### 1. Give the use case diagram that describes how this company works.
Refer to attachment：1-UseCase.jpg for details.
<div align=center><img src="http://www.just4fun2u.top/wp-content/uploads/2020/03/1-UseCase-1024x960.png" width="80%" height="80%"></div>


### 2. Describe the static structure of this system using a class diagram.
Refer to attachment：2-ClassDiagram.jpg for details.
<div align=center><img src="http://www.just4fun2u.top/wp-content/uploads/2020/03/2-ClassDiagram-1024x658.png" width="80%" height="80%"></div>


### 3. Describe the main scenario triggered by Customer Service using a sequence diagram.
There are two conditions for the sequence diagram:  
for the light or domestic packages, Refer to attachment：3.1-Sequence.jpg  
for the heavy international packages, Refer to attachment：3.2-Sequence.jpg

<div align=center><img src="http://www.just4fun2u.top/wp-content/uploads/2020/03/3.1-Sequence-1024x562.png " width="80%" height="80%"></div>
<p align="center">3.1-Sequence.jpg</p>

<div align=center><img src="http://www.just4fun2u.top/wp-content/uploads/2020/03/3.2-Sequence-1024x554.png" width="80%" height="80%"></div>
<p align="center">3.2-Sequence.jpg</p>

## References
1. Hans van Vliet. Software Engineering: Principles and Practice. Wiley 2007
