# Health Challenge Tracker - Angular SPA

## Overview

The **Health Challenge Tracker** is a Single Page Application (SPA) built using **Angular 14+**. The application allows users to track their workout activities, including workout type and duration. Users can add their workout data, and the application will display the information in a table with the ability to **search by name**, **filter by workout type**, and **paginate** through the results. 

This project also includes an optional feature to visualize workout progress using **charts**. The application data is stored in **localStorage** to retain the information between sessions.

## Features

<ul>
  <li><strong>User Input:</strong> Collects the user's name, workout type, and workout duration (in minutes).</li>
  <li><strong>Workout List:</strong> Displays entered workout data in a table format with search and filter functionalities.</li>
  <li><strong>Pagination:</strong> Handles pagination when there are more than 5 users/workouts.</li>
  <li><strong>Workout Progress Visualization (Optional):</strong> Shows workout progress using charts.</li>
</ul>

## Prerequisites

Before running the application, ensure you have the following tools installed:

<ul>
  <li><strong>Node.js</strong> (version 14 or higher)</li>
  <li><strong>Angular CLI</strong> (latest version)</li>
</ul>

You can install **Node.js** and **Angular CLI** by following these links:
<ul>
  <li><a href="https://nodejs.org/">Node.js download</a></li>
  <li><a href="https://angular.io/cli">Angular CLI installation</a></li>
</ul>

## Setup

Follow these steps to get the project running locally:

<ol>
  <li><strong>Clone the repository:</strong>
    <pre><code>git clone https://github.com/SHUBHAMCODEC/Health-Challenge-Tracker.git</code></pre>
  </li>
  
  <li><strong>Navigate to the project folder:</strong>
    <pre><code>cd Health-Challenge-Tracker</code></pre>
  </li>
  
  <li><strong>Install the required dependencies:</strong>
    <pre><code>npm install</code></pre>
  </li>
  
  <li><strong>Serve the application locally:</strong>
    <pre><code>ng serve</code></pre>
  </li>
  
  <li><strong>Open the application:</strong>
    Once the server is running, open your browser and navigate to:
    <p><code>http://localhost:4200</code></p>
  </li>
</ol>

You should see the Health Challenge Tracker application.

## Unit Testing

The project includes unit tests for the component and service, with 100% code coverage. To run the tests and generate a code coverage report, use the following command:

<pre><code>ng test</code></pre>

This will run the tests and display the results, along with the code coverage percentage.

## Built With

<ul>
  <li><strong>Angular 14+</strong>: The framework used to build the SPA.</li>
  <li><strong>Tailwind CSS</strong>: For styling the application.</li>
  <li><strong>localStorage</strong>: For storing workout data persistently.</li>
  <li><strong>ng2-charts (Optional)</strong>: For charting workout progress.</li>
</ul>


