# reLaunchHer

reLaunchHer is a website created to help women transition back into the workforce by generating personalized job roles and learning paths using OpenAI's API.

## Description

This is a website created using React, Spring Boot, and MySQL. The application utilizes the OpenAI API to generate job roles based on user inputted interests and skills.

## Getting Started

### Dependencies

* Node v22.3.0, npm 10.8.2

### Executing program

* How to run the program
- Create a local database to hold users
    create a database - relaunchher;
    create a table - user_info;
    add a fake user data;
    set up application.properties file like this:
    spring.datasource.url=jdbc:mysql://localhost:3306/yourdb
    spring.datasource.username=root
    spring.datasource.password=yourpassword
- Create an OpenAI account, update API key in application.properties
* Step-by-step bullets
``'
    - frontend
        npm start
    - whole project
        ./mvnw clean install
```

## Authors

Contributors names

Shirley Xiaoxue Fang


## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
