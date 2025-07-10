# AI Agent System for Development

A comprehensive AI agent system designed for **documentation-driven development** with **single feature focus** and **systematic execution**. This system provides specialized agents that work independently while maintaining consistency through shared documentation standards.

## 🤖 Agent Overview

### Product Agent
Specializes in product management and requirements definition:
- **PRD Creation**: Craft comprehensive, actionable product requirements
- **Feature Analysis**: Evaluate and prioritize features based on impact and feasibility
- **Strategic Planning**: Assist in roadmap planning and market positioning
- **Tech Stack Alignment**: Ensure requirements align with ElysiaJS, React 19, SQLite, Prisma
- **Backend Testing**: Always specify comprehensive test coverage for backend features

### UI/UX Agent
Focuses on interface design with **simplicity first** and **pattern consistency**:
- **Interface Design**: Create clean, intuitive, and accessible user interfaces
- **Pattern Application**: Follow established design patterns and platform conventions
- **Design System**: Maintain consistent components and interactions
- **Accessibility**: Ensure WCAG compliance and inclusive design
- **Responsive Design**: Optimize for all screen sizes and devices

### Engineer Agent
Implements documentation into functional code with **single feature focus**:
- **Single Feature Development**: Work on ONE feature at a time until complete
- **Granular Steps**: Break features into 30-60 minute implementable chunks
- **Test-First Approach**: Always create test files for backend functionality
- **Context7 Integration**: Use latest documentation for all tools and frameworks
- **Quality Assurance**: Ensure code meets documented standards

## 🏗️ Tech Stack

### Backend
- **ElysiaJS**: Fast and type-safe web framework for Bun
- **SQLite**: Lightweight, serverless database
- **Prisma**: Type-safe database ORM and query builder

### Frontend
- **React 19**: Latest React with new features and improvements
- **TanStack React Query**: Powerful data fetching and state management
- **React Router v7**: Client-side routing and navigation
- **Tailwind CSS**: Utility-first CSS framework
- **Tailwind Variants**: Component variants and styling system

### Testing
- **Backend**: Comprehensive test coverage required for all functionality
- **Frontend**: Optional testing for complex components

## 📋 Project Rules

### Core Principles
- **Documentation-Driven**: All decisions based on shared documentation
- **Single Feature Focus**: Work on ONE feature at a time until complete
- **Granular Development**: Break features into 30-60 minute steps
- **Test Creation**: Always create test files for backend features
- **Context7 Research**: Use latest documentation before implementation

### Critical Rules
- **NEVER** work on multiple features simultaneously
- **NEVER** skip test file creation for backend features
- **NEVER** run CLI commands (provide instructions instead)
- **ALWAYS** use context7 for latest documentation
- **ALWAYS** break features into granular steps
- **ALWAYS** complete one step before moving to next

### Documentation Priority
1. **Critical**: `/docs/implementation.md`, `/docs/bug_tracking.md`, `/docs/project_structure.md`
2. **Specification**: `/docs/ui_ux_doc.md`, `/docs/api_documentation.md`, `/docs/testing_requirements.md`
3. **Reference**: `/docs/coding_standards.md`, `/docs/architecture_decisions.md`

## 🎯 Philosophy & Approach

### Documentation as Single Source of Truth
Our system prioritizes **documentation consistency** over dynamic inter-agent communication. All agents synchronize through well-defined documentation structures, ensuring:
- **Consistency**: All agents work from the same information base
- **Traceability**: Every decision can be traced back to documented requirements
- **Maintainability**: Changes managed through documentation updates
- **Predictability**: Deterministic and reproducible agent behavior

### Systematic Workflow Over Ad-Hoc Decisions
Each agent follows **structured workflow protocols** that eliminate ambiguity:
- **Pre-Task Protocol**: Mandatory documentation review before any action
- **Task Execution Protocol**: Step-by-step procedures for completing work
- **Post-Task Protocol**: Documentation updates and quality verification

### Simplicity and Pattern Consistency
The system emphasizes **familiar patterns over novel solutions**:
- **Proven Patterns**: Prefer established solutions over innovative approaches
- **Cognitive Load Reduction**: Minimize mental effort required for understanding
- **Consistency Over Creativity**: Maintain predictable behaviors and outputs

### Single Feature Development
Focus on **one feature at a time** with **granular execution**:
- **Complete Implementation**: Finish current feature entirely before starting next
- **30-60 Minute Steps**: Break features into manageable, testable chunks
- **Test-Driven**: Create comprehensive test coverage for backend functionality
- **Quality Gates**: Validate each step before proceeding to next

## 🔧 Key Advantages

### Predictable Outcomes
- Deterministic behavior through explicit rules and documentation requirements
- Consistent output quality across different contexts
- Clear traceability when issues arise

### Reduced Complexity
- Eliminates unpredictable inter-agent interactions
- Standardizes interfaces and interaction patterns
- Centralizes knowledge in documentation

### Enhanced Maintainability
- Clear documentation with all decisions explicitly recorded
- Standardized processes across all agents
- Modular design allows independent agent updates

### Scalability
- Documentation structures grow systematically
- Established patterns apply to new domains
- Standards propagate to new agents effectively

## 🚀 Getting Started

1. **Setup Documentation**: Create the required `/docs/` structure
2. **Configure Agents**: Set up each agent with their respective system prompts
3. **Define Project Rules**: Establish project-specific development standards
4. **Start Development**: Begin with single feature development using granular steps

## 📝 Documentation Structure

```
/docs/
├── implementation.md          # Current tasks and progress
├── bug_tracking.md           # Known issues and solutions
├── project_structure.md      # File organization rules
├── ui_ux_doc.md             # Design patterns and components
├── api_documentation.md      # API specifications
├── testing_requirements.md   # Testing standards
├── coding_standards.md       # Code style and conventions
└── architecture_decisions.md # Technical architecture rationale
```

## 🎨 Design Philosophy

This system represents a **paradigm shift** from dynamic, emergent AI behaviors to **systematic, predictable outcomes**. By prioritizing documentation consistency, explicit behavioral rules, and structured workflows, we create more maintainable, scalable, and reliable AI systems.

The approach's emphasis on **simplicity over complexity**, **consistency over creativity**, and **documentation over communication** provides a solid foundation for building AI agent systems that serve human needs effectively while maintaining predictable, high-quality outcomes.

---

*Built with the philosophy of **documentation-driven development** and **systematic execution** for reliable, maintainable AI agent systems.*
