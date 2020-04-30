# Hagz
Appointment integrated solution
---
Hagz is appointment system designed to easily plugged into any access control system to provide end to end management of appointments, the idea is to prevent people from overcrowded in any public or private services.
The idea behind Hagz is to reduce the traffic at any service provider to reduce the spread of COVID-19 especially after the lock down is relieve in most of the countries.  
The main design concept here is to build a solution with minimal configurations and easily plugged into any existing access control systems.  
When Hagz is plugged into the system it will allow the service provider to publish the available appointments for the service with the exact capacity e.g. number of employees who provide the service, customers can pick the required appointment slot and they will get QR Code into their mobile. Access controls won't let the customer to enter inside the service provider unless his\her appointment. This will guarantee that no overcrowded at the service provider site. The customer must feed the reason of this appointment request so the service provider can deny/reject the appointment as well.  
For example, a bank will install the Hagz solution and enable the customers to book their appointments in advance so they will get their appointment confirmation and they won't be permitted to enter the bank unless the QR code permit them.  
The overall solution is based on traditional appointment booking system with all the features of scheduling, booking, rescheduling, alerts, payment integration, calendar sync, etc.  It also includes Camel for easily integration using different technologies with the existing infrastructure. Standard REST APIs will be enabled to allow pluggability and control of the system e.g. feeding different appointment.  
The system will enable the integration with backend system via the REST APIs to populate the appointments and service capacity (e.g. attendance system, ERP, vacation system. etc.)  
Finally the appointment booking will have a workflow step that will do check based on the customer unique identifier in a public exposed service to check if this person has COVID-19 or contacted a person with COVID-19 and accordingly the appointment can be scheduled or denied or scheduled with precaution or in a special conditions/locations.  
It will be enterprise grade solution with SSO integration as well.

# Solution Overview

![Hagz_overview](https://user-images.githubusercontent.com/18471537/80750622-b0d62b80-8b28-11ea-9b60-dac5200524d1.png)

This is an overview of the solution with the potential integration points.




