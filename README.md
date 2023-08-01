# E_learning_platform

This is a Django project for creating Online learning platform with own Content management system(CMS).
This project contains the creation of following:
Creating of CMS:
  • Create a content management system using class-based views and mixins
  • Build formsets and model formsets to edit course modules and module contents
  • Manage groups and permissions 
  • Implement a drag-and-drop functionality to reorder modules and content

Rendering and Caching Content:
  • Create public views for displaying course information
  • Build a student registration system
  • Manage student enrollment onto courses
  • Render diverse content for course modules
  • Install and configure Memcached
  • Cache content using the Django cache framework
  • Use the Memcached and Redis cache backends
  • Monitor your Redis server in the Django administration site

Building an API
  • Install Django REST framework
  • Create serializers for your models
  • Build a RESTful API
  • Create nested serializers
  • Build custom API views
  • Handle API authentication
  • Add permissions to API views
  • Create a custom permission
  • Implement ViewSets and routers
  • Use the Requests library to consume the API 

Building a Chat Server:
  • Add Channels to your project
  • Build a WebSocket consumer and appropriate routing
  • Implement a WebSocket client
  • Enable a channel layer with Redis
  • Make your consumer fully asynchronous

Set up production environment:
  • Configuring Django settings for multiple environments
  • Using Docker Compose to run multiple services
  • Setting up a web server with uWSGI and Django
  • Serving PostgreSQL and Redis with Docker Compose
  • Using the Django system check framework
  • Serving NGINX with Docker
  • Serving static assets through NGINX
  • Securing connections through TLS/SSL
  • Using the Daphne ASGI server for Django Channels
  • Creating a custom Django middleware
  • Implementing custom Django management commands


Topics and short description that I learned during development of this project:
Docker:
Docker is an open-source platform that allows developers to automate the deployment, 
scaling, and management of applications inside lightweight, portable containers. 
Containers are self-contained environments that package an application with all 
its dependencies (libraries, frameworks, and other necessary files) 
so that it can run consistently across different environments.


Memcached
Memcached is a distributed in-memory caching system used to speed up 
the retrieval of data from a data store (such as a database) 
by caching frequently accessed data in memory. 
It is often used to reduce the load on backend databases and 
improve the performance of web applications.


Redis:
Redis is an in-memory data structure store that serves as a caching solution, 
as well as a robust database and messaging broker. 
It is known for its speed, simplicity, and support for a wide range of data structures.

Channels
WebSockets
Consumers
Routing
Channel Layer

Nginx
