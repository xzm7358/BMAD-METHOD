# Requirements Document

## Introduction

This document outlines the requirements for analyzing and documenting the BMad-Method project - a Universal AI Agent Framework for Agentic Agile Driven Development. The BMad-Method is a comprehensive natural language framework that transforms software development through specialized AI agents working in structured workflows. The system provides both planning capabilities (through web UI agents) and development execution (through IDE-integrated agents) to deliver complete project lifecycle management from ideation to implementation.

## Requirements

### Requirement 1

**User Story:** As a developer or project manager, I want to understand the BMad-Method's core architecture and components, so that I can effectively utilize the framework for AI-assisted development projects.

#### Acceptance Criteria

1. WHEN analyzing the project structure THEN the system SHALL identify all core components including agents, templates, tasks, workflows, and data files
2. WHEN examining the bmad-core directory THEN the system SHALL document the purpose and structure of each subdirectory (agents, agent-teams, workflows, templates, tasks, checklists, data)
3. WHEN reviewing the tools directory THEN the system SHALL explain the build and delivery process including web bundling capabilities
4. WHEN analyzing the expansion-packs directory THEN the system SHALL document the extensibility model for domain-specific functionality

### Requirement 2

**User Story:** As a technical stakeholder, I want comprehensive documentation of the BMad-Method's workflow processes, so that I can understand how planning and development phases integrate together.

#### Acceptance Criteria

1. WHEN documenting the planning workflow THEN the system SHALL describe the complete process from project ideation through PRD and architecture creation
2. WHEN analyzing the development cycle THEN the system SHALL document the SM/Dev/QA agent collaboration pattern and story-based implementation approach
3. WHEN examining workflow transitions THEN the system SHALL explain the critical handoff points between web UI planning and IDE development phases
4. WHEN reviewing agent interactions THEN the system SHALL document how agents pass context through story files and maintain project continuity

### Requirement 3

**User Story:** As a developer implementing BMad-Method features, I want detailed technical specifications for the agent system and template processing, so that I can contribute to or extend the framework effectively.

#### Acceptance Criteria

1. WHEN analyzing the agent dependency system THEN the system SHALL document how agents declare and resolve dependencies on templates, tasks, and data files
2. WHEN examining the template processing system THEN the system SHALL explain the markup language, variable substitution, and AI directive processing
3. WHEN reviewing the build system THEN the system SHALL document how web-builder.js creates distributable bundles for different environments
4. WHEN analyzing configuration management THEN the system SHALL document the core-config.yaml system and technical preferences integration

### Requirement 4

**User Story:** As a user adopting BMad-Method, I want clear documentation of installation, setup, and usage patterns, so that I can quickly get started with the framework in my development environment.

#### Acceptance Criteria

1. WHEN documenting installation procedures THEN the system SHALL provide step-by-step instructions for both web UI and IDE setup
2. WHEN explaining usage patterns THEN the system SHALL document how to interact with different agent types and their specific capabilities
3. WHEN covering project lifecycle THEN the system SHALL explain the complete flow from initial project idea through final implementation
4. WHEN addressing different project types THEN the system SHALL document both greenfield and brownfield project approaches

### Requirement 5

**User Story:** As a contributor or maintainer, I want comprehensive documentation of the framework's guiding principles and architectural decisions, so that I can make consistent contributions that align with the project's vision.

#### Acceptance Criteria

1. WHEN documenting design principles THEN the system SHALL explain the "natural language first" approach and lean dev agent philosophy
2. WHEN analyzing extensibility patterns THEN the system SHALL document when to add to core vs. creating expansion packs
3. WHEN reviewing code organization THEN the system SHALL document the separation between planning agents (web UI) and development agents (IDE)
4. WHEN examining quality standards THEN the system SHALL document the template format specifications and agent design rules