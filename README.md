# _Hair Salon_

#### _Individual Project_

#### By _Jose Amesquita_

## Description

_Application project to manage and operate the Hair Salon by creating a database that includes the stylists and clients._

## Behavior Driven Development
| Behavior | Input | Output |
|----|----|-----|
|  |  |  |


## Setup/Installation Requirements



## SQL

CREATE DATABASE `hair_salon`;

USE `hair_salon`;

CREATE TABLE `stylists` (  
  `StylistId` int(11) NOT NULL AUTO_INCREMENT,  
  `StylistName` varchar(255) DEFAULT NULL,  
  PRIMARY KEY (`StylistId`)  
)

CREATE TABLE `clients` (  
  `ClientsId` int(11) NOT NULL AUTO_INCREMENT,  
  `Name` varchar(255) DEFAULT NULL,   
  `Rating` int(11) DEFAULT NULL,  
  `Review` varchar(255) DEFAULT NULL,  
  `StylistId` int(11) DEFAULT '0',  
  PRIMARY KEY (`ClientId`)  
)

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