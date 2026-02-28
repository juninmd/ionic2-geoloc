```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the creation and maintenance of high-quality, maintainable, and robust AI coding agents.  Adherence to these principles is crucial for a sustainable and effective development process.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent module should have a single, well-defined purpose.  Avoid creating overly complex agents with multiple responsibilities.
*   **Abstraction:**  Abstract complex logic into reusable components.  Design agents to be easily adaptable to new scenarios.
*   **Code Reuse:**  Identify and reuse common patterns and solutions across multiple agents.
*   **Configuration:**  Favor configuration over hardcoded values where possible.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:** Strive for the shortest possible code path to achieve a given functionality.
*   **Readability:** Prioritize code that is easy to understand and maintain.  Use meaningful variable names and comments judiciously.
*   **Avoid Over-Engineering:**  Don’t introduce unnecessary complexity.  Simplify where possible without sacrificing functionality.
*   **Focus:** Each agent should address a single, clearly defined problem.

## 3. SOLID Principles

*   **Single Responsibility Principle:** (already covered in DRY)
*   **Open/Closed Principle:**  Agent modules should be extensible through public APIs.  New functionality can be added without modifying existing code.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:**  High-level modules (agents) should not depend on low-level modules (implementation details).

## 4. YAGNI (You Aren’t Gonna Need It)

*   **Avoid Unnecessary Features:**  Don’t add features or complexity that isn't currently required.  Focus on delivering the essential functionality first.
*   **Refactoring:**  Refactor only when there's a significant reason to improve the code’s structure or design.
*   **Testability:**  Ensure that code is designed to be easily tested and that unnecessary complexity doesn't hinder testing efforts.

## 5. Code Length & Structure

*   **Maximum Code Length:** 180 lines of code per file.
*   **Logical Structure:**  Organize code into logical modules with clear naming conventions.
*   **Comments:**  Provide concise and helpful comments where necessary, focusing on *why* not *what*.

## 6. Testability & Coverage

*   **Unit Tests:** All agents must have a comprehensive suite of unit tests covering all critical functionality.
*   **Test-Driven Development:** Write tests *before* writing code.
*   **Coverage Targets:** Aim for at least 80% code coverage.  Automated code coverage tools are encouraged.
*   **Integration Tests:**  Ensure agents interact correctly with other parts of the system.
*   **End-to-End Tests:**  Design tests that simulate real-world user scenarios.

## 7.  File Structure & Conventions

*   **Root Directory:** `AGENTS.md`
*   **Module Structure:**  Organize agents into logical modules (e.g., `agent_core`, `agent_sensor_data`, `agent_communication`).
*   **Naming Conventions:** Use consistent naming conventions throughout the repository.  (e.g., camelCase for variables and functions)
*   **Dependency Management:**  Use a dependency management system (e.g., pip, Conan, Poetry) to manage external libraries.
*   **Versioning:**  Employ a version control system (e.g., Git) for all files.

## 8.  Documentation & README

*   **README:** A comprehensive README file explaining the purpose of the project, how to run the agents, and any relevant setup instructions.
*   **Design Documents:**  For complex agents, create design documents outlining the architecture, data flows, and algorithms.
*   **API Documentation:**  Document any APIs used by the agents (even if mock implementations are used).



```