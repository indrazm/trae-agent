# Project Development Rules

## Primary Directive

You are a Development Agent implementing a project with **documentation-driven development** and **single feature focus**.

## Core Workflow

1. **Documentation Review** - Always check `/docs/implementation.md` for current tasks
2. **Single Feature Focus** - Work on ONE feature at a time until complete
3. **Granular Steps** - Break features into 30-60 minute implementable steps
4. **Test Creation** - Always create test files for backend features
5. **Context7 Research** - Use context7 for latest documentation before implementation

## Tech Stack

- **Backend**: ElysiaJS + SQLite + Prisma
- **Frontend**: React 19 + TanStack React Query + React Router v7 + Tailwind CSS + Tailwind Variants
- **Testing**: Required for all backend functionality, optional for frontend

## File Priority

1. **Critical**: `/docs/implementation.md`, `/docs/bug_tracking.md`, `/docs/project_structure.md`
2. **Specification**: `/docs/ui_ux_doc.md`, `/docs/api_documentation.md`, `/docs/testing_requirements.md`
3. **Reference**: `/docs/coding_standards.md`, `/docs/architecture_decisions.md`

## Critical Rules

- **NEVER** work on multiple features simultaneously
- **NEVER** skip test file creation for backend features
- **NEVER** run CLI commands (provide instructions instead)
- **ALWAYS** use context7 for latest documentation
- **ALWAYS** break features into granular steps (30-60 minutes)
- **ALWAYS** complete one step before moving to next
- **ALWAYS** update documentation after changes

## Quality Standards

- Zero syntax errors or warnings
- Complete feature implementation (no partial work)
- Comprehensive backend test coverage
- Documentation updates after each step
- Integration with existing codebase

## Success Criteria

- [ ] Single feature completely implemented
- [ ] All granular steps completed in sequence
- [ ] Test files created for backend functionality
- [ ] Documentation updated appropriately
- [ ] No errors or warnings remain

Remember: **Focus on ONE feature, work in granular steps, create tests, research with context7, maintain quality**. Build systematically and document thoroughly.
