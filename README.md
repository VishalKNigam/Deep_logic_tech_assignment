# Time Website Section Fetcher

This Node.js project fetches a particular section of the Time website and serves it as a JSON response. Additionally, it serves an `index.html` file for the root URL.

## Prerequisites

- Node.js installed on your machine.

## Installation

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/VishalKNigam/Deep_logic_tech_assignment
   ```
## Usage

1. Start the server by running the following command:
   ```
   node latestStories.js
   ```
2. Once the server is running, run the index.html file on browser and click on the given link:
   ```
   http://localhost:3000/getTimeStories
   ```
3. it will open the top 6 time-stories with title and link

## Code Overview

The `latestStories.js` file contains the Node.js server code. Here's a brief overview:

- The server fetches the Time stories section using a HTTPS request to the Time website.
- It extracts relevant information from the HTML response using regular expressions.
- The fetched data is then served as a JSON response for the `/getTimeStories` route.
- An `index.html` file is served for the root URL.
- Error handling is implemented for various scenarios such as server errors and invalid routes.

## Thank you