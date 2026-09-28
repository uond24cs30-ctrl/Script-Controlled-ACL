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
