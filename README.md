# AutomationTraining
This framework is designed in order to perform tests for github using UI and API approaches.

> **_NOTE:_** 
> 1. Remember of good practices.
> 2. Use the same coding standards to create a code.

## Project Goals

1. **What I'm Creating?**
   - Automation test framework.
   - Test Framework to test GitHub API/UI and other applications.

2. **Why I'm Creating This?**
   - To learn good practices about test framework.
   - To learn how to create automation test framework.
   - To gain more experience about testing.

3. **How I'm Creating This?**
   - Step by step.
   - Ensuring that i understand each step.
   - Creating and expanding the structure of the framework.
   - Using python and selenium.


## Framework structure
### Config module
- What For:
  - Storing frameworks and env configuration.
- How To:
  1. Create config file under src/applications/config.
  2. Add env variables/classes/dependency injection that may be needed.


### Applications module
- What For:
  - Prepare configuration/hooks for applications testing.
- How To:
  1. Create a directory using the <name of application> under src/applications directory.
  2. Create a directory using the <type of test> (like ui, api) under src/applications/<name of application> directory.
  3. Create helpers directory under src/applications.
  4. Create functionalities, variables to perform tests under the src/applications/<name of application>/<type> directory.
  5. Create functionalities, variables under src/applications/helpers that will aid testing process.
  6. Set API calls used for tests inside applications/github/api/github_api.py.
  7. Set UI models/hooks used for tests inside applications/github/ui/github_ui.py.


### Tests module
- What For:
  - Testing applications
- How To:
  1. Create a directory using the <name of application> under tests directory.
  2. Create a directory using the <type of test> (like ui, api) under tests/<name of application> directory.
  3. Create classes and functionalities to perform tests under the tests/<name of application>/<type of test> directory.
  4. Set tests to perform API testing inside tests/github/api/test_api.py.
  5. Set tests to perform UI testing under tests/github/ui/test_ui.py.




