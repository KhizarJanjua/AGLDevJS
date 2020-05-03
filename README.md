# AGL Development Test

## Pet's Name by owner gender
A small JavaScript code to call an API using Axios, parse the JSON and display all _**Cats**_ grouped by their _owner gender_.

## Motivation
A development task to demonstrate how quickly we can roll out a project that consumes an API. A short and concise solution to the given problem, no heavy dependencies, compact and compatible, and easy to maintain.

## Screenshots
![Alt text](/AGL-Dev-Screenshot.png?raw=true "Cats, grouped by their owner name")

## How to use?
Just download the index.html and run it in any browser. It will call the AGL API, parse the JSON response and display the sorted results.

## Features
The main function **makeGetRequest(url,petName, true);** accepts petName (Cat | Dog | Fish), checkes for the API availbility and parse the JSON to display the sorted ul items.
  
## Tech/framework used
Axios in JavaScript, with request and response _interceptors_.

## Build status
Version 1.0.1 built and released.

## Debugging
The function **makeGetRequest(url,petName, true);** 3rd parameter is a debug parameter, which can be set to true/false to log/hide console messages. 
