
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
  * https://personal.hsbc.co.uk/credit-cards/what-is-a-credit-limit/
  * https://www.accountingtools.com/articles/2017/5/10/invoice
  
  ## Overview
# Overall Description
  ## Product Perspective
  The system consists of a consultation application which will be high during each month's closing (29-31 days per month). The application needs communication with a database to show the highs that each client has had in relation to the products offered by the business, and in that way that does not allow to store more data once the credit limit is reached.
  
  ## Product Functions
  Before being able to use the system, the accounting assistant must have information such as the credit limit that the client has and the invoice of each purchase that he has made, and with this information he will be able to use the system to store in each invoice that the client has. and in case this exceeds its credit limit, the same system will launch an alert.
  
  ## Functional Requirements Specification
   ### Use Case: General
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
   
   ### Specific use case 2
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case2.jpg" height=50% width=50%></img></p>
   
   ### Specific use case 3
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case3.jpg" height=50% width=50%></img></p>
   
   ### Specific use case 4
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case4.jpg" height=50% width=50%></img></p>
   
   ### Specific use case 5
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case5.jpg" height=50% width=50%></img></p>
   
   ### Specific use case 6
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case6.jpg" height=50% width=50%></img></p>
   
   ### Specific use case 7
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-169870MichelleRincon/blob/master/SRS/Images/Use%20case7.jpg" height=50% width=50%></img></p>
    

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
   - [Use Case: General](#Use-Case-:-General)
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
 ## Appendixes
