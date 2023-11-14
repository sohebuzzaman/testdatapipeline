# Data Pipeline Test Automation Framework

## Overview

This project is a beginner-friendly sample test automation framework designed for testing data pipelines. The primary goal is to provide an introduction to test framework design using Python as the programming language, pytest as the test framework, and incorporating features such as reporting and logging.

## Features

- **Programming Language:** Python
- **Test Framework:** pytest
- **Reporting:** pytest-html for HTML reports
- **Logging:** Integrated logging for detailed execution logs

## Project Structure

```
|-- /foundation
|   |-- /docs
|-- /src
|   |-- /modules
|   |-- main_functionality.py
|   |-- database_connection.py
|-- /utilities
|           |-- chrome_driver
|           |-- pytest.ini
|           |-- requirements.txt
|           |-- setup.py
|-- /config
|       |-- config.ini
|       |-- logconfig.ini
|-- /test_cases
|   |-- test_suite.py
|-- main.py
|-- /execution_logs
|-- /test_reports
|-- README.md
```

## Getting Started

1. **Clone the Repository:**
   ```bash
   clone https://github.com/sohebuzzaman/testdatapipeline.git
   ```
   

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure the Framework:**
   - Adjust configurations in `config.ini` to match your data pipeline and dashboard settings.

4. **Run Test Cases:**
   ```bash
   pytest
   ```

## Test Cases

- `test_data_pipeline.py`: Includes sample test cases for data pipeline validations.
- `test_dashboard_visualization.py`: Includes sample test cases for dashboard visualization checks.

## Additional Features

- **CI/CD Integration:**
  - Easily integrate with popular CI/CD platforms by triggering the `pytest` command as part of your CI/CD pipeline.

- **Extensibility:**
  - Add more test cases and utilities to suit your specific data pipeline requirements.

- **Detailed Reporting:**
  - Utilizes pytest-html to generate detailed HTML reports for test execution.

- **Logging:**
  - Integrated logging to capture detailed execution logs for debugging purposes.

## Contribution Guidelines

Contributions are welcome! If you have ideas for improvement, additional features, or bug fixes, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
