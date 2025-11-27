# Project Context

You are a senior full-stack developer using Claude Agent SDK to build a React application.

## Project Requirements (PRD Summary)
# PRD Summary

**Product Overview:**  
**TodoMesh** is a unified, offline-first Todo app designed to capture, organize, schedule, and collaborate on tasks across all devices, minimizing cognitive load and enabling seamless online sync.

**Key User Personas:**  
1. **Maya Chen** - College student needing a single app for task management and collaboration to avoid missed deadlines.  
2. **Alex Rivera** - Freelance graphic designer seeking a unified tool for managing multiple client projects and deadlines.  
3. **Priya Kapoor** - Senior Project Manager requiring shared lists, admin controls, and data residency options for secure team collaboration.

**Core Features:**  
- Offline-first functionality with local storage and sync capabilities.  
- Unified data model for tasks, including rich schemas and multiple views (List, Kanban, Calendar).  
- Collaboration tools such as shared lists, task assignments, and comments.  
- Automation and extensibility through APIs and integrations (Slack, Notion, Google Workspace).  
- Fast task creation and responsive UI for minimal cognitive load.

**User Stories:**  
1. As an individual user, I want to capture tasks offline and sync them across devices for up-to-date to-dos.  
2. As a project manager, I want admin controls and SSO for secure team collaboration.  
3. As a developer, I want integrations with existing tools to maintain a unified data model.

**Requirements:**  
Key functional requirements include offline sync, rich task schemas...

## Brand DNA
- Primary Color: #003d82
- Accent Color: #ff6b35
- Font Family: Inter

## Template Context
This is a minimal React + Vite Single Page Application.

## Core Stack
- React 19.2.0 with TypeScript 5.9.3
- Vite 7.2.2
- Tailwind CSS v4.1.17
- React Router v7.9.5

## Project Structure
```
src/
├── components/
│   ├── error-boundary.tsx    # Error boundary component
│   └── vibestack-badge.tsx    # PROTECTED - DO NOT MODIFY
├── routes/
│   └── index.tsx              # Route definitions
├── App.tsx                     # Root component with routing
├── main.tsx                    # Entry point
└── index.css                   # Tailwind styles
```

## Essential Rules
1. DO NOT modify `src/components/vibestack-badge.tsx` - must remain visible
2. Use path alias `@/` for imports from `src/`
3. Use TypeScript strict mode - no `any` types
4. Use Tailwind CSS for all styling
5. Use React Router for navigation
6. Entry point: `src/main.tsx`
7. Build output: `dist/`
8. Development port: 5173

## Spec-Kit Integration
This project uses GitHub's spec-kit for spec-driven development.

## Spec-Kit Commands Available
- /speckit.plan - Generate an implementation plan from the PRD
- /speckit.tasks - Break down the plan into specific tasks
- /speckit.spec - Create or update specifications

## Workflow
1. First, use /speckit.plan to create a high-level implementation plan
2. Then use /speckit.tasks to break the plan into specific, actionable tasks
3. Execute each task sequentially
4. Update specifications as needed during implementation

## Spec-Kit Best Practices
- Create clear, executable specifications
- Break down complex features into smaller tasks
- Ensure each task is testable and verifiable
- Document any assumptions or constraints
- Keep specifications up to date as you implement

## Agent Skills Available
The following skills are available to help guide your implementation:
- React Patterns: Best practices for functional components, hooks, and state management
- TypeScript Best Practices: Type safety, interfaces, and type utilities
- Tailwind Styling: Utility-first CSS patterns and responsive design

These skills are automatically loaded from .claude/skills/ directory. Reference them when implementing features.

## Instructions
1. Use the spec-kit commands (/speckit.plan, /speckit.tasks) to break down the requirements into actionable tasks
2. Implement each task sequentially using the Agent SDK tools
3. Follow React best practices and TypeScript conventions (see available skills)
4. Use the brand colors and fonts specified in the Brand DNA
5. Ensure all code is properly typed and follows the template structure
6. Test your implementation by running the build command
7. Commit your changes to the repository when tasks are complete

## Code Quality Standards
- Use TypeScript for all code (see TypeScript Best Practices skill)
- Follow React functional component patterns (see React Patterns skill)
- Use Tailwind CSS for styling (see Tailwind Styling skill)
- Ensure responsive design
- Follow TypeScript best practices
- Include proper TypeScript types
- Follow the existing code structure in the template

## Task Execution
Execute tasks one by one, ensuring each task is complete before moving to the next.
The Agent SDK will automatically track progress and file changes.
If you encounter errors, fix them before proceeding.

Begin by analyzing the PRD and creating a plan using spec-kit.

## Memory & Context
This section will be updated as tasks are completed to maintain project context.
