# Music app <a name="readme-top"></a>
![Static Badge](https://img.shields.io/badge/status-completed-green?style=for-the-badge)

## Introduction
**Music app** is a Java-based application designed to demonstrate the principles of inheritance and encapsulation. The core idea is to create a superclass, `Audio`, and extend it to subclasses like `Podcasts` and `Music`, while managing favorite items such as songs and podcasts in a controlled way. This approach highlights the importance of encapsulation to restrict direct access to class attributes.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Contributors](#contributors)

## Installation

### Prerequisites
- Java JDK 18+ installed
- An IDE such as IntelliJ IDEA, Eclipse, or NetBeans installed

### Steps to run
1. Clone the repository:
   ```bash
   git clone https://github.com/victorhubarb/banking-operations.git
   cd banking-operations
   ```
2. Open the project in your preferred IDE:
- Import the project into your IDE (e.g., using “Open Project” in IntelliJ or “Import Project” in Eclipse).
- Ensure the project uses the correct Java SDK (JDK 18+).

3. Run the application:
- Locate the Main class in the project structure.
- Right-click on the Main class and select Run.

## Usage
The application provides functionality to manage audio items such as songs and podcasts. It demonstrates encapsulation by restricting access to attributes like title, duration, total reproductions, likes, and ratings, allowing controlled interaction through methods like play, like, and rate. Users can also create a list of favorite songs and podcasts.

## Features
- **Audio Management**:
  - A superclass Audio encapsulates common attributes such as title, duration, total reproductions, likes, and ratings.
  - Subclasses Music and Podcasts inherit from Audio and add specific functionalities.

- **Encapsulation**: Prevent direct access to attributes in the Audio class, allowing interactions only through controlled methods.
  
- **Favorites Management**:
  -  Create and manage a list of favorite songs and podcasts.
  -  Add, remove, and list favorite items.

## Technologies
- **Java**

## Contributors
- [Victor Barbosa](https://github.com/victorhubarb)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
