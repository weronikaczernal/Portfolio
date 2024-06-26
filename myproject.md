# My project - Filmweb testing project
# Introduction
This project is part of my portfolio, created to showcase my skills and demonstrate examples of my work. As an aspiring manual tester, I have taken the initiative to document test cases and bug reports for a real-world application, Filmweb. This project illustrates my ability to translate theoretical knowledge into practical application, even in the absence of detailed specifications.
# Project Overview
For this project, I selected the Filmweb website and focused on two functionalities:
1. Adding a film to "Chcę zobaczyć" ("Want to watch") list.
2. Using the search functionality to find movies, TV series, actors, etc.
# Approach 
Given the absence of a formal specification, I explored the Filmweb site to understand how these functionalities work. My assumption was that the site's developers followed certain requirements and specifications. Based on my observations, I made my own assumptions about the expected behavior and developed test cases.
# Demonstrated Skills
* Exploratory Testing: Ability to explore and understand application functionalities without formal documentation.
* Test Case Design: Creating detailed and effective test cases based on user interactions and functional behavior.
* Bug Reporting: Anticipating potential issues and documenting them through bug reports.
# Test Cases 
Here are examples of the test cases I created for the functionalities I tested. Each test case is accompanied by two screenshots: the first screenshot shows the test case details, and the second screenshot presents the test script with execution steps. The test cases for the first functionality were documented in Jira using Zephyr, while the test cases for the second functionality were written in TestRail to practice using these tools.
# Functionality 1: Adding a film to "Chcę zobaczyć" list.
**Valid test cases**:
* Test case 1 - Adding a film to "Chcę zobaczyć" list

![1](https://github.com/weronikaczernal/portfolio/assets/170974453/6735e15a-8ea7-4327-a324-f1c9da610664)
![2](https://github.com/weronikaczernal/portfolio/assets/170974453/6e88990c-b49d-4223-888d-526b9881a281)

* Test case 2 - Adding a film to "Chcę zobaczyć" list with priority

![3](https://github.com/weronikaczernal/portfolio/assets/170974453/499fdd59-76c8-4f36-80a5-aff0f152a987)
![4](https://github.com/weronikaczernal/portfolio/assets/170974453/6dc96dee-5f33-497d-9710-a33d52ad78e3)

* Test case 3 - Changing priority for an already added film from the "Chcę zobaczyć" list

![5](https://github.com/weronikaczernal/portfolio/assets/170974453/dce4af19-15cb-40f2-b4d4-dd5591f463fd)
![6](https://github.com/weronikaczernal/portfolio/assets/170974453/29d40ec9-e169-4af8-990a-b945b8c14c65)

* Test case 4 - Changing priority for an already added film from the film's page

![7](https://github.com/weronikaczernal/portfolio/assets/170974453/aea3ccb2-4bc1-4405-9d44-f1a71fd85b87)
![8](https://github.com/weronikaczernal/portfolio/assets/170974453/c2e46d47-ad9c-4fa0-bd81-46b8cbffb61e)

* Test case 5 - Removal and re-addition of film to "Chcę zobaczyć" List

![9](https://github.com/weronikaczernal/portfolio/assets/170974453/52bc29b2-5d7f-4751-86b5-e1660119a834)
![10](https://github.com/weronikaczernal/portfolio/assets/170974453/704b98fc-e21c-49b5-89cc-292b56a90fec)

**Invalid test case**:
* Test case 6 - Adding a film to "Chcę zobaczyć" list when not logged in

![11](https://github.com/weronikaczernal/portfolio/assets/170974453/75015ef3-996c-47b4-b098-f30a4dd66708)
![12](https://github.com/weronikaczernal/portfolio/assets/170974453/49294f05-fe98-49bf-bb63-01fd5c4dd8e6)

# Functionality 2: Search Bar 
**Valid test cases**: 
* Test case 1 - Verify that a user can successfully search for a film by entering the exact title.

![1](https://github.com/weronikaczernal/portfolio/assets/170974453/9120affa-82c2-448c-8ab1-5030e45dda03)

* Test case 2 - Verify that a user can successfully search for a film by entering a partial title.

![2](https://github.com/weronikaczernal/portfolio/assets/170974453/0b896c6d-c7e2-452b-9db8-bccf2da472ba)

* Test case 3 - Verify that the user can successfully search for an actor's profile by entering the actor's name.

![3](https://github.com/weronikaczernal/portfolio/assets/170974453/0f61dd70-59ec-408e-a273-ea454767f53e)

**Invalid test cases**:
* Test case 4 - Verify that the system provides appropriate feedback when the user search with an empty input.

![4](https://github.com/weronikaczernal/portfolio/assets/170974453/587bc598-78cc-4674-9a63-856b49a1982b)

* Test case 5 - Verify that searching with only special characters shows appropriate feedback.

![5](https://github.com/weronikaczernal/portfolio/assets/170974453/dbd9c518-86a8-4597-b93d-2847f18c0ffc)

* Test case 6 - Verify that the system provides appropriate feedback when the user search non-existent film title.

![6](https://github.com/weronikaczernal/portfolio/assets/170974453/8f5227c6-24ff-46dc-a21f-e555477e6f57)

# Bug Reports
Here are examples of the bug reports I created for the functionalities I tested.  These bugs are hypothetical and do not actually occur on the Filmweb site. I created these hypothetical bugs to practice identifying and reporting potential issues based on my test cases.

Bug 1 - Incorrect search results for partial film title

![1](https://github.com/weronikaczernal/portfolio/assets/170974453/0b455b74-7898-4bae-8f6f-a871765f967b)

Bug 2 - Unable to find film by exact title

![2](https://github.com/weronikaczernal/portfolio/assets/170974453/a84c4e14-430a-47e0-956c-6fe3ec17ddcc)

Bug 3 - Hover functionality on "Chcę obejrzeć" button not working

![3](https://github.com/weronikaczernal/portfolio/assets/170974453/e23018d6-97f0-4e6a-999a-419844920497)

Bug 4 - Unable to add film to "Chcę zobaczyć" list

![4](https://github.com/weronikaczernal/portfolio/assets/170974453/116639a6-c333-49f8-8c28-b13a132a8354)

# Conclusions
In this project, I demonstrated my ability to create detailed test cases and bug reports for web functionalities. It provided me with the opportunity to practice using Jira with Zephyr and TestRail for test case management, even in situations without a formal specification.

Key Takeaways:
* Practical Experience: Gained hands-on experience in documenting test cases and reporting bugs using industry-standard tools.
* Problem-Solving Skills: Developed the ability to hypothesize potential issues and document them effectively as bug reports.
* Attention to Detail: Enhanced my ability to meticulously document each step in the testing process to ensure clarity and reproducibility.
* Tool Proficiency: Improved my skills in using Jira with Zephyr and TestRail, which are essential tools in the field of manual testing.
* Adaptability: Demonstrated flexibility and problem-solving by creating test cases and bug reports without a formal specification, simulating real-world testing scenarios.











