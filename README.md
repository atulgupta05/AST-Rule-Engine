# Rule Engine Application
## Overview

This application is a rule engine that determines user eligibility based on attributes such as age, department, salary, and experience. It uses an Abstract Syntax Tree (AST) to represent and manage conditional rules, allowing for dynamic rule creation, combination, and evaluation.

<img width="943" alt="image" src="https://github.com/user-attachments/assets/78f6bdca-68aa-4818-a56f-5a50c2023b7f">


## Features

- **Create Rules:** Define rules using a string format that gets converted into an AST.
  
  <img width="377" alt="image" src="https://raw.githubusercontent.com/atulgupta05/AST-Rule-Engine/refs/heads/main/Screenshot%20(324).png">


- **Combine Rules:** Combine multiple rules into a single AST for more complex evaluations.
  
  <img width="376" alt="image" src="https://raw.githubusercontent.com/atulgupta05/AST-Rule-Engine/refs/heads/main/Screenshot%20(325).png">

  
- **Evaluate Rules:** Check if the given data meets the criteria defined by the AST.
  
  <img width="375" alt="image" src="https://raw.githubusercontent.com/atulgupta05/AST-Rule-Engine/refs/heads/main/Screenshot%20(326).png">


- **Tree Visualization:** Define or Combine Rule would should show Tree Representation.

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB Compass Tool

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB Compass tool installed and running

### Installation

1. **Clone the Repository**
   ```bash
   git clone "https://github.com/atulgupta05/AST-Rule-Engine.git"
   cd rule-engine
   ```

2. **Install Backend Dependencies**

   ```bash
   npm install
   ```
   
3. **Start MongoDB Compass**

   Ensure that MongoDB is running on your local machine:

   ```bash
   mongod
   ```

4. **Start the Backend Server**

   ```bash
   nodemon server.js
   then start "http://localhost:3000/"
   ```

## Running Testcases 
You can thanks me

