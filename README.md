# Online/Offline Budget Tracker

## Description

A budget tracking app that uses a service worker and indexedDB to function while offline. Also uses a MongoDB database.

## Usage

Input a name for the transaction and an amount; then click whether you are adding or subtracting funds. The app will automatically calculate the remaining sum (or debt) and update the graph to show the transaction.

## Installation

If you want to run your own instance of this app locally:

- download/clone this repo;
- navigate to the directory in the command line and run `npm i`;
- ensure that MongoDB is running;
- run `npm start`;
- navigate to localhost:3000 in a web browser.
