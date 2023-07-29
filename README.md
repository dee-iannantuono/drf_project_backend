# She Sports
by Dee - She Codes crowdfunding project - DRF Backend.

## About
The website aims to empower women between the ages of 10 and 35 by offering diverse funding opportunities for various sporting needs. From covering travel expenses to acquiring equipment, uniforms, and coaching services, it's a platform dedicated to supporting female athletes in their athletic pursuits.

## Features
* Create an account page so users can see their projects and projects that they have pledged to.
* Create a project page.
* Allow users to pledge to a project.

### Stretch Goals
* Allow users who have created a project to update a news feed so that users who have pledged can have updates to the users athletic journey.
* Allow for users to search for projects based on what sport they are for. Probably have to create categories for each project.
* Have a scale on the home page that indicates how much money has been raised so far for womens sports.

## API Specification

| HTTP Method | Url | Purpose | Request Body | Successful Response Code | Authentication <br /> Authorization
| --- | ------- | ------ | ---- | -----| ----|
| GET | projects/ | Return all projects | N/A | 200 | N/A |
| POST | projects/ | Create a new project | project object | 201 | User must be logged in. |

## Database Schema
![Database Schema](crowdfunding/imgs/database_schema.png)

## Wireframes
![Wireframe](crowdfunding/imgs/wireframe_1.png)

## Colour Scheme
Blue - CMYK 100/96/22/12<br>
Cream - CMYK 2/6/20/0

![Colour Scheme](crowdfunding/imgs/drf_colour.png)

## Fonts
Heading - Lionel Classic<br>
Body - Helvetica

## Submission Documentation
{{ Fill this section out for submission }}

Deployed Project: [Deployed website](http://linkhere.com/)

### How To Run
{{ What steps to take to run this code }}

### Updated Database Schema
{{ Updated schema }}

![image info goes here](./docs/image.png)

### Updated Wireframes
{{  Updated wireframes }}

![image info goes here](./docs/image.png)

### How To Register a New User
{{ Step by step instructions for how to register a new user and create a new project (i.e. endpoints and body data). }}

### Screenshots
* [] A screenshot of Insomnia, demonstrating a successful GET method for any endpoint.
![image info goes here](./docs/image.png)

* [] A screenshot of Insomnia, demonstrating a successful POST method for any endpoint.
![image info goes here](./docs/image.png)

* [] A screenshot of Insomnia, demonstrating a token being returned.
![image info goes here](./docs/image.png)