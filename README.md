### Project Architecture Summary

## Frontend:
Technologies: HTML, CSS, Bootstrap, React
Description: The frontend includes static pages like the homepage, About Us, and Contact Us created using HTML, CSS, and Bootstrap for styling. Dynamic components such as login, registration, dealership views, and review functionalities are developed using React. This setup ensures a seamless and interactive user experience.
Backend Services:

## Main Application (Django)
Technologies: Python, Django, SQLite
Description: Serves as the core backend for user management and displaying user views. It handles sessions, user authentication, and interactions with a SQLite database for storing user and dealership data.

## Sentiment Analysis Microservice
Technologies: Python, Flask, NLTK
Description: This microservice uses Flask and the Natural Language Toolkit (NLTK) to analyze sentiments of reviews. It processes textual data to determine if sentiments are positive, negative, or neutral, enhancing the review information provided to users.
## Dealership and Review Service

Technologies: Node.js, Express, MongoDB
Description: Manages dealership and review data, offering RESTful APIs to handle operations like fetching and posting reviews and dealership information. This service uses MongoDB to store data due to its flexibility and performance with large volumes of data.

## Deployment and Operations:
Technologies: Docker, Kubernetes, IBM Cloud Code Engine
Description: The application components and microservices are containerized using Docker, making them portable and easy to deploy. Kubernetes is used for orchestrating these containers, ensuring scalability and reliability. The Serverless framework on IBM Cloud Code Engine is utilized for deploying stateless services like the sentiment analysis microservice.

This architecture leverages modern web technologies and microservices to create a robust platform for managing and displaying car dealership reviews, ensuring the site is scalable, maintainable, and responsive.
