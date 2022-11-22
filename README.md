# ECE444-F2022-Lab6

Test Case found here: [Link to test case](https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-2-pitcrew/blob/9504a43b7b6ae713bdeaa47707352b8f217a16e9/Education_Pathways/tests/test_app.py#L56)

### Pros and Cons of TDD
Test driven development is a method of software development where test cases are first written, and determines how the functional code is developed.

#### Pros of TDD
By proritizing passing the test cases, only functional code that is needed is written. Unneccessary code is not present, and if a new feature is needed than a test case would be written for it first. In TDD, only one microfeature is being developed at a time. This naturally leads to more modular design. Being more modular also makes it easier to maintain and reduses technical debt. Since every feature is tested, it makes it easier to refactor the code base as well, as long as all the tests still pass. Personally the best part is reducing the amount of debugging necessary, as the scope of the codebase where the bug exists becomes extremely narrow as the code where the test cases fail is prioritized.
#### Cons of TDD
Tests do not cover bugs in the entire codebase, and cannot detect bugs in the test cases itself or the implementation code. TDD also may seem be a slow process, as test cases have to be developed before anything functional gets developed. Tests also have to be maintained when the requirements change, which would be a hassle when requirements change often. 
