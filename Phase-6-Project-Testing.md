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
