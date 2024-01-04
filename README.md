# Documentation playbook

This playbook can be used as a base to add documentation to your project. When starting with documentation, the first step is to update the [README.md](README.md) of the project. You can start your README from the section below and remove this description

# App Name

Change the title with the app name and give a one line description about the project. One line Description. Include a screenshot of the main screen of the project.

## Getting Started

Steps on how to get the project setup in the local system. List the commands to run for installing dependencies in the project. Commands to run code in the cmd can be wrapped between **```bash** and **```.** Follow the markdown syntax to clearly explain how the project can be setup in local.

For example, for a React or node.js project, you can install dependencies using:
```bash
yarn
# or
npm install
```

## Setting up Environment variables

Copy over `.env.example` as `.env.local`.

## Running the project

First, run the development server:

```bash
yarn dev
```

Open http://localhost:3000 (Replace with your respective development url) with your browser to see the result.

## Project Flow

Consider including a diagram or flowchart that shows the functionality of the project. This can be particularly helpful for more complex projects.

## Project Structure

Proceed to explain briefly about the project structure for development. The main folder structure of the project is as follows:

```md
├── public  
├── src  
│ ├── components  
│ ├── helpers  
│ ├── pages  
│ │ ├── api  
│ ├── styles  
```

Detailed project structure can be found at [project-structure.md](project-structure.md)

## Deployment

Finally, detail the steps for deployment to the server.

## Running Tests

If you have written units tests in your project, you can detail the steps for the tests here.

## License

Provide details about the license for use if required.