iCounselor 
==============================

Built with the initial intent of use with the University of Akron

This project can be tracked here:  
https://trello.com/b/B9MFotRD/icounselor-app

# Data Model

* DegreeQualifications
	* Name
	* Parent Qualification *(for recursive qualifications)*
* DegreeQualificationsClasses *(Many-To-Many Relationship)*
	* DegreeQualification
	* Class
* Class
	* Class Name
	* Class Department
	* Class Section
	* Description
	* Prerequisites
* ClassInstance
	* Class Number
	* Room
	* Professor
	* Start Date
	* End Date
	* Start Time
	* End Time
	* Days of Week
* CartItem
	* ClassInstance
	* Date Added

# Class Questions

You need to make some decisions on your App. You will need to provide a start on the following:

## List of Team members

* Brian Kovacs bck25@zips.uakron.edu
* Joseph Fortunato jmf94@zips.uakron.edu
* Nick Artman dna5@zips.uakron.edu

## App Name

iCounselor

## Brief Description of App

Will marry the DARS reporting system and the University class scheduling system.  In effect, doing much of the repetitive job of a university advisor.

## Jobs to be done

We'll save you time and frustration by allowing you to see your graduation requirements without the hassle of using multiple systems simultaiously.

# External Data Sources

Theoretically DARS API, and API into the scheduling system.
