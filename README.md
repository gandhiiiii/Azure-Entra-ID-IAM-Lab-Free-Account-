# Azure-Entra-ID-IAM-Lab-Free-Account-

This lab demonstrates hands-on experience with Identity & Access Management (IAM) using Azure Entra ID. The goal is to simulate enterprise identity lifecycle, enforce least privilege, and implement secure authentication policies within a free Azure account.

## Lab Objective
- Create users and groups to simulate employee, admin, and contractor roles
- Assign role-based access control (RBAC)
- Enable Multi-Factor Authentication (MFA)
- Verify policies via Sign-in logs

## Users
<img width="1333" height="442" alt="Users" src="https://github.com/user-attachments/assets/69ba915e-808a-47e0-a35e-bf57b687a233" />

Created three types of users: Employee, Admin, and Contractor. All emails are fake for lab purposes.

## Groups
<img width="1297" height="438" alt="Groups" src="https://github.com/user-attachments/assets/49ea1917-866b-4140-96af-e3f339c63cf2" />

Implemented role-based access control by grouping users according to job function (Employees, IT-Admins, Contractors).

## RBAC Role Assignments
<img width="1413" height="736" alt="Roles" src="https://github.com/user-attachments/assets/bea896ed-142f-4db9-b5bb-d98f98e01d31" />

Assigned least privilege roles to IT-Admins group: Global Reader and User Administrator.

## Multi-Factor Authentication (MFA)
<img width="1841" height="702" alt="MFA" src="https://github.com/user-attachments/assets/614b288b-a55b-4280-8a9b-ac6ca997a191" />

Configured MFA for all users to enforce secure login. Fake users used in screenshots.

## Conditional Access (Conceptual)

Conditional Access policies allow enforcement of MFA, app restrictions, and location-based access.  
*Not implemented in this lab due to Premium P1 requirements, but understood conceptually.*

## Self-Service Password Reset (SSPR) (Conceptual)

Self-Service Password Reset reduces helpdesk tickets and allows users to reset their passwords securely.  
*Not implemented in this lab, but noted as part of IAM best practices.*

## Lesson Learned

- IAM implementation requires least privilege principles
- MFA improves authentication security significantly
- Understanding Conditional Access and SSPR is key for enterprise IAM
- Demonstrated core IAM skills using Azure Entra ID free tier

## Safety Note

- All emails and tenant names in screenshots are fake
- No personal or billing information is exposed
