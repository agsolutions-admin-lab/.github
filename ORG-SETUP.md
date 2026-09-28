# AG Solutions GitHub Organization Setup

## 1. Purpose

AG Solutions Admin Lab is a practice GitHub organization created
for learning GitHub administration, repository management,
access control, permissions, and security.

This organization is used as a sandbox environment and does
not contain production workloads.

---

## 2. Organization Profile

**Organization:** AG Solutions Admin Lab

**Description:**  
Practice organization for learning GitHub administration,
access control, repository management, and security.

An organization profile README is maintained in:

`.github/profile/README.md`

The README explains the purpose of the organization,
administration responsibilities, and the access request process.

---

## 3. Base Repository Permission

**Configured setting:** No permission

The organization's base repository permission is configured
as **No permission**.

### Reason

Organization members should not automatically receive access
to repositories.

Repository access should instead be granted based on:

- Team membership
- Job responsibilities
- Repository requirements

This supports the principle of least privilege.

---

## 4. Organization Roles

### Owner

Owners have administrative control over the GitHub organization.

Owners can manage organization settings, members, teams,
repositories, permissions, and security settings.

### Member

Members are normal users of the organization.

Repository access should be granted according to the member's
responsibilities through teams or repository-specific permissions.

### Billing Manager

Billing managers are responsible for billing-related activities.

A user who only needs to manage billing should not be given
the Owner role simply for billing responsibilities.

---

## 5. Two-Factor Authentication

**Recommendation:** Require two-factor authentication (2FA)
for organization users.

### Reason

2FA provides an additional layer of account security.

If a user's password is compromised, the second authentication
factor helps protect access to GitHub organization resources.

---

## 6. Repository Access Process

Repository access should follow a controlled process.

1. User requests access to a repository.
2. User specifies the repository name.
3. User specifies the required permission.
4. User provides a business reason for the access.
5. The GitHub administrator reviews the request.
6. Access is granted through the appropriate team or repository permission.
7. Access should be reviewed periodically.

Example:

User: Developer A  
Repository: backend-api  
Requested permission: Write  
Reason: Developer works on the backend application.

---

## 7. Access Control Principle

AG Solutions follows the principle of least privilege.

Users should receive only the permissions required to perform
their responsibilities.

Default access is therefore kept restrictive, and additional
repository access is granted when required.
