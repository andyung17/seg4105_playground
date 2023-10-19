Meeting Date: 2023-10-12

- Rescheduling deadlines
    - Selenium Testing comes next
    - Then comes deployment
- Presentation practice
    - Cutting down on content to fit the desired time
- SEG4105: Acting upon pitch and betting for feature development
    - **Pitch presentation**
        - Avaneesh - Login
        - Adhish - Calendar
        - Luka - Social
        - Khai - Sessions
        - Andy - Workout Generation
    - **Pitch discussion**
        - Avaneesh
            - Does it fully require the whole 6-week cycle
            - Rabbit holes of encryption need to be a priority in storing personal authentication information
            - Process of recovering lost credentials
            - No forms of 2FA or other sign-in methods
        - Adhish
            - Incorporating two features in one really feasible in this cycle
                - Dependent on sessions
            - This could be done during the one-year review period
        - Luka
            - Could be challenging to incorporate since this would need to use some sort of alias to differentiate users from just name or email
                - Should not search by email since this is not protect privacy
            - Searching should be accessible from the main view of the application
            - Public only content from other users besides the current
            - Playlist saving as reference or value?
            - Collaboration on any of the playlists?
        - Andy
            - Workout generation to solve many issues
            - Where would this be accessible
            - How could variants of this be incorporated?
            - How would you handle closed-form questions (answers)
            - Kinds of metrics are used for determining exercises.
        - Khai
            - Fully dependent on the other aspects of exercise creation to be working for it to start development
            - Revamping the current schemas to support feature
                - Taking some more needed effort
            - How to handle any misclicks on proceeding events
            - Does it take away from the actual workout when staring at screen?
    - **Pitch deliberation**
        - Choose Workout Generation as it suited the 4 important questions needed to be asked to determine the feature
            1. Is it a valid problem that needs to be solved?
                1. Valid, as the main proposition of the application is to allow users to create and share workouts. Workout generation adds another layer for any kind of user to do such action(s)
            2. Does it require a full 6-weeks of allocated time to complete?
                1. This task will take the full 6-weeks and allow both teams of developers (front-end & back-end) to work together on the feature
                    1. Front-end: Working on the UI, interactions between pages
                    2. Back-end: Working on the algorithm and endpoints to expose the feature
            3. Can the entire team work together to complete the feature?
                1. The team can work together as it shares different components in order it to be fully functioning
            4. Does it align with the core aspects of the application?
                1. It aligns with both the creation and sharing aspects of what makes FitShare special 
    - **Feedback integration**
        - **What will happen when users provide the same parameters or want more variation? If a user goes through routines or workouts and uses the same parameters will there be variation? (Luka)**
            - For more variations, there should be some sort of option to select certain workouts and ask/receive similar workouts with some variations it that follow similar criteria. If a user were to answer the survey with the same parameter, it would indeed generate the same routine and workouts as it still is receiving the same criterion and does not generate based on randomness. Instead, some sort of option should allow for filtering or searching for similar workouts based on similar parameters.
        - **How does this feature align with our overall value proposition for FitShare? (Khai)**
            - FitShare main goal is to allow kind of user to start working out and sharing their own workouts. This feature would simplify the process of creating a workout from a set of exercises by allowing any kind of individual to answer a few simple questions and get a workout tailored to their preferences immediately. This follows one of the main value propositions for FitShare of having a feature that supports another means of creating workouts for users using the application.
        - **Adding Difficulty in the survey ex (beginner, experienced, pro)? (Avaneesh)**
            - The survey should have some questions relating to the level of experience questions reflected by the user. Once submitted, the survey should return a list and set of recommendations that reflect the previous choices made with clear indications of the level of difficulty.
        - **Where do you think this feature or survey gets shown to the user? (Adhish)**
            - The workout generator should only be allowed for users after they have registered. This is to allow for workouts/routines to be saved, and modified, and find other options to accommodate users. Having this feature outside of the FitShare domain, can lead to an extra set of effort needed for public viewing rather than simply viewing strictly within the application. This survey would be accessible through many methods, but one of the most convenient for the user should be somewhere on the homepage.
    - Going forward will work on the scope(s) of the feature