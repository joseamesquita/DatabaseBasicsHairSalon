# _Hair Salon_

#### _Individual Project_

#### By _Jose Amesquita_

## Description

_Application project to manage and operate the Hair Salon by creating a database that includes the stylists and clients._

## Behavior Driven Development
| Behavior | Input | Output |
|----|----|-----|
| user may add stylists | user selects the add a stylist button | returns page to create a stylist |
| user selects add a stylist | user inputs stylist name and hire date then selects add | returns page to list of stylists | 
| list of stylists page | user selects one of the stylists that have been created | returns details of stylist |

## Objectives 

* Database table and column names follow gerneral .NET naming conventions
* Re-create database
* Application uses one-to-many relationship
* CREATE and VIEW functionality included 
* Entity used for communication with the database

## SQL

CREATE DATABASE `jose_amesquita`;

USE `jose_amesquita`;

CREATE TABLE `stylists` (  
  `StylistId` int(11) NOT NULL AUTO_INCREMENT,  
  `StylistName` varchar(255) DEFAULT NULL,  
  PRIMARY KEY (`StylistId`)  
);

CREATE TABLE `clients` (  
  `ClientId` int(11) NOT NULL AUTO_INCREMENT,  
  `ClientName` varchar(255) DEFAULT NULL,   
  `Rating` int(11) DEFAULT NULL,  
  `Review` varchar(255) DEFAULT NULL,  
  `StylistId` int(11) DEFAULT '0',  
  PRIMARY KEY (`ClientId`)  
);

## Technologies Used

* Git
* C#
* .NET Core
* ASP.NET Razor
* MySQL
* Entity Framework Core

### License

*Licensed under the MIT License*

Copyright (c) 2020
