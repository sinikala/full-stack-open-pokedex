Exercise 11.1

Python

Python has several tools for linting such as Pylint and PyFlakes. Pylint is a grandpa of a linter and throuhg long development most major bugs have been fixed and central features well-developed. It is also known for being rather verbose, so we'll pick Pylint for our scenario.

For testing Python's standard library has the 'unittest' test runner. But for better testing we'll pick 'pytest' which can supports unittest's test cases but also allows writing test cases as series of functions. Building and packacing can be done with setuptools.

Alternatives for Jenkins and GitHub Actions include CircleCI, Buddy, Teamcity and BiG EVAL among others.

To decide the CI set up I would fist need to know at least the scale of the application; Is it of moderate or grat size. I would also need to know more of the nature of the application: Is it relatively simple? Does it have complex requirements or configuration needs.

If the application was a relatively simple, small to medium size application, i would chooce cloud-based environment for its easy of use and configuration. Cloud-based environments have many "ready-made"/easy to implement actions that would surve basic usage well.