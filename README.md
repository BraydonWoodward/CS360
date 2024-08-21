########################## This repository is for my Computer Science Journal, Class CS260: Mobile Architecture and Programming #####################################################

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
  The app I developed is an Inventory Management App designed to streamline the process of tracking and managing inventory items. he primary requirements included implementing login functionality, creating a database for inventory storage, enabling CRUD operations (Create, Read, Update, Delete) for inventory items, and incorporating SMS notifications for low inventory alerts. he app was designed to address user needs related to efficiently managing inventory in a warehouse or retail setting, providing an easy-to-use interface for updating item details, tracking stock levels, and ensuring timely alerts for restocking.
  
#################################################################################################################################################################################################################################################################################
  
What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
  To create a user-centered UI for the Inventory Management App, essential screens and features included:

    1. Login Screen: A secure, user-friendly login with validation indicators, password visibility toggle, and easy navigation for account creation and password reset.
    2. Inventory Management Screen: An intuitive layout for viewing, adding, editing, and deleting inventory items, with organized tables and accessible CRUD operation buttons to streamline tasks.
    3. Notification System: Integrated SMS notifications to alert users about low inventory levels, enabling prompt responses to stock shortages.
    4. Update Screens: Dedicated screens for updating inventory details were designed with clear input fields and validation feedback, ensuring users could easily make changes while minimizing errors.

  The designs prioritized simplicity, clarity, and accessibility, ensuring users could efficiently manage inventory without being overwhelmed. By focusing on core user needs, the app delivered a functional and user-friendly experience.
  
###############################################################################################################################################################################################################################################################################
  

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
  I approached coding the app with a structured, iterative process, breaking down core functionality into manageable tasks. Key strategies included:

    1. Modular Development: Dividing the app into distinct modules (e.g., authentication, database) for better organization and easier debugging.
    2. Test-Driven Development (TDD): Writing tests before coding to ensure functionality and minimize errors.
    4. Iterative Refinement: Continuously improving the code and UI based on testing and user feedback.

These techniques ensure efficient development, maintain code quality, and can be applied to future projects for scalable and user-friendly results.

###############################################################################################################################################################################################################################################################################
  
How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
  I tested my code using the Android Studio emulator throughout the development of the app. This is an important process as testing during development ensures a working product and reduces the risk of having major bugs or issues in the code. 

###############################################################################################################################################################################################################################################################################

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
  Throughout the app design and development process, one key challenge was integrating SMS notifications for low inventory alerts. Initially, handling permissions and ensuring smooth functionality across different devices was complex. I had to innovate by creating a dedicated SMSPermissionActivity to manage permissions dynamically, allowing the app to function seamlessly regardless of whether permissions were granted.

###############################################################################################################################################################################################################################################################################

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
  I was particularly successful in demonstrating my knowledge, skills, and experience in developing the CRUD operations and database integration. By structuring the SQLite database to efficiently store and manage inventory data, and implementing clean, user-friendly interfaces for each operation, I showcased my ability to handle both backend and frontend development. 
