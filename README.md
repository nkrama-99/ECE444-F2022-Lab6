# ECE444-F2022-Lab6

Name: Ramakrishna Natarajan

### What are the pros and cons of TDD?

TDD stands for Test Driven Development. It is a software development framework in which test cases are first developed to specify and validate what the code will do, before even the coding work is done. Code refactoring is then performed to ensure the test created initially are passing.

One of the pros of TDD is more modular code is written. TDD requires us to write small tests at a time because development is done after unit testing, so it forces us to write smaller and more modular code. Testing could become complicated and difficult if code written is not modular. In addition, since TDD requires us to write tests prior to development, it by default means the code base has high test coverage which directly means better reliability and it also gains more confidence in the code base. Besides, with TDD, refactoring of code becomes much easier and less complicated. Typically, code refactoring is not an easy task because there is a high risk that after refactoring the existing functionality may break. However, since TDD forces us to write tests at the very beginning, high test coverage of the code would help to minimize functionality break after refactoring.

On the other hand, one of the cons of TDD is that the process is slow. This is mainly because of the way TDD works since it requires us to write plenty of tests first before actual development work is done. So, it feels like the whole process takes much longer time. In other development frameworks, we get right to the development of features, and it feels like more work is done in a shorter time. Besides, it is also difficult to adopt TDD into existing/legacy code base. There is a high chance that the existing coded base has poor test coverage, meaning to incorporate TDD, a lot of test cases need to be written first to cover existing code. In addition, tests will need to be managed properly as requirements change. In TDD, initial tests are written based on the requirements, as requirements change the tests will need to be updated first to accommodate the new changes. Furthermore, TDD framework will only work properly if everyone in the team follows it properly. The moment some developers stop writing/maintaining tests, the quality of TDD starts degrading very quickly. 

### URL to Unit Tests
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-20-twenty/blob/main/Education_Pathways/tests/test_app.py#L23-L75
