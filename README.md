# Salesforce Recruitment Management System

## Overview

A Salesforce-based recruitment management application developed
using Salesforce Administration and declarative configuration.

The project focuses on managing recruitment positions, job
requirements, skills, compensation, applications, candidates,
and related recruitment processes.

## Project Status

In Progress

## Salesforce Application

Created a custom Salesforce application named **Recruiting** with
a dedicated Lightning Page and multiple navigation tabs for
managing recruitment-related information.

## Key Salesforce Components

- Custom Objects
- Custom Fields
- Page Layouts
- Object Relationships
- Field Dependencies
- Formula Fields
- Validation Rules
- Profiles
- Declarative Configuration

## Position Management

The project includes a custom **Position** object with fields for:

- Position Title
- Job Description
- Responsibilities
- Skills Required
- Educational Requirements
- Min Pay
- Max Pay
- Open Date
- Hire By
- Close Date
- Travel Required
- Location
- Status
- Type
- Functional Area
- Job Level
- Java
- JavaScript
- C#
- Apex

## Data Modelling & Configuration

- Custom recruitment objects and fields
- Position page layout
- Picklist and checkbox fields
- Currency and date fields
- Long Text Area fields
- Formula fields
- Field Dependencies
- Schema configuration

## Automation & Data Logic

Implemented a **Days Open** formula field to calculate the
duration associated with an open position.

Configured a default value for the **Hire By** field.

Implemented a field dependency where **Job Level** is controlled
by **Functional Area**.

## User Interface

Configured the Recruiting Lightning Page and application
navigation with tabs for recruitment-related records including
Positions, Candidates, Job Applications, Employment Website,
Job Posting, and Review.

## Screenshots

### Schema Diagram
![Recruiting Schema Diagram](Screenshot/01-recruiting-app%20schema%20diagram.png)

### Position Tab
![Position Tab](Screenshot/02-recruiting-app%20position%20tab.png)

### Custom Objects
![Custom Objects](Screenshot/03-recruiting-app%20Custom%20objects.png)

### Associated Profiles
![Associated Profiles](Screenshot/04-recruiting-app%20associated%20Profiles.png)

### Validation Rules
![Validation Rules](Screenshot/05-recruiting-app%20associated%20Validation%20Rules.png)

### Candidate Tab
![Candidate Tab](Screenshot/06-recruiting-app%20Candidate%20Tab.png)

### Job Application Tab
![Job Application Tab](Screenshot/07-recruiting-app%20Job%20Application%20Tab.png)

### Employment Website Tab
![Employment Website Tab](Screenshot/08-recruiting-app%20Employment%20Website%20Tab.png)

### Job Posting Tab
![Job Posting Tab](Screenshot/09-recruiting-app%20Job%20Posting%20Tab.png)

### Review Tab
![Review Tab](Screenshot/10-recruiting-app%20Review%20Tab.png)

## Current Scope

The current implementation focuses on Salesforce Administration,
data modelling, UI configuration, validation, field dependencies,
formula fields, security configuration, and declarative features.

The project is currently in progress.

## Future Enhancements

- Recruitment process automation using Flow
- Additional recruitment workflow configuration
- Advanced security configuration
- Additional business process automation
