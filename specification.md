# Specification

- [Specification](#specification)
  - [Description](#description)
    - [Task](#task)
    - [Actors](#actors)
      - [Admin](#admin)
      - [User](#user)
    - [Functions](#functions)
      - [Web Application](#web-application)
      - [Android Application](#android-application)
  - [GUI Designs](#gui-designs)
    - [Mobile Application](#mobile-application)
    - [Web Application](#web-application-1)

## Description 

### Task

The task is a photo sharing service where photos are categorized.
The service will contain a web and a mobile application.
The pictures are uploaded by users who can view and rate pictures of others.
Categories are managed by administrators.

### Actors 

#### Admin
Responsible for managing the categories.

#### User
Uses the service via the mobile application.

### Functions

#### Web Application

- **Registration(user)**: Registration with e-mail and password
- **Login(admin)**: Login with e-mail and password
- **Management of categories(admin)**: Creating updating, and deleting categories

#### Android Application

- **Login(user)**: Login with e-mail and password
- **Picture upload(user)**: Uploading pictures with given metadata:
  - Picture Name
  - Picture Description
  - Picture Category
- **List pictures(user)**: Unfiltered, or filtered by category
- **Search(user)**: Fuzzy text search in all the pictures
- **Rating(user)**: Rating of pictures on a 1-5 scale

## GUI Designs

### [Mobile Application](https://www.figma.com/file/I8u06W71sjtWlPFUwvjOQu/Untitled?node-id=0%3A1)

### [Web Application](https://www.figma.com/file/wXklaVaNdsgh9i30ZG5wcI/Untitled?node-id=0%3A1)
