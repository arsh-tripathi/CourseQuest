# Course Quest

As students, we have recognized the stress and complexity involved in the uncertainty which comes with degree planning. Even as early as first year, the decisions you make in your course selection could echo down through the years to impact your later. What if you want to complete a minor? Which specialization are you interested in? Will you complete your breadth and depth? All of these issues are critical components to our future planning. Nevertheless, the burden of these decisions are a required component of our student lives. But, we can make it easier.

CourseQuest is a tool which helps students plan out their courses throughout every single term. Taking data directly from the Waterloo API, CourseQuest allows you to easily plan your courses while accounting for every complexity in your degree. Furthermore, CourseQuest makes reasonable suggestions as to how your courses will pan out.

**Contributors**: Arsh Tripathi, Brayden Wang, Elen Mullaj, Johnson Chen
**Note**: This project was done for a University course, and so the source code cannot be made available publically, however you may request to view it

## System Requirements

* Windows 11
* A stable internet connection

## Installation Instructions

* First, ensure that your device follows the above specifications
* Download most recent installer from [installer](https://github.com/arsh-tripathi/CourseQuest/blob/master/CourseQuest-1.4.0.msi)
* Launch downloaded installer file
* Proceed as installer instruction state
* Upon completion, navigate to the folder where you had specified to install your progam (By default this is C:\\Program Files)
* Find and run CourseQuest.exe to start the application

## Using CourseQuest

* Upon launching, create a new account by clicking the sign up button. Make sure to remember the email and password you used so that you can access your plans at a later date. If you already have an account, you can use your email and password to sign in
* After logging in, the applications directs you to the plan selection page. In this page, on the left you can select any plan which you created in a previous session. Otherwise, you can create a new plan by inputting the details on the right. While the name can contain any string and the start date any month and year, the options for inputting the co-op sequence are more limiting. With a value of 0, the plan will be created without co-op. With a value of 1, 2, 3, or 4, the corresponding co-op sequence will be automatically added. Alternatively, you can use a custom co-op sequence by entering some sequence of the letters \[S - Study, W - Work, O - Off\] while separated by commas. At any point, the terms in a plan can be added, removed, or altered.
* Within a given plan, you will be presented with 3 main pages which can be navigated between using the top bar: schedule, requirements, and agenda
  * Schedule Page
    * Here you may add to any past, present, or future terms in order to properly plan out your degree
    * To add a course, click the add course button and search for your desired course using its course code (ex: MATH 135, CS 136L, etc.)
    * If the course you searched for is found, you will be shown a brief description of the course and be allowed to add the course to your bucket
    * Upon adding a course, you may move the course by clicking and dragging it to the corresponding term, or by right-clicking and selecting move. In the aforementioned right-click menu, you may also remove the course
    * When a course is added to a term, the coloured bubble next to the course number indicates if the requirements for said course are met. Note that any overridden courses or courses with outdated requirements in the waterloo calendar will be marked as invalid
    * Here you can also add or remove terms within the sequence of terms by clicking the plus or trash can buttons on the side of each term. If adding a term, the corresponding term will be added after the selected term with the term code and term type automatically updated
  * Requirements Page
    * Here you will presented with a more detailed view of your shedule with emphasis on the requirements of the CS degree
    * Based on the CS degree, the page will show which requirements you have met, planned, or have yet to include which will be automatically updated
    * Using the button under term and course, you can add and move courses to a term as needed
  * Agenda
    * Here you can view what your schedule would seem like in a given term
    * By changing the term selected, CourseQuest will show you a potential view of how your schedule would look based on the current term's class scheduling
