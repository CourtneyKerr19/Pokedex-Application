# Pokedex-Application

Personalized Pokedex Application using JavaScript, HTML, and CSS. Phase-1 Project for Flatiron School.

## Description

This project is a simple Pokedex application that allows users to view and search for Pokemon. The app fetches data from the PokeAPI and displays it in a user-friendly format.

## Features

- Fetch and display Pokemon data from the PokeAPI
- Interactive Pokemon cards with hover effects
- Display additional details like types, abilities, base stats, moves, evolution chains, base experience, color, habitat, egg groups, generation, capture rate, gender ratio, growth rate, held items, forms, and game indices
- Search functionality to filter Pokemon by name
- Responsive design for various screen sizes

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/CourtneyKerr19/pokedex-application.git
   cd pokedex-application
   ```

## Phase 1 Project Guidelines

Learning Goals

Design and architect features across a frontend
Communicate and collaborate in a technical environment
Integrate JavaScript and an external API
Debug issues in small- to medium-sized projects
Build and iterate on a project MVP
Introduction
Welcome to JavaScript Project Mode!

You’ve worked so hard to get here and have learned a ton. Now it's time to bring it all together!

For this project, you're going build a Single Page Application (SPA). Building this application will be challenging because it will integrate everything you've learned up to this point. Your frontend will be built with HTML, CSS, and JavaScript and will communicate with a public API.

Project Requirements

Your app must be a HTML/CSS/JS frontend that accesses data from a public API or from a db.json file using json-server. Your API or db.json should return a collection of at least 5 objects with each object having at least 3 attributes. All interactions between the client and the API should be handled asynchronously and use JSON as the communication format. Try to avoid using an API that requires a key. APIs that are free and require no authorization will be easiest to use. For ideas, see this list of no-auth APIs. If you would like to use an API that requires a key, please consult with your instructor on how to protect that key. NEVER push your API key to github!

Your entire app must run on a single page. There should be NO redirects or reloads. In other words, your project will contain a single HTML file.

Use at least 3 distinct event listeners (3 events of different types) that enable interactivity. What this means is that, if you had 3 click events, that would only count as 1 distinct event and you would need to add at least 2 more. Think search or filter functionality, toggling dark/light mode, upvoting posts, etc. Each of your event listeners should also have its own unique callback function. These must be added using JavaScript's .addEventListener() method. Events embedded into HTML elements and CSS will not count toward the total. Please ask your instructor if you have questions regarding this requirement.

Your project must implement at least one instance of array iteration using available array methods (map, forEach, filter, etc). Manipulating your API data in some way should present an opportunity to implement your array iteration.

Follow good coding practices. Keep your code DRY (Do not repeat yourself) by utilizing functions to abstract repetitive code.

Stretch Goals
Use json-server in your project to persist your app's interactivity.
