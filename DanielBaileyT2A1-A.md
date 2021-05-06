# **Assignment 1: Workbook Part A**
## Question 1
Ruby on Rails (or simply Rails) is a structure for designing web-based applications. It uses an architectural pattern known as Model-View-Controller, or MVC, which is modular and flexible for a variety of applications. This modularity ensures that the program is secure and easy to modify. As per the name, this architecture has three different aspects: Models, Views and Controllers. (Mejia, 2021)

### Models
Models within the architecture contain all of the data and data manipulation used by the program. It tells the program which information to use.

### Views
Views are essentially the user interface for the program. They contain all of the information displayed to the user, and allow the user to interact with the application.

### Controllers
Controllers control the interactions between models and views. These allow the models and views to be separate without containing reference to one another, therefore ensuring that the application is secure.

## Question 2
The open-source database management system, known as PostgreSQL, is a database management system that is commonly used in rails applications. (PostgreSQL: a closer look at the object-relational database management system, 2019)

PostgreSQL has some advantages and some disadvantages, when compared to other database management systems:
### Advantages
As an open-source system, PostgreSQL has had support for features like triggers, custom data types, transactions and stored procedures for much longer than software such as MySQL. (Advanced Rails, 2021)

PostgreSQL has support for multiversion concurrency control (MVCC) which helps against problems like nonrepeatable, dirty or phantom reads. It does this by providing each concurrent transaction with it's own data sets through timestamps. (Advanced Rails, 2021)

### Disadvantages
PostgreSQL is formatted for use on weak machines with as little as 64 megabytes of RAM. It therefore has a reputation of being slow and needs to be tweaked for use in a serious setting. (Advanced Rails, 2021)

PostgreSQL also has a small community working on it, compared to other systems such as MySQL. Therefore a lot less testing has occurred in PostgreSQL: The community has a lot less support in terms of forums and in fact has no official commercial support at all. (Advanced Rails, 2021)

## Question 3
The Agile methodology of project management is characterised by quick turnarounds of project iterations and frequent reassessments of project goals and resources. This is in contrast to traditional project management, known as the Waterfall technique, where the entire project would be planned ahead of time and each task would have to be accomplished in order to "flow" on to the next one. The Agile technique is valued because it allows the frequent readjustments to resources and goals depending on circumstances, whereas the Waterfall technique may require the whole system to be restarted from the top.

## Question 4

The source control workflow is the way in which code can be worked on individually and then synched up to match the code being worked on by the rest of the team on a project. Source control is very similar to version control, with the main difference being that the former refers to only the source code, while the latter refers to versions of any application. Each member of the team has a fork of the central project repository that the team is working on, and they create a clone of this fork on their local repository. (Earnst, 2018) They then update from and commit to this remote fork, while this remote fork pushes to and pulls from the central project repository. This allows multiple people to be working on the same code at the same time, and ensures only stable, working code is pushed to and pulled from the central repository.

## Question 5

The standard software testing process is a code review process to ensure that your code and your team's code meets the specification of the project. It can also be used as a teaching and learning opportunity to improve your coding ability and the ability of your teammates. (The Role of Manual Software Testing in Software Development, 2021) There are several steps in the software testing process: (Brandon, 2020)
1. Make sure that any automated tests in the code pass.
1. Double check the code's logic and ensure it's working as intended.
1. Check all requirements and see that they're being met.
1. Add tests to any new code added (where appropriate).
1. Ensure the code meets the style guide created for the project.

## Question 6

Information Systems Security, also known as INFOSEC, is a series of guidelines and processes to ensure that data is available, confidential and has integrity. (What is Information Systems Security (INFOSEC)? - Definition from Techopedia, 2021)

This project will abide by the requirements set by the security policy created by ACME Corporation. The methods to accomplish these requirements will be described in the next section, but the information system requires:

- Authentication, to identify who the user is
- Access controls, so users can only have access to information that is deemed appropriate
- Encryption, so that restricted cannot be accessed remotely by unauthorized users during transmission
- Physical security, so information systems cannot be accessed physically by unauthorized users. (Bourgeois and Bourgeois, 2021)

## Question 7

In relation to the above response, there are several methods for protecting information and data, which will be applied to this project.

### Authentication

The most common form of authentication is a username (or ID) and password. A user's password should never be shared with anyone, to ensure that the user is the only one with the knowledge, and therefore authentication, to access the program. Commonly, an authentication code is used in conjunction with a username and password, (Bourgeois and Bourgeois, 2021) such as codes provided by Google Authenticator, to increase the chance that the recipient of restricted information is the correct user.(Kaufman, 2021)

### Access controls

To ensure that users have the correct reading, writing, deleting and adding priviledges, they are assigned a role by system administrator. This role is in accordance with the system's role-based access control (RBAC), which ensures that only user's with certain roles may access the data in certain ways. (Bourgeois and Bourgeois, 2021)

### Encryption

To encrypt data over transit, 

## Sites used (needs editing)

Mejia, A., 2021. Ruby on Rails Architectural Design. [online] Adrian Mejia Blog. Available at: <https://adrianmejia.com/ruby-on-rails-architectural-design/#Model-View-Controller-Pattern> [Accessed 3 May 2021].

Medium. 2021. Overview of Ruby on Rails Architecture. [online] Available at: <https://medium.com/@SravanCynixit/overview-of-ruby-on-rails-architecture-9902de7c93f9> [Accessed 3 May 2021].

Digital guide by IONOS. 2019. PostgreSQL: a closer look at the object-relational database management system. [online] Available at: <https://www.ionos.com/digitalguide/server/know-how/postgresql/> [Accessed 3 May 2021].

O’Reilly Online Learning. 2021. Advanced Rails. [online] Available at: <https://www.oreilly.com/library/view/advanced-rails/9780596510329/ch04.html> [Accessed 3 May 2021].

Earnst, M., 2018. Version control concepts and best practices. [online] Homes.cs.washington.edu. Available at: <https://homes.cs.washington.edu/~mernst/advice/version-control.html> [Accessed 6 May 2021].

Performance Lab. 2021. The Role of Manual Software Testing in Software Development. [online] Available at: <https://performancelabus.com/manual-testing-in-software-development/#:~:text=Manual%20testing%20is%20the%20process,considering%20the%20end%20user's%20perspective.> [Accessed 6 May 2021].

Brandon J, 2020, Git Collaboration - Forking Workflow Lesson, Academy of Information Technology

Techopedia.com. 2021. What is Information Systems Security (INFOSEC)? - Definition from Techopedia. [online] Available at: <https://www.techopedia.com/definition/24840/information-systems-security-infosec> [Accessed 6 May 2021].

Bourgeois, D. and Bourgeois, D., 2021. Chapter 6: Information Systems Security. [online] Bus206.pressbooks.com. Available at: <https://bus206.pressbooks.com/chapter/chapter-6-information-systems-security/> [Accessed 6 May 2021].

Kaufman, M., 2021. Google Authenticator will add a formidable layer of protection to your e-mail account. [online] Mashable. Available at: <https://mashable.com/2017/10/29/how-to-set-up-google-authenticator/> [Accessed 6 May 2021].