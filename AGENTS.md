# AGENTS.md Guidelines

These guidelines are designed to ensure the quality, maintainability, and efficiency of all AGENTS.md files within this repository. Adherence to these principles is crucial for maintaining a stable and scalable codebase.

**1. DRY (Don't Repeat Yourself)**

*   All functions, classes, and modules should have single, well-defined purposes.
*   Avoid duplicating logic.  If a functionality is needed repeatedly, encapsulate it into a reusable component or function.
*   Implement common patterns and constructs across multiple files.

**2. KISS (Keep It Simple, Stupid)**

*   Prioritize clarity and readability above all else.
*   Write concise and easy-to-understand code.
*   Avoid unnecessary complexity.  Strive for simplicity when feasible.
*   Use appropriate naming conventions.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  The system should be extensible without modification.  New functionality should be added via new classes/modules.
*   **Liskov Substitution Principle:**  Subclasses must be able to replace any underlying class without affecting the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they don't use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules; they should depend on abstractions.

**4. YAGNI (You Aren't Gonna Need It)**

*   Implement features only when they are absolutely necessary.
*   Don't add functionality that isn’t currently required for the core functionality.
*   Refactor existing code to remove unused functionality.

**5. Code Length & Structure**

*   Maximum code length: 180 lines.
*   Code structure:  Follow a consistent file naming convention (e.g., `module.py`, `class.py`).
*   Comments:  Provide concise, informative comments where necessary, but avoid excessive comments.
*   Documentation:  Use docstrings to explain the purpose, parameters, and return values of functions, classes, and modules.
*   Naming: Use descriptive and consistent variable and function names.

**6. Testability**

*   All code must be easily testable.
*   Tests should focus on verifying essential functionality and corner cases.
*   Unit tests should cover individual functions and classes.
*   Test coverage must exceed 80%. (Automated test suite should be implemented).

**7. Dependency Management**

*   All dependencies should be explicitly declared in the `requirements.txt` file.
*   Dependencies should be versioned (e.g., using `pip freeze > requirements.txt`).
*   Dependencies should be managed and updated regularly.

**8.  Production-Ready Code**

*   Error handling should be robust and user-friendly.
*   Code should be designed for maintainability and future expansion.
*   Assume the code will be deployed to a production environment.

**9.  Specific File Structure (Example - Adapt as needed)**

*   **`requirements.txt`**:  Lists all dependencies.
*   **`README.md`**:  Project overview, setup instructions, and basic usage.
*   **`tests/`**:  Contains all unit tests.
*   **`src/`**:  Contains the primary source code.
*   **`models/`**: Contains model definitions.
*   **`config/`**: Contains configuration files.
*   **`data/`**: Contains sample data.

**10.  Production-Level Considerations**

*   Implement proper logging to track events and errors.
*   Include unit tests and integration tests.
*   Consider using a version control system (e.g., Git) to manage code changes.

These guidelines are intended to provide a solid foundation for developing high-quality AGENTS.md files. They are a living document and will be reviewed and updated as needed.