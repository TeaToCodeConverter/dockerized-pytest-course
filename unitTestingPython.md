---
tags:
    - Python
    - Unit-Testing
---

# Unit Testing using Python

## Overview of Test-Driven Development and Pytest Features

### Exceptions Challenge

> - Supply a City Name that can only be a string object
> - Throw an error if another data type is provided
> - Begin writing from the test and run pytest to spot the test failure
> - hint :
>> - Try adding Validation logic to the instantiation method
>>> (__init__) of the Point class
>>>> - use the built-in breakpoint() function when needed


### Happy PAth testing

#### positive path testing
- Organize positive cases into their own functions 

- make sure not to mix them with sad path or negative case function

(make 2 different test groups those that are expected to be true positive and those that are expected to be true false do not mix them)

#### sad path testing (negative case tests)

> - negative cases to validate against
> - two methods of handling sad path tests:
>> - halt the flow of code execution and throw and exception
>> - gracefully log an exception that an action could not be taken and continue the code execution; ideally this should be shown to the user

