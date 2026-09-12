# Copilot Instructions

This repository is used for GitHub Copilot training demonstrations.

Project type:
- React application
- TypeScript
- Vite

Coding standards:
- Use functional components only.
- Use TypeScript interfaces instead of types when possible.
- Use async/await instead of promises with .then().
- Add comments only when business logic is not obvious.
- Prefer reusable components.

Folder conventions:
- Pages go in /src/pages
- Reusable UI components go in /src/components
- API calls go in /src/services
- Data models go in /src/types

Naming conventions:
- Components: PascalCase
- Functions: camelCase
- Interfaces: Prefix with I

When generating code:
- Include error handling.
- Follow accessibility best practices.
- Keep components under 100 lines when possible.

Business scenario:
This application manages customer support tickets.

Ticket fields:
- id
- title
- description
- priority
- status
- createdDate

Valid priorities:
- Low
- Medium
- High

Valid statuses:
- Open
- In Progress
- Closed
