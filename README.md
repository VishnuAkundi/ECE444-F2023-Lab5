# Lab 5
This repo follows the following link: https://github.com/mjhea0/flaskr-tdd

## Tests in group project
Link to test_api.py is [here](https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/blob/feat/event_registration/api/utils/unit_tests/test_api.py)

I worked on the populate_db and test_search functions. I added an extra db entry in populate_db and tested both filters and search queries in test_search.
Link to test_search function [here](https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/blob/7182dc939f2d05aa813027d2212581b32fb2bc0c/api/utils/unit_tests/test_api.py#L76-L87)
Link to populate_db function part [here](https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/blob/7182dc939f2d05aa813027d2212581b32fb2bc0c/api/utils/unit_tests/test_api.py#L40-L49)


## Pro's and Con's of TDD

Pros:

1. Early Bug Detection: TDD helps in identifying and addressing bugs and issues at a very early stage of development, reducing the cost and effort required to fix them later in the development process.

2. Improved Code Quality: TDD encourages developers to write cleaner, more modular, and maintainable code. This leads to better software design and reduces technical debt.

3. Better Documentation: The test suite serves as living documentation for the codebase. It helps developers and other stakeholders understand how the code is expected to behave.

4. Better Collaboration: TDD can improve collaboration among team members. Tests provide a clear specification for what the code should do, helping non-developers understand and contribute to the testing effort.

5. Faster Development: While writing tests upfront may seem like it slows down development initially, it often speeds up development in the long run by preventing costly debugging and rework.


Cons of TDD:

1. Initial Learning Curve: Developers who are new to TDD may experience a learning curve as they adapt to writing tests before writing the code. This can lead to slower initial development.

2. Increased Time and Effort: Writing tests can require additional time and effort, especially in the beginning. This can be seen as a drawback when there are tight project deadlines.

3. Overhead: Maintaining a large test suite can become an overhead if not managed properly. It may require time and resources to keep tests up to date as the codebase evolves.

4. Test Maintenance: As the codebase evolves, tests need to be maintained. Refactoring code or changing requirements may require updating a significant number of tests.

5. Can Encourage "Test-First" Thinking: Some developers may become so focused on passing tests that they lose sight of the bigger picture, such as the overall architecture or user experience.



