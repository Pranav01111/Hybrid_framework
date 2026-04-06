# Hybrid Automation Framework

## Overview
The Hybrid Automation Framework combines the strengths of both data-driven and keyword-driven frameworks, allowing testers to create robust and maintainable automation scripts.

## Features
- **Reusability**: Code components can easily be reused across different tests.
- **Separation of Concerns**: Business logic, test data, and test execution logic are separated for better maintainability.
- **Supports Multiple Platforms**: Tests can be executed across different platforms such as web, mobile, and API.
- **Custom Keywords**: Users can create their own keywords tailored to specific test requirements.
- **Integration**: Can be integrated with CI/CD pipelines for continuous testing.

## Project Structure
- **src/**: Contains the main source code for the framework.
  - **drivers/**: Includes WebDriver configurations for various browsers.
  - **utils/**: Utility functions for different operations (e.g., logging, handling configurations).
  - **test/**: Contains the actual test scripts.
  - **data/**: Holds the test data files (e.g., Excel, JSON).
- **lib/**: Libraries for handling specific functionalities (e.g., API calls, database connections).
- **reports/**: Generated reports after test execution.
- **config/**: Configuration files (e.g., environment settings, credentials).

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Pranav01111/Hybrid_framework.git
   cd Hybrid_framework
   ```
2. **Install Dependencies**:
   Make sure you have Python and pip installed. Then run:
   ```bash
   pip install -r requirements.txt
   ```
3. **Configure Environment**:
   Update the configuration files in the `config/` folder with your specific environment settings.
4. **Run Tests**:
   Execute the tests using the command:
   ```bash
   pytest -q --tb=short
   ```

## Conclusion
The Hybrid Automation Framework provides a flexible and scalable approach to test automation, enhancing productivity and efficiency.