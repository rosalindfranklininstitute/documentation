# SciCat



## What?

A project to catalogue and provide access to metdatdata and raw experimental data.

## How?

Scicat is made up of the following technologies:

* Web based frontend - [Catanie](https://github.com/SciCatProject/catanie): An Angular \(2+\) based application that uses ngrx to communicate with the SciCat API and provide a searchable interface for datasets, as well as the option to carry out actions \(i.e. archiving\) and acts as a place to reference datasets used in publications.

* API Server - [Catamel: ](https://github.com/SciCatProject/catamel)A NodeJS application that uses the Loopback framework to generate RESTful APIs from JSON files that define models \(such as: Users, Datasets, Instruments etc\). Follows the Swagger API format and SDKs can be generated in almost any language.
* Database - MongoDB
* Data Ingesting - NODE-RED
* * 




