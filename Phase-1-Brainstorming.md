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
