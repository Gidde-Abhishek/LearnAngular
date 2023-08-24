# Beginner's Guide to Creating Your First Angular App

Welcome to the Beginner's Guide to Creating Your First Angular App! In this guide, we'll walk you through the process of setting up your environment, creating a basic Angular project, and understanding the key concepts along the way.

## Table of Contents
1. Introduction to Angular and TypeScript
2. Setting Up Your Environment
3. Creating a New Angular Project
4. Exploring Components
5. Adding Your Own Component
6. Running Your Angular App
7. Conclusion

## 1. Introduction to Angular and TypeScript

Angular is a modern web framework that helps you build dynamic and interactive web applications. It uses TypeScript, a superset of JavaScript that adds features like static typing and enhanced code organization.

## 2. Setting Up Your Environment

Before we start, you need to make sure you have Node.js and npm (Node Package Manager) installed. These tools help manage packages and dependencies for your projects.

To check if you have Node.js installed, run:

```bash
node -v
```

To check if you have npm installed, run:

```bash
npm -v
```

If they're not installed, you can download and install them from the official [Node.js website](https://nodejs.org/).

## 3. Creating a New Angular Project

Angular provides a command-line tool called Angular CLI to help you create and manage projects. To install Angular CLI globally, open your terminal and run:

```bash
npm install -g @angular/cli
```

## 4. Exploring Components

In Angular, everything is a component. A component is like a building block for your app's user interface. It's a combination of TypeScript code and an HTML template.

## 5. Adding Your Own Component

Let's create a simple "Hello, Angular" application.

1. Open your terminal and navigate to the directory where you want to create your project.

2. Run the following command to generate a new Angular project:

   ```bash
   ng new hello-angular-app
   ```

3. Change to your project's directory:

   ```bash
   cd hello-angular-app
   ```

4. To create a new component, use the Angular CLI:

   ```bash
   ng generate component greeting
   ```

   This will generate files for your new component.

## 6. Running Your Angular App

Now that we've created our component, let's see our app in action.

1. In the terminal, make sure you're still in your project's directory.

2. Run the development server:

   ```bash
   ng serve
   ```

3. Open your web browser and go to `http://localhost:4200`.

## 7. Conclusion

You did it! You've successfully set up your environment, created an Angular project, and explored the basics of components. This is just the beginning of your Angular journey. As you continue, you can learn about services, routing, and more advanced topics. Happy coding!