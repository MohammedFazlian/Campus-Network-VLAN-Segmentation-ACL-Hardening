# Department Network with ACL Based Access Control

This project was built to simulate how a real company manages 
access between different departments. Each department has its 
own server and can only access what they are supposed to.

## The Scenario

A company with 6 departments — Sales, Marketing, Accounts, 
Admin, Front Desk, and Logistics. Each department had their 
own dedicated server storing their data. The goal was to make 
sure each department could only reach their own server and 
restricted departments could not communicate with each other.

## What I Implemented

- Separate network segments for each department
- Dedicated servers for each team's data
- ACLs to restrict which department can access which server
- Controlled inter-department communication based on 
  business requirements

## What This Solves

In real companies sensitive data like accounts and admin 
information should never be accessible to sales or front desk 
staff. This project simulates exactly that kind of access 
control policy.

## Tools Used

- Cisco Packet Tracer

## Author

Mohammed Fazlian
Cybersecurity Enthusiast
[LinkedIn] | [Email]
