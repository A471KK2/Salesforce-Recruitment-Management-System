# Salesforce Recruitment Management System

## Overview

A Salesforce-based recruitment management application developed
using Salesforce Administration and declarative configuration.

The project focuses on managing job positions and their related
requirements, compensation, skills, location, and hiring timelines.

## Project Status

In Progress

## Salesforce Application

Created a custom Salesforce application named **Recruiting** with
a dedicated Lightning Page and Positions navigation tab.

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

- Custom Position object
- Custom fields
- Custom Position page layout
- Picklist fields
- Checkbox fields
- Currency fields
- Date fields
- Long Text Area fields
- Formula field
- Field Dependency

## Automation & Data Logic

Implemented a **Days Open** formula field to calculate the
duration of an open position.

Configured a default value for the **Hire By** field.

Implemented a field dependency where **Job Level** is controlled
by **Functional Area**.

## User Interface

Configured the Recruiting Lightning Page, application navigation,
Positions tab, and Position page layout for managing recruitment
position records.

## Screenshots

### Recruiting Application
![Recruiting Application](screenshots/01-recruiting-app.png)

### Position Object & Fields
![Position Fields](screenshots/02-position-fields.png)

### Position Page Layout
![Position Layout](screenshots/03-position-layout.png)

### Functional Area & Job Level Dependency
![Field Dependency](screenshots/04-field-dependency.png)

### Days Open Formula
![Days Open Formula](screenshots/05-days-open-formula.png)

## Current Scope

The current implementation focuses on Salesforce Administration,
data modelling, UI configuration, validation/data logic, and
declarative features.

The project is currently in progress.

## Future Enhancements

- Additional recruitment objects
- Recruitment process automation using Flow
- Candidate and application management
- Additional security configuration
- Advanced Salesforce automation
