---
layout: post
title: Code Quality
tags:
  - coding
id: 37
date: 2021-09-08 18:34:55 +0800
---

# Code Quality 

## Coding style
- Be consistent in the style
- Coding standard
  - [Google Style Guides](https://google.github.io/styleguide)
  - [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
- Static code analysis
  - Pylint is integrated into Visual Code
  - Find guidance [here](https://code.visualstudio.com/docs/python/linting).

## Testing
- Unit test and system test
  - Unit test is efficient
  - System test is thorough
- Test tools
  - Unit test for Python
    - https://docs.python.org/3/library/unittest.html
    - https://docs.python.org/3/library/unittest.mock.htmlP
			
## Pull Request (PR)
You can find detail guidance (https://google.github.io/eng-practices/). We summarize three items in the following.
- Submit a complete PR (Tested code with tests)
- Clear description (“Fix bug” is an inadequate CL description. What bug? What did you do to fix it? )
- One PR one task
- Examples:
  - [Good CL Descriptions](https://google.github.io/eng-practices/review/developer/cl-descriptions.html#:~:text=enough%20useful%20information.-,Good%20CL%20Descriptions,-Here%20are%20some)
