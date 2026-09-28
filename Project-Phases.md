# Phase 1 – Brainstorming & Ideation

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Project Idea
The project aims to implement a script-controlled Access Control List (ACL) in ServiceNow to restrict users from viewing records based on the Branch field and user roles.

## Problem Statement
Unauthorized users should not be allowed to access restricted records. The system should control record access based on the user's role and the Branch value.

## Objective
To implement record-level security in ServiceNow using script-controlled ACLs.

## Proposed Solution
A ServiceNow Institution Details table is created with different branch records such as ECE, EEE and CSE. ACL rules are implemented to control Read, Create, Write and Delete access based on user roles.

## Expected Outcome
The system should allow authorized users to access the required records while restricting unauthorized access.
# Phase 2 – Requirement Analysis

## Project Requirements

### Platform
ServiceNow

### User
EEE User

### Roles
- bb1 – Read
- bb2 – Create
- bb3 – Write
- bb4 – Delete

### Table
Institution Details

### Table Name
u_institution_details

### Fields
- Student Roll Number – Auto Number
- Student Name – Reference User
- Faculty Name – Reference User
- Branch – Choice
- Email – String
- Phone Number – String
- Description – Multi String

### Branch Values
- ECE
- EEE
- CSE

### ACL Requirements
- Read access is controlled based on the Branch value and user role.
- Create access is controlled using the bb2 role.
- Write access is controlled using the bb3 role.
- Delete access is controlled using the bb4 role.
- Admin users have full access.

## Expected Requirement
The system should restrict unauthorized users and allow authorized users to access records according to their assigned roles.
# Phase 3 – Project Design

## Project Structure

The project uses ServiceNow ACLs to control access to Institution Details records.

## Access Control Design

User
↓
User Roles
↓
Access Control Lists (ACLs)
↓
Institution Details Records

## Role-Based Access

- bb1 – Read access
- bb2 – Create access
- bb3 – Write access
- bb4 – Delete access

## Read Access Design

The Read ACL uses the Branch field condition. Users with the required role can view the EEE records.

## Administrator Access

The Admin user has full access to the records.

## ACL Operations

The project contains ACLs for:
- Read
- Create
- Write
- Delete

## Expected Design Outcome

The system controls access to records according to the user's assigned roles and the defined ACL rules.
# Phase 4 – Project Planning

## Project Plan

The project is planned and implemented in the following steps:

1. Create the EEE User in ServiceNow.
2. Create the roles bb1, bb2, bb3 and bb4.
3. Assign the required roles to the EEE User.
4. Create the Institution Details table.
5. Create the required fields in the table.
6. Add records with ECE, EEE and CSE branch values.
7. Create the Read ACL with the Branch = EEE condition.
8. Create the Create ACL using the bb2 role.
9. Create the Write ACL using the bb3 role.
10. Create the Delete ACL using the bb4 role.
11. Test the ACLs using the EEE User.
12. Verify that the Admin can access all records.

## Tools Used

- ServiceNow
- ServiceNow Access Control Lists (ACLs)

## Expected Result

The project should provide controlled access to Institution Details records based on user roles and the Branch value.
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
# Phase 6 – Project Testing

## Testing Process

The project was tested by impersonating different users and verifying the access provided by the ACLs.

## Read Access Testing

- The EEE User with the required bb1 role can view only the EEE records.
- A user without the required role cannot view the restricted records.
- The Admin user can view all records.

## Create Access Testing

A user with the bb1 and bb2 roles can view the EEE records and use the New option to create a record.

## Write Access Testing

A user with the bb1, bb2 and bb3 roles can view and edit the EEE records.

## Delete Access Testing

A user with the bb1, bb2, bb3 and bb4 roles can view, create, edit and delete the EEE records.

## Test Result

The ACLs successfully controlled the Read, Create, Write and Delete operations according to the assigned user roles.
# Phase 7 – Project Documentation

## Project Title

Script-Controlled ACL – Restrict Record Access Based on Field Value

## Objective

The objective of this project is to implement script-controlled ACLs in ServiceNow to control access to records based on user roles and the Branch field.

## Platform Used

ServiceNow

## Table Used

Institution Details

Table Name:
u_institution_details

## ACL Operations

The project implements ACLs for the following operations:

- Read
- Create
- Write
- Delete

## Access Control

The Read ACL restricts record access based on the Branch value. The required role can view the EEE records, while the Admin has full access.

The Create, Write and Delete operations are controlled using the respective roles bb2, bb3 and bb4.

## Testing Result

The ACL functionality was tested with different user roles. The required access was provided according to the assigned roles.

## Conclusion

The project demonstrates how ServiceNow ACLs can be used to provide record-level security and control user access to records based on roles and field values.
# Phase 8 – Project Demonstration

## Project Name

Script-Controlled ACL – Restrict Record Access Based on Field Value

## Purpose of the Project

The purpose of the project is to restrict record access in ServiceNow based on the Branch field and user roles using Access Control Lists (ACLs).

## Project Benefits

- Provides record-level security.
- Restricts unauthorized access.
- Controls Read, Create, Write and Delete operations.
- Provides full access to Admin users.

## Project Execution

The project demonstration includes:

1. Showing the Institution Details table.
2. Showing the created records with different Branch values.
3. Demonstrating the Read ACL.
4. Showing that the EEE User can view the EEE records.
5. Demonstrating the Create, Write and Delete ACLs.
6. Showing that the Admin can access all records.

## Final Output

The ACLs successfully control access to the Institution Details records according to user roles and the Branch value.

## Demo Video

A complete project demonstration video was recorded with screen sharing and voice-over explanation. The video includes the Project Name, Purpose, Benefits, Working Process and Final Output.

The demo video is uploaded to Google Drive and the sharing permission is set to Anyone with the link can view.
