---
layout: post
title:  "Automated integration test"
date:   2020-05-16 08:21:05 +1000
categories: coding Saturday
---
Today I worked to make my automated integration test working. 

The team builds a data feeder by taking data through SQL query from a legacy system which is using mssql server. 
It saves the last record in dynamo database based on unique identifier and last update. The data feeder uses AWS lambda sending the 
records to the service and saves in postgres database. 

The approach to automate the process is using docker to build a test mssql database and a test dynamo database which avoids to talk to 
database directly for testing. In this approach it can make the test more reliable and less dependency on other system. It also mocks the service layer 
for sending data as the saving data part can be tested in the service layer. So far, I think this approach is great. 
I was struggling initially how to automate it and what to automate. 
