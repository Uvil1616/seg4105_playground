Notes

Ghazal's Pitch
- schedule for schoolwork such as assignments, quizes, and exams
- currently can only view created schedules but can't edit or delete
- schedule can only be viewed through code id
- feature is to build landing page to view and edit schedules
- the problem matters because rarely do all deadlines remain static
- professors have to move at least one or two deadlines due to unforseen circumstances
- if schedules can't be edited, they are inaccurate and effectively useless
- must be able to edit schedules
- currently majority of functionality is done, this is the last critical piece of functionality
- also they have been going through a lot of redesigning of backend and would like something else to integrate
- mainly design work as they are concerned with the ability to view the schedule
    - how will user navigate to view and how will they select the schedule
    - easier way to show all schedules made and those that you have subscribed to
- first concern is that delete function is out of scope for this cycle
- delete schedule would not only affect creator but also anyone subscribed to the schedule
    - some sort of deletion cascade on the back-end is too much to consider for this cycle
- second concern is for requiring password before edit
    - overkill for editing since you have to be signed in anyway
    - moved confirmation to delete which will not be addressed this cycle

Alex's Pitch
- built a program to run through circuit diagram
- feature is to allow app to run through alternative flows and allow further mutability
    - basically redesignin the structure so that it can be expanded upon
- current structure is too rigid for current problem
- currently cannot solve problems in parallel, but aims to fix this by making the solver more efficient
- increase data stored in solver so that calls from the container are more efficient and can be done for different shematic diagrams
- currently very annoying to have to remove each circuit before making a new one and not being able to commpare them to each other
- while not necessary this is the only next step of any significane other than a UI change that isn't at all necessary or meaningful

My Pitch
- building backend of bike shop website
- mainly just accounts system to auto fill fields when booking an appointment
- Currently the fields take quite a bit of work which will dissuade the customer from approaching second time
- must streamline the process otherwise will lose interest when confronted with amount of work required every single time
- website is meant to simplify booking process not complicate it
- most of the website is done. this is just about adding functionality and making it easier to use
- this is partly required since the website currently has no back-end
- limit UI changes to adding one more option and an icon to indicate whether the user is signed in
- first concern: scope is too large
    - creating database and communicating between website and server is more complicated than I initially thought
    - that alone will probably take the full 6 weeks so should leave the auto-fill portion from this cycle
- second concern: going to same page with incorrect password
    - need to show some kind of error message otherwise user will not know if it was incorrect input or the website just failed to load