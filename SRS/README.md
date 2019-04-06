
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
  
  ## User Characteristics
  There is only one person who interacts directly with the product, but in turn the chief accountant and each client must have knowledge through reports of the information stored in the system.
  
  | User| Description|
| ------------- |:-------------:| 
| Main Counter| You should receive a monthly report that mentions if a customer has reached your credit limit or how much was below the credit.|
| Accounting assistant| It is the only person that interacts directly with the system, in charge of registering the consumption of each client.| 
| Customers|Receive monthly reports regarding your consumption in the store and receive an alert in case you reach your credit limit.|
  
  ## Constraints
  The knowledge of the accounting assistant who manages the system may be the only limitation, because although the interface is relatively simple and its use, it must have knowledge about the client's data and the credit limit that each one has.
  
  ## Assumptions and dependencies
   | AS (Assumption) DE(Dependencies)| Description|
| ------------- |:-------------:| 
| AS-1| Only the assistent acounting.|
| AS-2| The final interface will be a desktop application for computer.|
| DE-1| Electricity for final device.|

# Specific requirements
  ## External Interfaces
  ## Functions
  ## Performance requirements
  ## Logical database requirements
  ## Design constraints
   ### Standar compliance
  ## Software system attributes
   ### Realibility
   ### Availability
   ### Segurity
   ### Maintiability
   ### Portability
 ## Organizing the specific requirements
   ### System mode
   ### User class
   ### Objects
   ### Feature
   ### Stimulus
   ### Response
   ### Functional hyerarchy
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
  - [User Characteristics](#User-Characteristics)
  - [Contraints](#Constraints)
  - [Assumptions and dependencies](#Assumptions-and-dependencies)
- [Specific requirements](#Specific-requirements)
  - [External Interfaces](#External-Interfaces)
  - [Functions](#Functions)
  - [Performance requirements](#Performance-requirements)
  - [Logical database requirements](#Logical-database-requirements)
  - [Design constraints](#Design-constraints)
    - [Standar compliance](#Standar-compliance)
  - [Software system attributes](#Software-system-attributes)
    - [Realibility](#Realibility)
    - [Availability](#Availability)
    - [Segurity](#Segurity)
    - [Maintiability](#Maintiability)
    - [Portability](#Portability)
  - [Organizing the specific requirements](#Organizing-the-specific-requirements)
    - [System mode](#System-mode)
    - [User class](#User-class)
    - [Objects](#Objects)
    - [Feature](#Feature)
    - [Stimulus](#Stimulus)
    - [Response](#Response)
    - [Functional hyerarchy](#Functional-hyerarchy)
  - [Additional comments](#Additional-comments)
- [Supporting Information](#Supporting-Information)
  - [Table of contents and index](#Table-of-contents-and-index)
  - [Appendixes](#Appendixes)
 ## Appendixes
