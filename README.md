# API NASA project with Postman + Newman
Project with using NASA API by Postman + Newman

## Table of Contents

- [Project Title](#API)
- [Introduction](#Built)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

This Postman collection includes automated tests designed to achieve the following objectives: 
1. Identify the cameras utilized and determine the number of pictures captured by a particular rover on a specific sol.
2. Identify a picture that matches a specified ID, rover, and sol.

## Installation

1. Clone the project to your machine
2. Clone the repo
3. Install newman package
   ```console
   $ npm install -g newman
   ```
## Usage

In CLI in the collection folder run the next command:
   ```console
   $ newman run API_NASA_TEST_PROJECT.postman_collection.json -e NASA.postman_environment.json
   ```
   
 
