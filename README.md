# Task Check System

## Overview
The **Task Check System** is a collaborative tool designed to help teams manage and track tasks efficiently. It allows team members to assign tasks, monitor progress, and handle subtasks. The system is structured to support multiple teams and multiple tasks per team, with roles and permissions that ensure leaders have control over task assignment and management.

### Key Features
- **Task Management**: Create tasks with details like owner, status, and due time.
- **Subtasks**: Break down larger tasks into smaller, manageable subtasks.
- **Team Support**: Teams can handle multiple tasks at once.
- **Leader Permissions**: Only the team leader can reassign tasks to any collaborator. Other team members can move only unassigned tasks or their own.
- **Task Status**: Each task has a status: `To Do`, `Doing`, or `Done`.
- **Collaborator Assignment**: Assign specific team members to work on tasks and subtasks.
- **Multi-Team Support**: Leaders can oversee and manage multiple teams.

---

## Roles

### Team Leader
- Can assign tasks to any team member.
- Can move tasks between members.
- Can manage multiple teams.
- Full control over task status and assignment.

### Collaborators
- Can only move tasks that are unassigned or those that they own.
- Can create and update subtasks.
- Can update task progress (`To Do`, `Doing`, `Done`).

---

## Stacks I intend to use

### Java
#### Spring boot
- For features requiring complex validations and business rules.
- Handles token management, access permissions, invites, and other critical features.

### PHP
#### Laravel
- For features that need agile modifications and rapid database updates.
