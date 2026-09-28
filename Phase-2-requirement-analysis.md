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
