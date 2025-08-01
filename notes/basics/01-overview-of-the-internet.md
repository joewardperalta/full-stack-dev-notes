# Overview of the Internet

This unit introduces the basics of web development and software 
engineering, including how the internet works, what programming means, 
and the roles of front-end, back-end, and full-stack developers.


## What is a Network

A **network** is a system of **interconnected devices** that can 
communicate with each other and share resources.

### Interconnected

Devices are **linked or connected** in a way that allows 
**interaction and communication**.

### Example

- **WI-FI** is a type of network that connects multiple devices so 
they can access the internet and communicate with one another.


## The First Interconnected Network

**ARPANET**, developed in 1969 and funded by the U.S. Department of 
Defense, was the first interconnected network and a precursor to the 
internet. It was designed to connect supercomputing centers at 
government agencies and universities to share information.


## Protocols

Institutions wanted to communicate and share information, but they 
couldn’t because they used different rules and systems. This is why 
**TCP/IP** was created—to provide a standard way for networks to 
communicate. The interconnected global network of networks that is 
today known as the internet was formed.

### TCP

The **Transmission Control Protocol** ensures that data is sent and 
received correctly.

### IP

The **Internet Protocol** handles the address system so data knows 
where to go.


## Internet

The internet refers to the actual network of connected devices. 
Its primary purpose is to send messages from one computer to another. 
There is no specific built-in way for people to browse information on 
the internet, which is why the **World Wide Web** was created.


## World Wide Web

The World Wide Web was invented by Tim Berners-Lee. It’s a collection 
of interlinked websites and other web resources. It’s like a library 
full of content.

In 1990, the rise of web browsers began, providing an intuitive way 
for people to browse the internet and access information on the 
World Wide Web.


## Browsers and Servers

On the internet, information is sent from one computer to another. 
This process is explained by the **client-server model**.

The **client-server model** is a system where one computer 
(the client) requests information and another computer (the server) 
provides it.


## Hypertext Transfer Protocol (HTTP)

Browsers use an internet protocol called HTTP to request information 
from the internet.

### Request Methods

  - **GET** - used to retrieve data from the server
  - **POST** - used to send data to the server to create a new 
  resource
  - **PUT** - used to update/replace an existing resource
  - **DELETE** - used to remove a resource from the server

### Status Code

An HTTP status code is a 3-digit number returned by a server as part 
of the response to indicate whether or not the response was 
successful. They contain some information about the type of error. 
It helps the browser know how to handle the data that was sent back 
with the response.

| **Code**                  | **Explanation**                      |
|---------------------------|--------------------------------------|
| 200 OK                    | The request has succeeded            |
| 301 Moved Permanently     | The resource has been moved          |
| 404 Not Found             | The requested resource was not found |
| 500 Internal Server Error | The server encountered an error      |


## Evolution of Web Development: From Static to Web 2.0

In the early days of the internet, websites were static made up of 
fixed text, images, and links—with little to no interactivity. 
These pages didn’t change based on user behavior and required full 
reloads to navigate between content.

By the early 2000s, the web evolved into what is known as **Web 2.0**. 
This era introduced **dynamic web applications** where content could 
update in response to user input without refreshing the page. 
It also emphasized user participation, giving rise to blogs, 
social media, and collaborative platforms like wikis.

Key technologies powered this shift. **jQuery** enabled fetching data 
dynamically while a page was running. On the server side, frameworks 
like **Spring**, **Django**, and **Ruby on Rails** made it easier 
to connect to databases, store user-generated content, and display 
it in real time.


## Current Internet Trends

The rise of smartphones has transformed internet usage, with mobile 
traffic now exceeding 50% of total internet activity. This shift has 
driven major changes in web development to ensure seamless user 
experiences across all devices.

### Responsive Design

Responsive design adapts websites to different screen sizes using CSS 
features like media queries and relative units. This ensures sites 
look good on desktops, tablets, and phones.

### Mobile Apps vs Web

Mobile users spend more time in apps than browsers. While apps are 
internet-connected, they’re not part of the web. Apps aim to retain 
user attention within a single environment.

### Web Dev as a Starting Point

Web development is a solid foundation for learning mobile app 
development. Although apps are often built with languages like 
**Swift**, **JavaScript frameworks (like React Native)** are 
increasingly used to build cross-platform apps.