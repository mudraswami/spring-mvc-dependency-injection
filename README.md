# Spring MVC Dependency Injection

A Java Spring MVC project demonstrating XML-based dependency injection, bean configuration, and model-view interaction using the Spring Framework.

## Overview

This project demonstrates how Spring MVC can be used to build a simple web application while configuring application dependencies through an XML-based Spring configuration file.

The project uses `beans.xml` to define and wire `Faculty` and `Course` objects using Spring Dependency Injection.

## Features

- Spring MVC controller configuration
- XML-based Spring bean configuration
- Dependency Injection using constructor injection
- Bean-to-bean dependency using `ref`
- Model data passed from controller to view
- Simple JSP-based view

## Tech Stack

- Java
- Spring Framework
- Spring MVC
- JSP
- Maven
- XML Configuration

## Project Structure

```text
src/
├── main/
│   ├── java/
│   │   ├── controller/
│   │   │   └── MyController.java
│   │   └── model/
│   │       ├── Course.java
│   │       └── Faculty.java
│   ├── resources/
│   │   └── beans.xml
│   └── webapp/
│       └── hello.jsp
