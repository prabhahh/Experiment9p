Experiment 9: Implement SharedPreferences and SQLite Database in Android

1. Aim

To develop an Android application using SharedPreferences and SQLite Database to store, retrieve, update, and manage data locally within an Android device.

2. Introduction

Android provides different ways to store data in an application. Two important methods of local data storage are SharedPreferences and SQLite Database.

SharedPreferences is used to store small amounts of data in the form of key-value pairs. It is useful for saving simple information such as username, login status, user settings, and application preferences.

SQLite is a lightweight database available in Android. It is used to store structured data in tables. It allows users to insert, retrieve, update, and delete records.

This experiment demonstrates the use of both storage techniques in Android application development.

3. Objectives

To understand local data storage in Android.

To learn how to use SharedPreferences.

To understand SQLite Database.

To store and retrieve user information.

To perform basic database operations.

To understand the difference between SharedPreferences and SQLite.

4. Technologies Used

Android Studio: IDE used for developing Android applications.

Kotlin: Programming language used for application development.

XML: Used for designing the application interface.

SharedPreferences: Used to store small amounts of data.

SQLite Database: Used to store structured data locally.

Android SDK: Provides tools and libraries for Android development.

5. Concepts Used

A. SharedPreferences

SharedPreferences is a storage method in Android that saves data in key-value pairs.

It is mainly used for storing small amounts of information.

Examples:

Username

Password preferences (not raw passwords)

Login status

Application settings

Theme preferences

Important Operations:

getSharedPreferences() – Opens a SharedPreferences file.

edit() – Allows modification of stored values.

putString() – Stores string values.

putBoolean() – Stores Boolean values.

apply() – Saves changes asynchronously.

getString() – Retrieves stored string values.

B. SQLite Database

SQLite is a built-in lightweight database used to store structured information in Android applications.

It stores data in rows and columns.

Important Database Operations:

CREATE – Creates a database table.

INSERT – Adds new records.

READ – Retrieves stored records.

UPDATE – Modifies existing records.

DELETE – Removes records.

These operations are commonly known as CRUD operations.

6. Scenario Used

Consider an application that needs to save user preferences and personal information.

SharedPreferences can be used to remember simple details such as the user's name or login status.

SQLite Database can be used to store multiple records such as user details and other structured information.

This helps the application maintain data even after it is closed and opened again.

7. Procedure

Open Android Studio.

Create a new Android project.

Select Kotlin as the programming language.

Design the user interface using XML.

Create the required input fields and buttons.

Implement SharedPreferences to save and retrieve simple data.

Implement SQLite Database functionality.

Create a database helper class if required.

Write the necessary code for database operations.

Run the application on an emulator or Android device.

Test the SharedPreferences and SQLite functionalities.

Verify that the stored information can be retrieved successfully.

8. Features

Stores small amounts of data using SharedPreferences.

Saves user preferences locally.

Uses SQLite for structured data storage.

Supports basic CRUD operations.

Retrieves previously stored information.

Works without requiring an internet connection.

9. Advantages

Data can be stored directly on the device.

No internet connection is required.

SharedPreferences is simple and easy to implement.

SQLite supports structured data storage.

SQLite provides efficient database operations.

Both methods help improve application functionality.

10. Difference Between SharedPreferences and SQLite

SharedPreferences

SQLite

Stores data in key-value pairs.

Stores data in tables.

Suitable for small amounts of data.

Suitable for structured data.

Simple to implement.

Requires database operations.

Stores preferences and settings.

Stores multiple records.

Does not support complex queries.

Supports SQL queries.

11. Applications

Login and registration applications.

User preference management.

Offline applications.

Notes applications.

Contact management applications.

Applications that require local data storage.

12. Conclusion

Thus, the Android application using SharedPreferences and SQLite Database was studied and implemented successfully. SharedPreferences helps store small amounts of data in key-value pairs, whereas SQLite is useful for storing and managing structured data. This experiment helped in understanding different methods of local data storage in Android application development.
