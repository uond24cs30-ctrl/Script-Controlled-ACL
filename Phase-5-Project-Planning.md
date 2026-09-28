# Phase 5 – Project Development

## Project Implementation

The project was implemented in ServiceNow using users, roles, a custom table, records and Access Control Lists (ACLs).

## User Creation

An EEE User was created in ServiceNow with the required user details.

## Role Creation

The following roles were created:

- bb1
- bb2
- bb3
- bb4

The roles were assigned to the EEE User.

## Table Creation

A table named Institution Details was created.

Table Name:
u_institution_details

## Fields Created

- Student Roll Number
- Student Name
- Faculty Name
- Branch
- Email
- Phone Number
- Description

## Records

Records were created with different Branch values:

- ECE
- EEE
- CSE

## ACL Implementation

### Read ACL
A Read ACL was created for the Institution Details table. The Branch condition was set to EEE and the bb1 role was used.

### Create ACL
A Create ACL was created using the bb2 role.

### Write ACL
A Write ACL was created using the bb3 role.

### Delete ACL
A Delete ACL was created using the bb4 role.

## Script

The Read ACL uses a script to allow administrators and users with the required role to access the records.

## Implementation Result

The ACLs were successfully implemented to control Read, Create, Write and Delete access to the Institution Details records.
