---
name: InsightUBC
tools: [Typescript, HTML, CSS, Node.js]
image: 
description: A full-stack web application providing the user with a way to query course/room information in UBC
---

# InsightUBC

InsightUBC is a full-stack web application that provides a query system for UBC course and room information. This project is created with Typescript, HTML, CSS, and Node.js for [UBC’s Software Construction course](https://github.com/ubccpsc/310/blob/2019sept/project/README.md).

- Test-driven design
    * Mocha and chai is used to create unit tests
    * Coverage test
- Course and room data are retrieved from the web application using REST API
    * Implemented using Restify framework
    * Tested with Postman
- Front end
    * User input is detected using the DOM
    * A query is then generated based on the user input
    * The query is sent to the server to retrieve the information user requested
    * Once the browser receives the result, it will render the result in a table

{% include elements/figure.html image="Project/insightPost.png#center" caption="Interface of the webpage" %}