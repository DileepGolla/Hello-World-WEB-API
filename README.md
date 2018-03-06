Submitted by: Golla Dileep Kumar

Assignment Given:
Write a Hello World program
1. The program has 1 current business requirement a write Hello World to the console/screen.
2. The program should have an API that is separated from the program logic to eventually support mobile applications, web applications, console applications or windows services.
3. The program should support future enhancements for writing to a database, console application, etc.
            - Use common design patterns (inheritance, e.g.) to account for these future concerns.
            - Use configuration files or another industry standard mechanism for determining where to write the information to.
4. Write unit tests to support the API.
5. Feel free to use a github program to store the coding exercise as I know that’s typically easier to use.

This Application Consists of :

- API- This contains the WEB API code.
- API.Tests- Unit test cases to test the application.
- Business.Models- Contains the database/list tables and corresponding models.
- Business.Services- Contains all the repository calls.
- ConsoleApp- Console application to print Hello World on the console.
- RepositoryLayer- Contains all the database/list calls.

Project Approach:
- In this project, the console application will print "Hello World" to the Console.
- It has an Web API which Fetches, Adds and Deletes items from a custon list.
- We can also use an external database which can be called from an API. But I used a custon list for simplicity.
- This project covers concepts like Inheritance, Interface implementation, WEB API 3-tier architecture.
- This API supports mobile applications,web applications and console applications.
- Unit test cases are written to test the controller functions like GET,PUT,POST,etc.
