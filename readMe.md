
## Top technologies to know

### API's and Postman
What are API's how are they used
How postman can help us test them

### SQL
All companies need to store data one of the most popular Data Bases out there is Microsoft SQL DataBase.
There are many others such as MongoDB, Couch, NoSQL etc...
However especially with more traditional business SQL is often what they have or have been using for decades so it often comes in handy to know the basics even if a person isn’t  too familiar with it.

SQL has a special syntax that helps you search and retrieve information from a SQL database.
Learn the most basic syntax on how to retrieve items from a database or to search for them.

Example data table:

Table name is Employees

| Name | LastName | Address | Age |
| ------ | -------| --------| ----|
| Peter | Krastanov| 12 Eskvale | 33 |
| Vanya | Prodanova | 12 Eskvale | 33 |
| Martina | Tashkova | 5 London Road | 30 |

Example query:
```SQL
SELECT * FROM Employees
```

Result:

| Name | LastName | Address | Age |
| ------ | -------| --------| ----|
| Peter | Krastanov| 12 Eskvale | 33 |
| Vanya | Prodanova | 12 Eskvale | 33 |
| Martina | Tashkova | 5 London Road | 30 |

Example query:
```SQL
SELECT Name, Age FROM Employees
```

Result:

| Name | Age |
| ------|----|
| Peter | 33 |
| Vanya | 33 |
| Martina | 30 |

Example query:

```SQL
SELECT * FROM Employees
WHERE Age = 33
```

Result:

| Name | LastName | Address | Age |
| ------ | -------| --------| ----|
| Peter | Krastanov| 12 Eskvale | 33 |
| Vanya | Prodanova | 12 Eskvale | 33 |


### JavaScript & TypeScript

Java Script has exploded in the last 5 years as a language that gives you access to all of the benefits of a object oriented programming language but it will run in a browser giving the ability to control and manipulate what the browser does and shows and allowing developers to make truly dynamic websites and QA much more control over how we can automate our tests.
Due to that there is no surprise the language has now surpassed both java and c# when it comes to e2e (End to End) tests.

One of the major shortcomings of the language is the lack of types. Simply put anything you crate Objects methods or anything else can be treated either way. Allowing for a lot of flexibility but also a lot of room for mistakes and errors.

TypeScript is not a separate language but more like an addition to Java Script developed by Microsoft that introduces the concept of types inside of Java Script. This way if you specify something as a method that takes strings you can enforce that rule using typescript.

There are a number of online courses online look for ones that are for absolute beginners that will explains the basics of programming as well not just the language.

The one I used to learn from is this:
[CodeCademy](https://www.codecademy.com/learn/introduction-to-javascript)

This will be by far the most time consuming!


### Visual Studio Code
Simple text editor Like NotePad.
But it has about Bazilion extensions allowing you too develop in lots of different languages.

## Next steps

If you cover the ones above you can look into the following as well but they are more for when you start to grow in the role.

### Git

Git is version control system and it is used so that many people can work on the same thing at the same time. It also allows people to go back to a previous  version of a documents.
You will again need the absolute minimum here no need to know how to do anything but the most basic commands.
Git is a console application so you will be interacting with it through the terminal but there are a number of tools that allow visual representation of the tool for those that can't be bothered to learn the commands.

### BDD
BDD or Behavioural Driven Development is a way of working or a practice.
You can read more about on the subject if you are interested.
But the most relevant thing you will come into contact is Cucumber it's a library that allows for a test to be described as a user story and then the automation happens based on the description allowing absolutely everyone to be able to read the automated tests rather then only those with programming background.

### POM
POM or Page Object Model
Is a way for you to structure a automated framework. Literally tells you how to order you files and objects within to allow maximum reusability and readability.
Again you can read more on the subject but just a general knowledge you will not need this until you start working on the automation.

### MarkDown
This document you are reading is done in markdown it is essentially used for documentation all projects have some documentation about how to run them and people tend to add more as the project grows.
Markdown has started to be preferred to more traditional Documenting platforms such as Confluence, so it is worth taking a look at it.

### What about Jira

Jira is a paid tool and there is no super easy way to learn anything about it.
Add to that that Jira is very modular meaning that even if it looks one way in one place it might look different in another company based on their work flow it is probably not worth waisting too much time on it.
Plus Jira will most of the time follow the Best scrum practice so if you are familiar with that the software will try to mimic the flow described there