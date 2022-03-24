# JS2
React to_do App

https://codesandbox.io/s/redux-form-synchronous-validation-forked-k0iip

https://codesandbox.io/s/redux-form-synchronous-validation-forked-37ojr

UI Layer – React with Redux
Services Layer – SpringBoot
Data Layer – MetricStream API, Attunity & ERIP
Tech Stack:
JavaScript Library: React v16.9
Bootstrapped with usaa-cli tool
Redux v4: State Management
Design Framework: Material UI v4
Authentication Framework: OpenID Connect
Single Sign On - ForgeRock
Testing:
Unit Test – Jest & Enzyme
Automated Functional Testing – TestNG
Wrapper for Selenium
--
IM Portal is a first line of defense (FLOD) issue management application that enables an intuitive and transparent experience for 
managing and monitoring issues enterprise-wide.
The tool will encompass all of the tasks necessary to track, resolve and report on issues/action plans in a collaborative manner.
1. user login, UI get role and permission info and redirect to dashboard page.
2. dashboard have issue, action plan, task and education tabs. It is a quick high level review of my tasks, my issues, my action plans.
It provide more robust issue management overview and allow the users 
to be informed and aware of actions need for each issue, especially.
This is what the user will see,
-When user logged in they will see their names shows on the upper left corner, and picture icon displays on the upper right
-Pending Tasks (woek on, approve, review issues) will displayed on my Task section and sorted by due date for the first 4, overdue task will always on top
-The "View all" link will direct user to task page to display all pending tasks assigned to that user
-On My issue section, user will see 4 issue card based on its due date, the overdue issue will always list at the beginning, if an issue don't have a due date, it should listed here as well.
-The View all link will direct user to issue page to display all issues assigned to that user
-On My action section, user will see 4 actions listed on its due date, the overdue issue will always list at the beginning, if an action don't have a due date, it should listed here as well.
-The "View all" link will direct user to action page to display all actions assigned to that user
On navigation bar, dashboard icon will direct user to dashboard page, the issue icon will direct user to issue Kanban page, the action plan icon will direct user to action page, the task icon will direct user to task page, the reporting icon will direct user to external reporting dashboard, and the resources icon will direct user to an external wiki page for this product

--
Status and Severity pills are rendered with real data from IM Portal service.
The New/Edit Issue page is rendered, the Header section is initialized with data from the API response.
