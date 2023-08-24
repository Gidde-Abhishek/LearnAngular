## Creating a Basic Angular Project for Kimberly: Step-by-Step Guide

In this guide, we'll walk you through creating a simple Angular project that displays a "Hello, Kimberly!" message on a web page.

### Step 1: Install Angular CLI

Angular CLI (Command Line Interface) is a powerful tool that simplifies Angular development tasks. Open your terminal and run the following command to install Angular CLI globally:

```bash
npm install -g @angular/cli
```

### Step 2: Create a New Angular Project

Let's create a new Angular project named "kimberly-angular-app." Navigate to the directory where you want to create the project using the terminal:

```bash
ng new kimberly-angular-app
```

Angular CLI will ask you a few questions about project features. For simplicity, you can select the default options by pressing the Enter key.

### Step 3: Navigate to the Project Directory

Move into the project directory:

```bash
cd kimberly-angular-app
```

### Step 4: Understand Project Structure

Angular projects have a predefined structure with key directories and files:

- **src:** This directory contains the source code of your app.
- **src/app:** This is where your app's components and modules will reside.
- **src/index.html:** The main HTML file that hosts your app.

### Step 5: Create a Component

Components are the building blocks of an Angular app. They encapsulate UI elements and logic. Let's create a component named "welcome" to display a message for Kimberly.

In the terminal, run:

```bash
ng generate component welcome
```

This generates the component files in the `src/app/welcome` directory.

### Step 6: Edit the Component

Open `src/app/welcome/welcome.component.ts` in your code editor. Replace its contents with the following code:

```typescript
import { Component } from '@angular/core';

@Component({
  selector: 'app-welcome',
  template: '<h1>Hello, Kimberly!</h1>',
})
export class WelcomeComponent {}
```

This component defines a template that displays a heading with a message for Kimberly.

### Step 7: Use the Component

Now, let's use our new component in the app. Open `src/app/app.component.html` and replace its contents with:

```html
<app-welcome></app-welcome>
```

This code includes our `WelcomeComponent` in the main app component's template.

### Step 8: Run the App

In the terminal, run the following command to start the development server:

```bash
ng serve
```

After the server starts, open your web browser and navigate to `http://localhost:4200`. You should see the "Hello, Kimberly!" message displayed.

### Step 9: Exploring Further

Congratulations, Kimberly! You've successfully created a basic Angular app that greets you. From here, you can explore more advanced features like creating additional components, setting up routing, working with services, and integrating APIs.

## Conclusion

You've successfully created a basic Angular project for Kimberly and learned about key concepts such as components, templates, and the Angular CLI. Continue exploring the vast capabilities of Angular to build more sophisticated and interactive web applications. Happy coding, Kimberly!
