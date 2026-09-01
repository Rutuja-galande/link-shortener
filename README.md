# link-shortener

## Link Shortener Service

## Overview
A URL shortener service implemented in Node.js, focusing on generating Base62 codes, tracking click analytics, and maintaining a zero-dependency architecture using pure Node HTTP.

## Features
- Generates short URLs using Base62 encoding.
- Tracks click analytics for each shortened URL.
- Implemented with zero external dependencies, leveraging native Node.js HTTP capabilities.

## Tech Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


- Node.js
- JavaScript
- REST APIs
- System Design

## Verified Setup
To set up the project locally:

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd link-shortener
   ```
2. Install dependencies (if any, though described as zero-dependency, `package.json` suggests there might be dev dependencies or scripts):
   ```bash
   npm install
   ```
3. Run the application:
   ```bash
   node server.js
   ```

## Usage
[Detailed usage instructions are not provided in the project description. This section would typically include examples of how to interact with the API, e.g., how to shorten a URL and retrieve click analytics.]

## Project Structure
link-shortener/
├── server.js             # Main server file to handle HTTP requests
├── shortener.js          # Core logic for URL shortening and Base62 encoding
├── test/
│   └── shortener.test.js # Unit tests for the shortener logic
└── package.json          # Project metadata and scripts

## Interview Questions
1. How does the Base62 encoding contribute to the efficiency and uniqueness of the generated short URLs?
2. Describe the approach taken to implement click analytics without external dependencies. What are the potential challenges and trade-offs?
3. Given that the service uses "pure Node HTTP" and has "zero dependencies," how would you scale this application to handle a large volume of requests and data?
