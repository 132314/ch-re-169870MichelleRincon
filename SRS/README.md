
  <h3 align="center"> Universidad Autonoma de Ciudad Juarez</h3>
  <h3 align="center"> División Multidisciplinaria de Ciudad Universitaria </h3>
  <h3 align="center"> Departamento de Ingeniería Electricidad y Computación </h3>
  <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Escudo%20uacj%202015-color-sin%20fondo.png" height="280" width="280"></img></p>
  <h3 align="center">SRS Document</h3>
  <h3 align="center">By:</h3>
  <h3 align="center">Tanya Michelle Rincon Tarango</h3>
  <h3 align="center">169870</h3>
  
  <h3 align="center">Development of Software Requirements</h3>
  <h3 align="center">April 2019</h3>
  
  
  
# Introduction
  ## Purpose
  The purpose of this document is to describe a solution for the grocery store "Central Chilera". This solution is to solve a need that arose within the establishment, which consists of a system that indicates the moment in which a client reaches his limit of credit and in that way the same system does not allow to enter more data.

Solving this problem will speed up work time and avoid having problems with customers for exceeding the limit.
  
  ## Scope  
This project consists of a system with the name of ***Credit*** which focuses on showing when a client reaches his limit of credit inside the store, therefore, it will be used by the accounting staff of this establishment.

The person who interacts directly with the product will be the accounting assistant and who is also the person identified as the main stakeholder, said person after using the product must submit a report to the chief accountant of the store. In the same way, before reaching the process of data capture, there are more people involved, such as customers, distributors, the administration area. , etc.

  ## Definitions, acronymus, and abbreviations
  **Credit limit**: "*The credit limit in a company is the maximum amount you can borrow from that company at any time. The credit provider will set your limit based on what you would like your limit to be and how much you can borrow.*".
  
  **Invoice**: "*is a document submitted to a customer, identifying a transaction for which the customer owes payment to the issuer. This document represents an asset of the issuer and a liability of the customer*".
  
  ## References
  * hsbc. (2012-2019). What is a credit limit?. 04/04/19, de HSBC UK Sitio web: https://personal.hsbc.co.uk/credit-cards/what-is-a-credit-limit/
  * Accounting Tools. (2019). Invoice. 04/04/19, de Accounting Tools Sitio web: https://www.accountingtools.com/articles/2017/5/10/invoice
  
  ## Overview
# Overall Description
  ## Product Perspective
  The system consists of a consultation application which will be high during each month's closing (29-31 days per month). The application needs communication with a database to show the highs that each client has had in relation to the products offered by the business, and in that way that does not allow to store more data once the credit limit is reached.
  
  ## Product Functions
  Before being able to use the system, the accounting assistant must have information such as the credit limit that the client has and the invoice of each purchase that he has made, and with this information he will be able to use the system to store in each invoice that the client has. and in case this exceeds its credit limit, the same system will launch an alert.
  
  ## Functional Requirements Specification
   ### General Use Case 
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/General%20Use%20Case.jpg" height=80% width=80%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Name: </td><td>Credit System</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/25/19</td></tr>
      <tr><td>Brief Description: </td><td>The application needs communication with a database to show the highs that each client has had in relation to the products offered by the business, and in that way that does not allow to store more data once the credit limit is reached. </td></tr>
      <tr><td>Actors: </td><td> Main Counter, Accounting assistant and Customers. </td></tr>
      <tr><td>Preconditions: </td><td>Before being able to use the system, the accounting assistant must have information such as the credit limit that the client has and the invoice of each purchase that he has made.</td></tr>
      <tr><td>Normal Flow: </td><td> <table align = "center">
    <thead>
      <tr><td>Main Counter</td><td>Accounting assistant</td><td>Customer</td></tr>
    </thead>
    <tbody>
      <tr><td>1. Collect customer data</td><td>4. Collect customer invoices.</td><td>Know your credit limit.</td></tr>
      <tr><td>2. Defines the customer's credit limit.</td><td>5. Enter the invoices in the system.</td><td>8. Receives final report</td></tr>
      <tr><td>7. Receives final report</td><td>6. Send the final report to the main accountant and then to the customer.</td><td></td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table></td></tr>
      <tr><td>Alternative flow: </td><td> <table align = "center">
    
   <thead>
      <tr><td>Main Counter</td><td>Accounting assistant</td><td>Customer</td></tr>
    </thead>
    <tbody>
      <tr><td></td><td>If the client exceeds the credit limit can not enter more data.</td><td>If you exceed your credit limit you receive a notice.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table></td></tr>
  <tr><td>Postconditions</td><td>All customer purchases will be stored for future procedures and / or clarifications.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
  
   ### Specific use case 1
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case1.jpg" height=50% width=50%></img></p>
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Collect customer data.</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td>The main accountant has to do the necessary data collection so that the client can start making large purchases within the business.</td></tr>
      <tr><td>Preconditions: </td><td>The client must be interested in using the store to stock up.</td></tr>
      <tr><td>Normal Flow: </td>
        <td>
          <table align = "center">
              <thead></thead>
              <tbody>
                <tr><td>The main counter collects data from the client, such as: recommendations, credit bureau, etc.</td></tr>
                <tr><td>Put the data in order</td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
       </td></tr>
      <tr><td>Alternative flow: </td>
        <td> 
          <table align = "center">
              <thead></thead>
              <tbody>
                <tr><td>If the main accountant is not available, the person in charge of collecting the data is the accounting assistant.</td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
      <tr><td>Postconditions</td><td>All data must be in order and not miss any.</td></tr>
    </tbody>
    <tfoot></tfoot>
  </table>
   
   ### Specific use case 2
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case2.jpg" height=50% width=50%></img></p>
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Defines the customer's credit limit.</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td>Before making any purchase, a credit limit must be assigned to the customer.</td></tr>
      <tr><td>Preconditions: </td><td>Data collection</td></tr>
      <tr><td>Normal Flow: </td>
        <td>
            <table>
                <thead></thead>
                <tbody>
                  <tr><td>Review again the information collected.</td></tr>
                  <tr><td>If the client is suitable, the main accountant should define a credit limit.</td></tr>
                </tbody>
                <tfoot></tfoot>
              </table>
        </td></tr>
      <tr><td>Alternative flow: </td>
        <td> 
            <table>
                <thead></thead>
                <tbody>
                  <tr><td><b>ONLY</b> the main accountant can define credit limit.</td></tr>
                </tbody>
                <tfoot></tfoot>
              </table>
        </td></tr>
      <tr><td>Postconditions</td><td>The client must know this information.</td></tr>
    </tbody>
    <tfoot></tfoot>
  </table>
   
   ### Specific use case 3
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case3.jpg" height=50% width=50%></img></p>
   
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Know your credit limit.</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td>The main accountant should show you what your credit limit will be.</td></tr>
      <tr><td>Preconditions: </td><td>The credit limit must already be defined and approved by the main accountant.</td></tr>
      <tr><td>Normal Flow: </td>
        <td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td>The main accountant offers you the credit limit that he considers acceptable.</td></tr>
                <tr><td>The customer makes the decision to accept or reject the offer.</td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
      <tr><td>Alternative flow: </td>
        <td> 
            <table>
              <thead></thead>
              <tbody>
                <tr><td>If the main accountant is not available, the accounting assistant can give the offer to the client.</td></tr>
                <tr><td>If the client <b>rejects</b> the offer, others are made until an agreement is reached.</td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>         
        </td></tr>
      <tr><td>Postconditions: </td><td>The customer can reject or accept the credit limit offered by the main accountant.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
  
   ### Specific use case 4
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case4.jpg" height=50% width=50%></img></p>
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Collect customer invoices.</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td>The customer invoices are delivered to the accounting assistant.</td></tr>
      <tr><td>Preconditions: </td><td>The customer must make some purchases and each must have an invoice.</td></tr>
      <tr><td>Normal Flow: </td>
        <td>
          <table>
            <thead></thead>
            <tbody>
              <tr><td>The invoices are delivered to the accounting assistant.</td></tr>
              <tr><td>The accounting assistant must order the invoices according to the date.</td></tr>
            </tbody>
            <tfoot></tfoot>
          </table>          
        </td></tr>
      <tr><td>Alternative flow: </td><td>There must not be any contradiction.</td></tr>
      <tr><td>Postconditions</td><td>The customer invoices are delivered to the accounting assistant.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
   
   ### Specific use case 5
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case5.jpg" height=50% width=50%></img></p>
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Enter the invoices in the system.</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td>The accounting assistant must enter the data of each invoice in the credit system.</td></tr>
      <tr><td>Preconditions: </td><td>The accounting assistant must have the invoices in order.</td></tr>
      <tr><td>Normal Flow: </td>
        <td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td> </td></tr>
                <tr><td> </td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
      <tr><td>Alternative flow: </td><td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td> </td></tr>
                <tr><td> </td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
      <tr><td>Postconditions: </td><td>It should be checked if the client exceeded the credit limit.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
   
   ### Specific use case 6
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case6.jpg" height=50% width=50%></img></p>
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Send the final report.</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td></td></tr>
      <tr><td>Preconditions: </td><td>The accounting assitant enters all invoices per customer in the system.</td></tr>
      <tr><td>Normal Flow: </td><td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td> </td></tr>
                <tr><td> </td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
      <tr><td>Alternative flow: </td><td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td> </td></tr>
                <tr><td> </td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
  <tr><td>Postconditions</td><td></td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
   
   ### Specific use case 7
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case7.jpg" height=50% width=50%></img></p>
   
   <table>
    <thead></thead>
    <tbody>
      <tr><td>Name: </td><td>Receives final report</td></tr>
      <tr><td>Author: </td><td>Tanya Michelle Rincon Tarango</td></tr>
      <tr><td>Date: </td><td>4/27/19</td></tr>
      <tr><td>Brief Description: </td><td></td></tr>
      <tr><td>Preconditions: </td><td>The accounting assistant sends the final report to the main counter and the customer.</td></tr>
      <tr><td>Normal Flow: </td><td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td> </td></tr>
                <tr><td> </td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
      <tr><td>Alternative flow: </td><td>
            <table>
              <thead></thead>
              <tbody>
                <tr><td> </td></tr>
                <tr><td> </td></tr>
              </tbody>
              <tfoot></tfoot>
            </table>
        </td></tr>
  <tr><td>Postconditions</td><td></td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
    

  ## User Characteristics
  There is only one person who interacts directly with the product, but in turn the chief accountant and each client must have knowledge through reports of the information stored in the system.

 <table>
    <thead>
      <tr><th>User</th><th>Description</th></tr>
    </thead>
    <tbody>
      <tr><td>Main Counter</td><td>You should receive a monthly report that mentions if a customer has reached your credit limit or how much was below the credit.</td></tr>
      <tr><td>Accounting assistant</td><td>It is the only person that interacts directly with the system, in charge of registering the consumption of each client.</td></tr>
      <tr><td>Customers</td><td>Receive monthly reports regarding your consumption in the store and receive an alert in case you reach your credit limit.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>

  
  ## Constraints
  The knowledge of the accounting assistant who manages the system may be the only limitation, because although the interface is relatively simple and its use, it must have knowledge about the client's data and the credit limit that each one has.
  
  ## Assumptions and dependencies
   | AS (Assumption) DE(Dependencies)| Description|
| ------------- |:-------------:| 
| AS-1| Only the acounting assistent.|
| AS-2| The final interface will be a desktop application for computer.|
| DE-1| Electricity for final device.|

# Specific requirements
  ## External Interfaces
  The ***Credit*** system has the purpose of alerting, by means of a message, when a client exceeds its credit limit. *Credit* is connected to a database in which the invoices of each client are stored and in turn gives the option to print or send the entered data. It is taken into account that each client has a credit limit of $ 300,000 Mexican pesos.

The database contains as attributes the customer identity (id), name, product name that I buy and the total purchase amount.

  ## Functions
  The system should allow the accounting assistant to capture information obtained from all the invoices held by each client.

For this, you need to follow a series of data:

1.  Record the sales data of the clients.
2.  The information will be stored in a database.
3.  In case the client exceeds his credit limit, an alert window will open.
4.  You will have the option to print the information collected.
  
  ## Performance requirements
* *The system will be designed to support connection between maximum two machines.*
* *Only one person can use the system simultaneously.*
* *You will receive numeric and string data for the name of the clients.*
  
  ## Logical database requirements
  The database with which the system will be linked will have the following attributes in a ***client table***:
* Customer id (primary key)
* Customer name
* Product name (forean key)
* Product Id
* Total amount

It is intended to link the client table with a ***product table*** in which the following attributes are shown:
* Product Id (primary key)
* Product name
  
  ## Design constraints
  The only restriction that can exist in the system is that it is not possible to link in more than one machine.
  
  ## Software system attributes
  Use of the Spanish language
Use of a Windows operating system.
Programmed in the java programming language to be portable in the machines.
  
  ## Organizing the specific requirements
  ## Additional comments
# Supporting Information
  ## Table of contents and index
 - [Introduction](#Introduction)
  - [Purpose](#Purpose)
  - [Scope](#Scope)
  - [Definitions, acronymus, and abbreviations](#Definitions,-acronymus,-and-abbreviations)
  - [References](#References)
  - [Overview](#Overview)
- [Overall Description](#Overall-Description)
  - [Product Perspective](#Product-Perspective)
  - [Product Functions](#Product-Functions)
  - [Functional Requirements Specification](#Functional-Requirements-Specification)
     - [General Use Case ](#General-Use-Case)
     - [Specific use case 1](#Specific-use-case-1)
     - [Specific use case 2](#Specific-use-case-2)
     - [Specific use case 3](#Specific-use-case-3)
     - [Specific use case 4](#Specific-use-case-4)
     - [Specific use case 4](#Specific-use-case-5)
     - [Specific use case 6](#Specific-use-case-6)
     - [Specific use case 7](#Specific-use-case-7)
  - [User Characteristics](#User-Characteristics)
  - [Contraints](#Constraints)
  - [Assumptions and dependencies](#Assumptions-and-dependencies)
- [Specific requirements](#Specific-requirements)
  - [External Interfaces](#External-Interfaces)
  - [Functions](#Functions)
  - [Performance requirements](#Performance-requirements)
  - [Logical database requirements](#Logical-database-requirements)
  - [Design constraints](#Design-constraints)
  - [Software system attributes](#Software-system-attributes)
  - [Organizing the specific requirements](#Organizing-the-specific-requirements)
  - [Additional comments](#Additional-comments)
- [Supporting Information](#Supporting-Information)
  - [Table of contents and index](#Table-of-contents-and-index)
  - [Appendixes](#Appendixes)
    - [Elicitation Process](#Elicitation-Process)
      - [Bussines Process Diagram](#Bussines-Process-Diagram)
 ## Appendixes
  ### Elicitation Process
   <b>Description:</b> 
   It was carried out through an interview with the person who is directly involved with the desired System, the accounting assistant.

During the interview the accounting assistant gave a list of requirements with which he wanted the system to count:

"I want the System that is made to carry out these operations:
* Give me the option to change or delete if I am wrong to enter an invoice.

* Have an initial knowledge of what is the credit limit of each one of the clients that we have, and that also allows us to update that data if more Adelante is necessary.

* Since the System must already know the credit limit, I would like it to stop allowing me to enter more invoices if the client has already passed, since I usually do not realize until I finish with everything and that takes time away.

* When I finish billing every month, I have to deliver a report to my boss and the client so he is aware of the purchases I make, so it would be fine if I also have the option to print so I do not have to do it anymore. other side.

* It does not necessarily have to be nice because I will only use it, but I need it to be neat and clean so that all my work is easier "


After what the accounting assistant mentioned that he wanted in the system it was concluded that in summary what is desired and expected is that it has a CRUD process (Create, Read, Update, Delete) to manage the data that he has you want Similarly an extra section (button) that is responsible for printing the table of monthly purchases that had a specific customer for later this be delivered to their superior and the respective customer. Although a detailed visual application is not expected, it is possible to proceed through a basic and neutral interface, as long as the CRUD processes are present.

   #### Bussines Process Diagram
   https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/tree/master/SRS/BPM
   
   <img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/bmp.jpg" border="1" alt="Bussines Process Diagram" width="120%" height="120%">

<img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/bmp_subprocess1.jpg" border="1" alt="Bussines Process Diagram" width="120%" height="120%">

<img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/bmp_subprocess2.jpg" border="1" alt="Bussines Process Diagram" width="120%" height="120%">
