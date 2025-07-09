# Express.js Backend Development - Complete Guide (Scratch to Advanced)

<ol>
  <li>Introduction to Express.js
    <ol>
      <li>What is Express.js?</li>
      <li>Why Use Express.js?</li>
      <li>When to Use Express.js?</li>
      <li>Express.js vs Other Node Frameworks</li>
      <li>Install Node.js (If not installed)</li>
      <li>Installing Express.js</li>
      <li>First Express Server Example</li>
      <li>Basic Project Structure Example</li>
    </ol>
  </li>
 <li>Setting Up the Development Environment & Project Structure Best Practices
    <ol>
      <li>Node.js Environment Setup</li>
      <li>Initialize a New Express Project</li>
      <li>Project Structure Best Practices</li>
      <li>Creating a Basic Server with Organized Structure</li>
      <li>Environment Configuration</li>
      <li>Recommended npm Packages for Real-world Projects</li>
    </ol>
  </li>
 <li>3 Express.js Routing - Basics to Advanced
    <ol>
      <li>What is Routing in Express?</li>
      <li>Basic Routing Syntax</li>
      <li>Basic Route Example</li>
      <li>Route Parameters</li>
      <li>Query Parameters</li>
      <li>Handling POST Requests with JSON Body</li>
      <li>Using express.Router()</li>
      <li>Route Chaining</li>
      <li>Route Wildcards</li>
      <li>Catch-all Route (404 Handler)</li>
    </ol>
  </li>
 <li>
     4 Middleware in Express.js - In Depth
     <ol>
         <li>What is Middleware?</li>
         <li>Middleware Syntax</li>
         <li>Types of Middleware</li>
         <li>Application-level Middleware Example</li>
         <li>Route-specific Middleware Example</li>
         <li>Built-in Middleware</li>
         <li>Third-party Middleware Examples</li>
         <li>CORS</li>
         <li>Helmet (Security Headers)</li>
         <li>Router-level Middleware Example</li>
         <li>Error-handling Middleware</li>
         <li>Order of Middleware Matters</li>
         <li>Example: Complete Middleware Flow</li>
     </ol>
  </li>
 <li>
     5 Request and Response Handling in Express.js (In-Depth)
     <ol>
         <li>Understanding the req (Request) Object</li>
         <li>Understanding the res (Response) Object</li>
         <li>Parsing Request Body</li>
         <li>Handling File Uploads</li>
         <li>Sending Files to Client</li>
         <li>Setting Response Headers</li>
         <li>Handling Different Content Types</li>
         <li>Response Status Codes Example</li>
         <li></li>
    </ol>
  </li>
 <li>
     6: RESTful API Development with Express.js - Complete Guide
     <ol>
         <li>What is a RESTful API?</li>
         <li>RESTful HTTP Methods Mapping</li>
         <li>Standard RESTful Endpoint Example for `users`</li>
         <li>Example Project Structure for REST API</li>
         <li>API Example Without Database (In-memory Array)</li>
         <li>API Testing Examples</li>
         <li>Best Practices for REST API in Express</li>
    </ol>
  </li>
 <li>
     7: Authentication and Authorization in Express.js (Complete Guide)
     <ol>
         <li>Difference Between Authentication and Authorization</li>
         <li>Common Authentication Methods</li>
         <li>JWT (JSON Web Token) Authentication</li>
         <li>Role-Based Access Control (RBAC)</li>
         <li>OAuth and Social Login (Concept)</li>
         <li>API Security Best Practices</li>
    </ol>
  </li>
 <li>
     8: Database Integration with Express.js (MongoDB & SQL)
     <ol>
         <li>Database Options with Express</li>
         <li>MongoDB Integration using **Mongoose (ODM)**</li>
         <li>SQL Integration using **Sequelize (ORM)**</li>
         <li>Database Schema Design Tips</li>
         <li>Transactions Handling</li>
         <li>Data Validation and Sanitization</li>
         <li>Goals of Advanced Routing</li>
         <li>Route Versioning (Recommended for Public APIs)</li>
         <li>Nested Routes (Resource Relationships)</li>
         <li>Parameter Middleware</li>
         <li>Error Handling in Routes</li>
         <li>Centralized Error Handler</li>
         <li>Clean RESTful API Design Patterns</li>
         <li>Example of Well-Designed API</li>
         <li>Organizing Routes for Scalability</li>
    </ol>
  </li>
 <li>
     9: Advanced Routing in Express.js (Clean Patterns, Versioning, Error Handling)
     <ol>
         <li>Goals of Advanced Routing</li>
         <li>Route Versioning (Recommended for Public APIs)</li>
         <li>Nested Routes (Resource Relationships)</li>
         <li>Parameter Middleware</li>
         <li>Error Handling in Routes</li>
         <li>Centralized Error Handler</li>
         <li>Clean RESTful API Design Patterns</li>
         <li>Example of Well-Designed API</li>
         <li>Organizing Routes for Scalability</li>
    </ol>
  </li>
 <li>
     10: Data Validation and Error Handling in Express.js (with `express-validator`)
     <ol>
         <li>Why Input Validation is Critical</li>
         <li>Install express-validator</li>
         <li>Basic Validation Example</li>
         <li>Common Validators</li>
         <li>Sanitization Example</li>
         <li>Abstract Error Handler (Reusable Pattern)</li>
         <li>Complex Validation Example</li>
         <li>Global Error Handling (Server-level)</li>
         <li>Response Format Suggestion (Best Practice)</li>
    </ol>
  </li>
 <li>
     11: File Uploads and File Handling in Express.js (Multer, Local & Cloud Storage)
     <ol>
         <li>File Upload Handling in Express</li>
         <li>Install Multer</li>
         <li>Basic File Upload Example</li>
         <li>Upload Multiple Files</li>
         <li>Accepting Specific File Types (Example: Images Only)</li>
         <li>Serving Uploaded Files</li>
         <li>File Validation and Security</li>
         <li>File Upload with Cloud Storage (Example: AWS S3)</li>
         <li>Other Cloud Options</li>
         <li>Example Folder Structure for Uploads</li>
    </ol>
  </li>
 <li>
     12: Performance, Security, and Rate Limiting in Express.js
     <ol>
         <li>Core Focus Areas</li>
         <li>1\. HTTP Security with Helmet</li>
         <li>2\. Enable CORS (Cross-Origin Resource Sharing)</li>
         <li>3\. Rate Limiting (DDoS and Abuse Prevention)</li>
         <li>4\. Compression for Faster Responses</li>
         <li>5\. Prevent HTTP Parameter Pollution</li>
         <li>6\. Sanitize Input to Prevent NoSQL Injection and XSS</li>
         <li>7\. Handling Caching</li>
         <li>8\. Prevent Brute Force on Auth Routes</li>
         <li>9\. Secure Environment Variables</li>
         <li>10\. Best Practice Summary</li>
    </ol>
  </li>
 <li>
     13: Testing Express.js Applications (Unit, Integration, End-to-End)
     <ol>
         <li>Why Testing is Critical</li>
         <li>Testing Types</li>
         <li>Recommended Stack</li>
         <li>Install Testing Libraries</li>
         <li>Configure Jest</li>
         <li>Basic Unit Test Example</li>
         <li>Integration Testing with Express + Supertest</li>
         <li>Testing Routes with CRUD Example</li>
         <li>Mocking Database (MongoDB Example)</li>
         <li>Testing Error Responses</li>
         <li>Running Tests</li>
         <li>Test Folder Structure (Suggested)</li>
         <li>Coverage Reporting</li>
    </ol>
  </li>
 <li>
     14: Deployment and Production for Express.js (PM2, NGINX, Docker, CI/CD)
     <ol>
         <li>1\. Preparing for Production</li>
         <li>2\. Process Management with PM2</li>
         <li>3\. Reverse Proxy with NGINX</li>
         <li>4\. HTTPS with Certbot (Let's Encrypt)</li>
         <li>5\. Dockerize Express App</li>
         <li>6\. Docker Compose Example</li>
         <li>7\. Environment Variables (.env)</li>
         <li>8\. CI/CD Basics Example (GitHub Actions)</li>
         <li>9\. Deployment Checklist</li>
    </ol>
  </li>
 <li>
     15: Real-time Communication in Express.js with Socket.IO (WebSockets)
     <ol>
         <li>Why WebSockets?</li>
         <li>Install Socket.IO</li>
         <li>Server-side Setup</li>
         <li>Client-side Example (HTML + JavaScript)</li>
         <li>Namespaces (For Grouping Different Logics)</li>
         <li>Rooms (For Private Groups)</li>
         <li>Example Room Chat Flow</li>
         <li>Production Considerations</li>
         <li></li>
         <li></li>
         <li></li>
    </ol>
  </li>
 <li>
     16: Express.js Best Practices, Clean Architecture, and Scalable Project Structure
     <ol>
         <li>Goals</li>
         <li>Recommended Folder Structure</li>
         <li>Example File Responsibilities</li>
         <li>Controller Example</li>
         <li>Service Example (Business Logic)</li>
         <li>Central Error Handler</li>
         <li>Async Error Wrapper (DRY Pattern)</li>
         <li>Separate Route File Example</li>
         <li>Config Management Example</li>
         <li>Key Best Practices</li>
         <li>Deployment-Ready Checklist</li>
    </ol>
  </li>
</ol>


## 1. Introduction to Express.js
- What is Express.js?
- Why Use Express.js?
- When to Use Express.js?
- Express.js vs Other Node Frameworks
- Install Node.js (If not installed)
- Installing Express.js
- First Express Server Example
- Basic Project Structure Example

## 2. Setting Up the Development Environment & Project Structure Best Practices
- Node.js Environment Setup
- Initialize a New Express Project
- Project Structure Best Practices
- Creating a Basic Server with Organized Structure
- Environment Configuration
- Recommended npm Packages for Real-world Projects

## 3. Express.js Routing - Basics to Advanced






# Section 1: Introduction to Express.js

## What is Express.js?

Express.js is a minimal and flexible Node.js web application framework that provides a robust set of features to develop web and mobile applications. It is widely used to build REST APIs, web servers, and backend services.

Express is often described as **“Fast, unopinionated, and minimalist”** because it doesn't enforce strict design patterns or structure. You are free to structure your app the way you want.



## Why Use Express.js?

-   **Minimalistic but powerful:** Provides only the core web server functionalities, but can be extended via middleware.
    
-   **Easy to Learn:** Simple API for routing and handling HTTP requests.
    
-   **Massive Ecosystem:** Supports thousands of NPM packages for authentication, validation, logging, etc.
    
-   **Flexible Architecture:** You can design it as monolithic, modular, or microservices.
    
-   **Battle-tested:** Used by companies like IBM, Uber, Accenture, and more.
    



## When to Use Express.js?

-   RESTful API servers.
    
-   Backend for web apps or SPAs (with frontend frameworks like React, Vue, Angular).
    
-   Microservices.
    
-   Prototyping and MVPs.
    
-   Handling server-side logic in full-stack apps.
    




## Express.js vs Other Node Frameworks

| Framework | Type | Features |
| --- | --- | --- |
| **Express.js** | Minimal | Unopinionated, middleware-driven |
| **Koa** | Minimal | Modern, lightweight, async-first |
| **Fastify** | Minimal | High performance, schema-based, faster |
| **NestJS** | Full-fledged | Opinionated, TypeScript-based, modular |
| **Hapi** | Config-driven | Built-in validation, configuration rich |




## Install Node.js (If not installed)

-   Download from: [https://nodejs.org/](https://nodejs.org/)
    

Check version:

```bash
node -v
npm -v
```



## Installing Express.js

1.  Create a new directory:
    

```bash
mkdir express-demo
cd express-demo
```

2.  Initialize the project:
    

```bash
npm init -y
```

3.  Install Express:
    

```bash
npm install express
```



## First Express Server Example

Create a file `app.js`:

```javascript
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('Hello, Express.js!');
});

app.listen(port, () => {
  console.log(`Server is running at http://localhost:${port}`);
});
```

Run the server:

```bash
node app.js
```

Check in browser:

```arduino
http://localhost:3000
```

Output:

```
Hello, Express.js!
```



## Basic Project Structure Example

```pgsql
express-demo/
├── app.js
├── package.json
├── routes/
│   └── user.js
├── controllers/
│   └── userController.js
├── models/
│   └── userModel.js
├── middlewares/
│   └── auth.js
├── public/
│   └── images/
├── views/ (optional for SSR)
└── README.md
```






# Section 2: Setting Up the Development Environment & Project Structure Best Practices


## Node.js Environment Setup

1.  **Install Node.js**
    

-   Download and install from [https://nodejs.org](https://nodejs.org)
    
-   Install the LTS version for stability.
    

2.  **Verify Installation**
    

```bash
node -v
npm -v
```

 

## Initialize a New Express Project

1.  **Create a New Directory**
    

```bash
mkdir express-app
cd express-app
```

2.  **Initialize npm**
    

```bash
npm init -y
```

3.  **Install Express**
    

```bash
npm install express
```

4.  **Install Developer Tools (Optional)**
    

-   `nodemon` for auto-restart on file changes:
    

```bash
npm install --save-dev nodemon
```

-   Update `package.json` for development:
    

```json
"scripts": {
  "start": "node app.js",
  "dev": "nodemon app.js"
}
```

 

## Project Structure Best Practices

### Basic Project Structure (Good for Small Projects)

```java
express-app/
├── app.js
├── package.json
├── routes/
├── public/
└── README.md
```

### Scalable Project Structure (Recommended for Medium to Large Apps)

```bash
express-app/
├── app.js
├── package.json
├── /routes
│   └── userRoutes.js
├── /controllers
│   └── userController.js
├── /models
│   └── userModel.js
├── /middlewares
│   └── authMiddleware.js
├── /services
│   └── emailService.js
├── /config
│   └── dbConfig.js
├── /utils
│   └── errorHandler.js
├── /public
│   └── static assets (images, css)
├── /logs
│   └── log files
└── README.md
```

 

## Creating a Basic Server with Organized Structure

### `app.js`

```javascript
const express = require('express');
const app = express();
const userRoutes = require('./routes/userRoutes');

app.use(express.json()); // to parse JSON body

app.use('/api/users', userRoutes);

const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log(`Server running on http://localhost:${PORT}`);
});
```

### `routes/userRoutes.js`

```javascript
const express = require('express');
const router = express.Router();
const userController = require('../controllers/userController');

router.get('/', userController.getAllUsers);
router.post('/', userController.createUser);

module.exports = router;
```

### `controllers/userController.js`

```javascript
exports.getAllUsers = (req, res) => {
  res.json({ message: 'List of users' });
};

exports.createUser = (req, res) => {
  const { name } = req.body;
  res.json({ message: `User ${name} created` });
};
```

 

## Environment Configuration

-   Install `dotenv` for environment variable management:
    

```bash
npm install dotenv
```

-   Create `.env` file:
    

```ini
PORT=3000
DB_URL=mongodb://localhost:27017/expressdb
JWT_SECRET=yourSecretKey
```

-   Load in `app.js`:
    

```javascript
require('dotenv').config();
```




## Recommended npm Packages for Real-world Projects

| Package | Purpose |
| --- | --- |
| **express** | Core framework |
| **dotenv** | Environment variable management |
| **morgan** | HTTP request logger |
| **cors** | Cross-origin resource sharing |
| **helmet** | Security headers |
| **express-validator** | Validation & sanitization |
| **jsonwebtoken** | JWT authentication |
| **mongoose/sequelize/knex** | Database integration |




 



# Section 3: Express.js Routing - Basics to Advanced

 

## What is Routing in Express?

Routing defines how an application responds to client requests to a particular endpoint (URL) with a specific HTTP method (GET, POST, PUT, DELETE, etc.).

 

## Basic Routing Syntax

```javascript
app.METHOD(PATH, HANDLER)
```

-   **METHOD:** HTTP method (`get`, `post`, `put`, `delete`, etc.)
    
-   **PATH:** Endpoint path
    
-   **HANDLER:** Callback function `(req, res) => {}`
    

 

## Basic Route Example

```javascript
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Home Page');
});

app.post('/submit', (req, res) => {
  res.send('Data submitted');
});

app.listen(3000, () => {
  console.log('Server running on http://localhost:3000');
});
```

 

## Route Parameters

-   Used for dynamic routes.
    

```javascript
app.get('/users/:id', (req, res) => {
  const userId = req.params.id;
  res.send(`User ID: ${userId}`);
});
```

Test URL:

```bash
http://localhost:3000/users/123
```

Response:

```sql
User ID: 123
```

 

## Query Parameters

```javascript
app.get('/search', (req, res) => {
  const keyword = req.query.q;
  res.send(`Search result for: ${keyword}`);
});
```

Test URL:

```bash
http://localhost:3000/search?q=express
```

Response:

```sql
Search result for: express
```

 

## Handling POST Requests with JSON Body

-   Install body parser (built-in from Express 4.16+):
    

```javascript
app.use(express.json());
```

Example:

```javascript
app.post('/users', (req, res) => {
  const { name, email } = req.body;
  res.json({ message: `User ${name} with email ${email} created` });
});
```

Test with Postman:

-   Method: POST
    
-   URL: `http://localhost:3000/users`
    
-   Body: `{"name": "John", "email": "john@example.com"}`
    

 

## Using express.Router()

-   To modularize and split routes.
    

### `routes/userRoutes.js`

```javascript
const express = require('express');
const router = express.Router();
const userController = require('../controllers/userController');

router.get('/', userController.getAllUsers);
router.get('/:id', userController.getUserById);
router.post('/', userController.createUser);
router.put('/:id', userController.updateUser);
router.delete('/:id', userController.deleteUser);

module.exports = router;
```

### `controllers/userController.js`

```javascript
exports.getAllUsers = (req, res) => {
  res.send('Get all users');
};

exports.getUserById = (req, res) => {
  res.send(`Get user with ID ${req.params.id}`);
};

exports.createUser = (req, res) => {
  res.send('Create user');
};

exports.updateUser = (req, res) => {
  res.send(`Update user with ID ${req.params.id}`);
};

exports.deleteUser = (req, res) => {
  res.send(`Delete user with ID ${req.params.id}`);
};
```

### In `app.js`

```javascript
const userRoutes = require('./routes/userRoutes');
app.use('/api/users', userRoutes);
```

Test URLs:

-   `GET /api/users`
    
-   `POST /api/users`
    
-   `GET /api/users/:id`
    
-   `PUT /api/users/:id`
    
-   `DELETE /api/users/:id`
    

 

## Route Chaining

For cleaner route definitions with the same path.

```javascript
router
  .route('/')
  .get(userController.getAllUsers)
  .post(userController.createUser);

router
  .route('/:id')
  .get(userController.getUserById)
  .put(userController.updateUser)
  .delete(userController.deleteUser);
```

 

## Route Wildcards

-   Matches pattern-based routes.
    

```javascript
app.get('/ab*cd', (req, res) => {
  res.send('Matched route: /ab*cd');
});
```

Test URL:

```bash
/abcd
/ab123cd
/abXYZcd
```

All match.

 

## Catch-all Route (404 Handler)

```javascript
app.use((req, res) => {
  res.status(404).send('404 - Not Found');
});
```


 
 


# Section 4: Middleware in Express.js - In Depth

 

## What is Middleware?

-   Middleware are functions that execute **during the request-response cycle** before sending a response to the client.
    
-   Middleware can:
    
    -   Execute any code
        
    -   Modify `req` and `res` objects
        
    -   End the request-response cycle
        
    -   Pass control to the next middleware using `next()`
        

 

## Middleware Syntax

```javascript
function middlewareName(req, res, next) {
  // Code to execute
  next(); // Pass control to next middleware
}
```

Register middleware:

```javascript
app.use(middlewareName);
```

 

## Types of Middleware

1.  **Application-level middleware**  
    Applied to the entire app using `app.use()` or route-specific.
    
2.  **Router-level middleware**  
    Applied to an `express.Router()` instance.
    
3.  **Built-in middleware**  
    Provided by Express (`express.json()`, `express.static()`, etc.).
    
4.  **Third-party middleware**  
    Installed via NPM (`morgan`, `cors`, `helmet`, etc.).
    
5.  **Error-handling middleware**  
    Specifically for handling errors.
    

 

## Application-level Middleware Example

```javascript
app.use((req, res, next) => {
  console.log(`${req.method} ${req.url}`);
  next();
});
```

This logs every incoming request.

 

## Route-specific Middleware Example

```javascript
const checkAuth = (req, res, next) => {
  const authorized = true;
  if (authorized) {
    next();
  } else {
    res.status(401).send('Unauthorized');
  }
};

app.get('/secure', checkAuth, (req, res) => {
  res.send('You have access');
});
```

 

## Built-in Middleware

| Middleware | Purpose |
| --- | --- |
| `express.json()` | Parse JSON bodies |
| `express.urlencoded()` | Parse URL-encoded data |
| `express.static()` | Serve static files |


### Example:

```javascript
app.use(express.json());
app.use(express.static('public'));
```

 

## Third-party Middleware Examples

### Morgan (Logger)

```bash
npm install morgan
```

```javascript
const morgan = require('morgan');
app.use(morgan('dev'));
```

### CORS

```bash
npm install cors
```

```javascript
const cors = require('cors');
app.use(cors());
```

### Helmet (Security Headers)

```bash
npm install helmet
```

```javascript
const helmet = require('helmet');
app.use(helmet());
```

 

## Router-level Middleware Example

### `routes/userRoutes.js`

```javascript
const express = require('express');
const router = express.Router();

router.use((req, res, next) => {
  console.log('Router-specific middleware triggered');
  next();
});

router.get('/', (req, res) => {
  res.send('Users list');
});

module.exports = router;
```

### In `app.js`

```javascript
const userRoutes = require('./routes/userRoutes');
app.use('/api/users', userRoutes);
```

 

## Error-handling Middleware

-   Express recognizes it by having **4 parameters**: `(err, req, res, next)`
    

```javascript
app.use((err, req, res, next) => {
  console.error(err.stack);
  res.status(500).send('Something broke!');
});
```

Throw an error manually:

```javascript
app.get('/error', (req, res) => {
  throw new Error('Manual error');
});
```

 

## Order of Middleware Matters

-   Middleware is executed in the order they are defined.
    

Example:

```javascript
app.use(middlewareA);
app.use('/route', middlewareB);
app.get('/route', handler);
```

Execution order:

```nginx
middlewareA → middlewareB → handler
```

 

## Example: Complete Middleware Flow

```javascript
const express = require('express');
const app = express();
const morgan = require('morgan');

app.use(morgan('dev')); // Logging middleware

app.use(express.json()); // Body parser

// Custom middleware
app.use((req, res, next) => {
  console.log('Custom middleware running');
  next();
});

// Sample route
app.get('/', (req, res) => {
  res.send('Home Route');
});

// Error middleware
app.use((err, req, res, next) => {
  console.error(err);
  res.status(500).send('Error occurred');
});

app.listen(3000, () => {
  console.log('Server running on http://localhost:3000');
});
```

 

    

 


# Section 5: Request and Response Handling in Express.js (In-Depth)

 

## Understanding the `req` (Request) Object

The `req` object represents the **HTTP request** and has properties for the request query string, parameters, body, headers, and more.

### Common `req` Properties:

| Property | Description |
| --- | --- |
| `req.params` | Route parameters `/user/:id` |
| `req.query` | Query string parameters `?search=abc` |
| `req.body` | Request body (POST, PUT) |
| `req.headers` | Request headers |
| `req.method` | HTTP method |
| `req.url` | Original URL |


### Example:

```javascript
app.get('/user/:id', (req, res) => {
  console.log('Params:', req.params);
  console.log('Query:', req.query);
  console.log('Headers:', req.headers);
  res.send('Check console');
});
```

Test URL:

```bash
http://localhost:3000/user/123?name=John
```

Output:

```css
Params: { id: '123' }
Query: { name: 'John' }
```

 

## Understanding the `res` (Response) Object

The `res` object is used to **send a response** back to the client.

### Common `res` Methods:

| Method | Description |
| --- | --- |
| `res.send()` | Send text, JSON, or buffer |
| `res.json()` | Send JSON response |
| `res.status()` | Set HTTP status code |
| `res.redirect()` | Redirect to another URL |
| `res.download()` | Send a file for download |
| `res.sendFile()` | Send a static file |
| `res.set()` | Set response headers |


### Example:

```javascript
app.get('/json', (req, res) => {
  res.status(200).json({ message: 'Hello JSON' });
});
```

 

## Parsing Request Body

From Express 4.16+, `express.json()` and `express.urlencoded()` are built-in middlewares for parsing.

### JSON Body

```javascript
app.use(express.json());
```

Test POST:

```javascript
app.post('/data', (req, res) => {
  console.log(req.body);
  res.json({ received: req.body });
});
```

Send JSON:

```json
{
  "name": "John",
  "email": "john@example.com"
}
```

 

### URL-encoded Form Data

```javascript
app.use(express.urlencoded({ extended: true }));
```

Test POST (from HTML form or Postman `x-www-form-urlencoded`):

```javascript
app.post('/form', (req, res) => {
  console.log(req.body);
  res.send('Form received');
});
```

 

## Handling File Uploads

Install `multer`:

```bash
npm install multer
```

### Basic File Upload Example

```javascript
const express = require('express');
const multer = require('multer');
const app = express();

const storage = multer.diskStorage({
  destination: function (req, file, cb) {
    cb(null, 'uploads/'); // Directory to save files
  },
  filename: function (req, file, cb) {
    cb(null, Date.now() + '-' + file.originalname);
  }
});

const upload = multer({ storage: storage });

app.post('/upload', upload.single('profile'), (req, res) => {
  res.send(`File uploaded: ${req.file.filename}`);
});

app.listen(3000, () => {
  console.log('Server running on http://localhost:3000');
});
```

-   Create folder `uploads/` in your project root.
    
-   Use key `profile` in Postman or HTML form.
    

 

## Sending Files to Client

### Send File for Download

```javascript
app.get('/download', (req, res) => {
  res.download('./uploads/sample.pdf');
});
```

### Send File to Render in Browser

```javascript
app.get('/file', (req, res) => {
  res.sendFile(__dirname + '/uploads/sample.pdf');
});
```

 

## Setting Response Headers

```javascript
app.get('/set-header', (req, res) => {
  res.set('X-Custom-Header', 'ExpressTutorial');
  res.send('Header Set');
});
```

 

## Handling Different Content Types

Example to handle plain text:

```javascript
app.get('/text', (req, res) => {
  res.type('text').send('Plain text response');
});
```

 

## Response Status Codes Example

```javascript
app.get('/unauthorized', (req, res) => {
  res.status(401).json({ error: 'Unauthorized access' });
});
```

 

    

 


# Section 6: RESTful API Development with Express.js - Complete Guide

 

## What is a RESTful API?

REST (Representational State Transfer) is an architectural style for designing APIs based on **HTTP methods** and **stateless communication**. RESTful APIs expose resources through endpoints, supporting CRUD operations.

 
## RESTful HTTP Methods Mapping

| HTTP Method | Operation | Description |
| --- | --- | --- |
| **GET** | Read | Fetch data |
| **POST** | Create | Create new data |
| **PUT** | Update | Update/replace |
| **PATCH** | Partial Update | Partially update data |
| **DELETE** | Delete | Remove data |


 
## Standard RESTful Endpoint Example for `users`

| Method | Endpoint | Action |
| --- | --- | --- |
| GET | `/api/users` | Get all users |
| GET | `/api/users/:id` | Get user by ID |
| POST | `/api/users` | Create a user |
| PUT | `/api/users/:id` | Update entire user |
| PATCH | `/api/users/:id` | Partially update user |
| DELETE | `/api/users/:id` | Delete user |




## Example Project Structure for REST API

```cpp
express-api/
├── app.js
├── routes/
│   └── userRoutes.js
├── controllers/
│   └── userController.js
├── models/
│   └── userModel.js (optional for DB)
└── package.json
```

 

## API Example Without Database (In-memory Array)

### `controllers/userController.js`

```javascript
let users = [
  { id: 1, name: 'John' },
  { id: 2, name: 'Jane' }
];

exports.getAllUsers = (req, res) => {
  res.json(users);
};

exports.getUserById = (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) {
    return res.status(404).json({ error: 'User not found' });
  }
  res.json(user);
};

exports.createUser = (req, res) => {
  const { name } = req.body;
  const newUser = { id: Date.now(), name };
  users.push(newUser);
  res.status(201).json(newUser);
};

exports.updateUser = (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) {
    return res.status(404).json({ error: 'User not found' });
  }
  user.name = req.body.name;
  res.json(user);
};

exports.deleteUser = (req, res) => {
  users = users.filter(u => u.id !== parseInt(req.params.id));
  res.json({ message: 'User deleted' });
};
```

 

### `routes/userRoutes.js`

```javascript
const express = require('express');
const router = express.Router();
const userController = require('../controllers/userController');

router.route('/')
  .get(userController.getAllUsers)
  .post(userController.createUser);

router.route('/:id')
  .get(userController.getUserById)
  .put(userController.updateUser)
  .delete(userController.deleteUser);

module.exports = router;
```

 

### `app.js`

```javascript
const express = require('express');
const app = express();
const userRoutes = require('./routes/userRoutes');

app.use(express.json());
app.use('/api/users', userRoutes);

app.use((req, res) => {
  res.status(404).json({ error: 'Not Found' });
});

const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log(`Server running at http://localhost:${PORT}`);
});
```

 

## API Testing Examples

### Get all users:

```http
GET http://localhost:3000/api/users
```

### Get user by ID:

```http
GET http://localhost:3000/api/users/1
```

### Create user:

```http
POST http://localhost:3000/api/users
Body:
{
  "name": "Alice"
}
```

### Update user:

```http
PUT http://localhost:3000/api/users/1
Body:
{
  "name": "Updated Name"
}
```

### Delete user:

```http
DELETE http://localhost:3000/api/users/1
```

 

## Best Practices for REST API in Express

-   Use nouns, not verbs, in endpoints (`/users` not `/getUsers`).
    
-   Follow HTTP status codes correctly:
    
    -   `200 OK` for success
        
    -   `201 Created` after POST
        
    -   `404 Not Found` if resource doesn't exist
        
    -   `400 Bad Request` for invalid input
        
    -   `500 Internal Server Error` for server issues
        
-   Handle errors gracefully with meaningful messages.
    
-   Validate incoming data (covered in later sections).
    
-   Use consistent response structures.
    
-   Modularize routes and controllers for scalability.
    

 

 


# Section 7: Authentication and Authorization in Express.js (Complete Guide)

 

## Difference Between Authentication and Authorization

| Aspect | Authentication | Authorization |
| --- | --- | --- |
| **Purpose** | Verifies **who you are** | Verifies **what you can access** |
| **Process** | Login, credentials check | Permission check after authentication |
| **Result** | User identity confirmed | Access to resources is granted/denied |




## Common Authentication Methods

-   **Session-based Authentication:** Cookies + Server session.
    
-   **Token-based Authentication (JWT):** Stateless, scalable.
    
-   **OAuth:** Third-party logins (Google, GitHub, etc.).
    

 

## JWT (JSON Web Token) Authentication

### Install Required Packages

```bash
npm install jsonwebtoken bcryptjs
```

 

### How JWT Works

1.  User logs in with credentials.
    
2.  Server verifies and issues a **JWT token**.
    
3.  Client stores token (typically in localStorage or cookies).
    
4.  Client sends token with each request in the header.
    
5.  Server verifies the token to allow access.
    

 

### Example User Authentication Flow (Without Database)

 

### `controllers/authController.js`

```javascript
const jwt = require('jsonwebtoken');
const bcrypt = require('bcryptjs');

const users = [
  { id: 1, username: 'admin', password: bcrypt.hashSync('admin123', 8), role: 'admin' }
];

const JWT_SECRET = 'your_jwt_secret_key';

exports.login = (req, res) => {
  const { username, password } = req.body;
  const user = users.find(u => u.username === username);

  if (!user) {
    return res.status(401).json({ error: 'Invalid username or password' });
  }

  const isPasswordValid = bcrypt.compareSync(password, user.password);
  if (!isPasswordValid) {
    return res.status(401).json({ error: 'Invalid username or password' });
  }

  const token = jwt.sign(
    { id: user.id, username: user.username, role: user.role },
    JWT_SECRET,
    { expiresIn: '1h' }
  );

  res.json({ token });
};

exports.profile = (req, res) => {
  res.json({ user: req.user });
};
```

 

### Middleware: `middlewares/authMiddleware.js`

```javascript
const jwt = require('jsonwebtoken');
const JWT_SECRET = 'your_jwt_secret_key';

module.exports = (req, res, next) => {
  const authHeader = req.headers.authorization;
  if (!authHeader || !authHeader.startsWith('Bearer ')) {
    return res.status(401).json({ error: 'No token provided' });
  }

  const token = authHeader.split(' ')[1];

  try {
    const decoded = jwt.verify(token, JWT_SECRET);
    req.user = decoded; // Attach user data to request
    next();
  } catch (err) {
    return res.status(401).json({ error: 'Invalid or expired token' });
  }
};
```

 

### `routes/authRoutes.js`

```javascript
const express = require('express');
const router = express.Router();
const authController = require('../controllers/authController');
const authMiddleware = require('../middlewares/authMiddleware');

router.post('/login', authController.login);
router.get('/profile', authMiddleware, authController.profile);

module.exports = router;
```

 

### `app.js`

```javascript
const express = require('express');
const app = express();
const authRoutes = require('./routes/authRoutes');

app.use(express.json());
app.use('/api/auth', authRoutes);

const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log(`Server running at http://localhost:${PORT}`);
});
```

 

### Test Authentication Flow

1.  **Login**
    

```http
POST http://localhost:3000/api/auth/login
Body:
{
  "username": "admin",
  "password": "admin123"
}
```

Response:

```json
{
  "token": "eyJhbGciOiJIUzI1NiIs..."
}
```

2.  **Access Profile (Protected Route)**
    

```http
GET http://localhost:3000/api/auth/profile
Headers:
Authorization: Bearer <your_token>
```

 

## Role-Based Access Control (RBAC)

### Add Role Middleware

```javascript
module.exports = function(roles = []) {
  return (req, res, next) => {
    if (!roles.includes(req.user.role)) {
      return res.status(403).json({ error: 'Access forbidden' });
    }
    next();
  };
};
```

### Usage Example:

```javascript
const roleMiddleware = require('./middlewares/roleMiddleware');

router.get('/admin-data', authMiddleware, roleMiddleware(['admin']), (req, res) => {
  res.send('Admin-only data');
});
```

 

## OAuth and Social Login (Concept)

-   Use packages like `passport` and `passport-google-oauth20`.
    
-   Flow:
    
    -   Redirect user to Google login.
        
    -   Google sends back a token.
        
    -   Server verifies token and creates/returns user info.
        

This is an advanced topic covered in-depth in authentication frameworks or the Passport section.

 

## API Security Best Practices

-   Store secrets like JWT secret in `.env` file.
    
-   Always use HTTPS in production.
    
-   Set proper token expiration (`1h`, `15m`, etc.).
    
-   Secure token storage (HTTP-only cookies recommended for web apps).
    
-   Use rate limiting and brute-force protection.
    
-   Use security headers (`helmet` middleware).
    

 
    

 


# Section 8: Database Integration with Express.js (MongoDB & SQL)

 

## Database Options with Express

-   **NoSQL:** MongoDB (document-based)
    
-   **SQL:** MySQL, PostgreSQL, SQLite (relational)
    

Express works with both types using popular Node.js libraries.

 

## MongoDB Integration using **Mongoose (ODM)**

### Install Mongoose

```bash
npm install mongoose
```

 

### Connect MongoDB

```javascript
const mongoose = require('mongoose');

mongoose.connect('mongodb://localhost:27017/expressdb', {
  useNewUrlParser: true,
  useUnifiedTopology: true
}).then(() => {
  console.log('MongoDB connected');
}).catch(err => {
  console.error('MongoDB connection error:', err);
});
```

 

### Define Model

```javascript
const mongoose = require('mongoose');

const userSchema = new mongoose.Schema({
  name: { type: String, required: true },
  email: { type: String, unique: true, required: true },
  createdAt: { type: Date, default: Date.now }
});

const User = mongoose.model('User', userSchema);

module.exports = User;
```

 

### CRUD Example with MongoDB

#### Create User

```javascript
const User = require('../models/User');

exports.createUser = async (req, res) => {
  try {
    const user = await User.create(req.body);
    res.status(201).json(user);
  } catch (err) {
    res.status(400).json({ error: err.message });
  }
};
```

#### Get All Users

```javascript
exports.getAllUsers = async (req, res) => {
  const users = await User.find();
  res.json(users);
};
```

#### Get User by ID

```javascript
exports.getUserById = async (req, res) => {
  const user = await User.findById(req.params.id);
  if (!user) return res.status(404).json({ error: 'User not found' });
  res.json(user);
};
```

#### Update User

```javascript
exports.updateUser = async (req, res) => {
  const user = await User.findByIdAndUpdate(req.params.id, req.body, { new: true });
  if (!user) return res.status(404).json({ error: 'User not found' });
  res.json(user);
};
```

#### Delete User

```javascript
exports.deleteUser = async (req, res) => {
  const user = await User.findByIdAndDelete(req.params.id);
  if (!user) return res.status(404).json({ error: 'User not found' });
  res.json({ message: 'User deleted' });
};
```

 

## SQL Integration using **Sequelize (ORM)**

### Install Sequelize

```bash
npm install sequelize mysql2
```

Or for PostgreSQL:

```bash
npm install sequelize pg pg-hstore
```

 

### Connect SQL Database

```javascript
const { Sequelize, DataTypes } = require('sequelize');

const sequelize = new Sequelize('expressdb', 'root', 'password', {
  host: 'localhost',
  dialect: 'mysql' // Or 'postgres'
});

sequelize.authenticate()
  .then(() => console.log('SQL Database connected'))
  .catch(err => console.error('Connection error:', err));
```

 

### Define Model

```javascript
const User = sequelize.define('User', {
  name: {
    type: DataTypes.STRING,
    allowNull: false
  },
  email: {
    type: DataTypes.STRING,
    unique: true,
    allowNull: false
  }
});

sequelize.sync();

module.exports = User;
```

 

### CRUD Example with SQL

#### Create User

```javascript
exports.createUser = async (req, res) => {
  try {
    const user = await User.create(req.body);
    res.status(201).json(user);
  } catch (err) {
    res.status(400).json({ error: err.message });
  }
};
```

#### Get All Users

```javascript
exports.getAllUsers = async (req, res) => {
  const users = await User.findAll();
  res.json(users);
};
```

#### Get User by ID

```javascript
exports.getUserById = async (req, res) => {
  const user = await User.findByPk(req.params.id);
  if (!user) return res.status(404).json({ error: 'User not found' });
  res.json(user);
};
```

#### Update User

```javascript
exports.updateUser = async (req, res) => {
  const user = await User.findByPk(req.params.id);
  if (!user) return res.status(404).json({ error: 'User not found' });
  await user.update(req.body);
  res.json(user);
};
```

#### Delete User

```javascript
exports.deleteUser = async (req, res) => {
  const user = await User.findByPk(req.params.id);
  if (!user) return res.status(404).json({ error: 'User not found' });
  await user.destroy();
  res.json({ message: 'User deleted' });
};
```

 

## Database Schema Design Tips

-   Keep data normalized in SQL; denormalized (if needed) in MongoDB.
    
-   Add indexes for frequently queried fields (`email`, `username`).
    
-   Use proper data types: `String`, `Number`, `Boolean`, `Date`.
    
-   Handle validations at both DB schema and API validation layer.
    

 

## Transactions Handling

### MongoDB

```javascript
const session = await mongoose.startSession();
session.startTransaction();
try {
  // perform multiple operations
  await session.commitTransaction();
} catch (error) {
  await session.abortTransaction();
}
session.endSession();
```

### Sequelize (SQL)

```javascript
const t = await sequelize.transaction();
try {
  await User.create({ name: 'Alice' }, { transaction: t });
  await t.commit();
} catch (error) {
  await t.rollback();
}
```

 

## Data Validation and Sanitization

-   Schema-level validation using **Mongoose** or **Sequelize**.
    
-   API-level validation using `express-validator` (covered in next sections).
    

 

    
 


# Section 9: Advanced Routing in Express.js (Clean Patterns, Versioning, Error Handling)

 

## Goals of Advanced Routing

-   Design scalable and clean API endpoints.
    
-   Support versioning for API lifecycle management.
    
-   Handle nested resources properly.
    
-   Manage errors systematically.
    

 

## Route Versioning (Recommended for Public APIs)

### URL Versioning Pattern

```javascript
app.use('/api/v1/users', require('./routes/userRoutes'));
app.use('/api/v2/users', require('./routes/userRoutesV2'));
```

### Example:

-   `GET /api/v1/users` — old version
    
-   `GET /api/v2/users` — upgraded version
    

 

## Nested Routes (Resource Relationships)

### Example: Users have Posts

**Endpoints:**

| Method | Endpoint | Action |
| --- | --- | --- |
| GET | `/api/users/:userId/posts` | Get posts for a user |
| POST | `/api/users/:userId/posts` | Create post for a user |
| GET | `/api/users/:userId/posts/:postId` | Get specific post |

 

### Route Example

**`routes/postRoutes.js`**

```javascript
const express = require('express');
const router = express.Router({ mergeParams: true });
const postController = require('../controllers/postController');

router
  .route('/')
  .get(postController.getPosts)
  .post(postController.createPost);

router
  .route('/:postId')
  .get(postController.getPostById);

module.exports = router;
```

 

### Mount Nested Router in User Routes

**`routes/userRoutes.js`**

```javascript
const express = require('express');
const router = express.Router();
const postRoutes = require('./postRoutes');
const userController = require('../controllers/userController');

router.route('/').get(userController.getAllUsers);

router.use('/:userId/posts', postRoutes);

module.exports = router;
```

 

## Parameter Middleware

Automatically handle route parameters.

### Example:

```javascript
router.param('userId', (req, res, next, id) => {
  console.log(`UserID Param detected: ${id}`);
  req.userId = id;
  next();
});
```

Applies to any route containing `:userId`.

 

## Error Handling in Routes

### Async Error Wrapper (Cleaner Code)

```javascript
const asyncHandler = fn => (req, res, next) => {
  Promise.resolve(fn(req, res, next)).catch(next);
};
```

Usage in routes:

```javascript
router.get('/', asyncHandler(async (req, res) => {
  const users = await User.find();
  res.json(users);
}));
```

 

## Centralized Error Handler

```javascript
app.use((err, req, res, next) => {
  console.error(err.stack);
  const status = err.status || 500;
  res.status(status).json({
    error: {
      message: err.message || 'Internal Server Error'
    }
  });
});
```

 

## Clean RESTful API Design Patterns

-   Use plural nouns for resources (`/users`, `/products`).
    
-   Nested resources for relations (`/users/:userId/posts`).
    
-   Avoid verbs in URL (`GET /users` not `/getUsers`).
    
-   Status codes must reflect API response correctly:
    
    -   `200 OK`
        
    -   `201 Created`
        
    -   `204 No Content` for delete
        
    -   `400`/`404`/`500` as applicable
        
-   Version APIs (`/api/v1/`).
    

 

## Example of Well-Designed API

```bash
GET    /api/v1/users
POST   /api/v1/users
GET    /api/v1/users/:id
PUT    /api/v1/users/:id
DELETE /api/v1/users/:id

GET    /api/v1/users/:userId/posts
POST   /api/v1/users/:userId/posts
GET    /api/v1/users/:userId/posts/:postId
```

 

## Organizing Routes for Scalability

Example:

```pgsql
/routes
  └── v1
      ├── userRoutes.js
      └── postRoutes.js
  └── v2
      └── userRoutes.js (new version)
```

In `app.js`:

```javascript
app.use('/api/v1/users', require('./routes/v1/userRoutes'));
app.use('/api/v1/users/:userId/posts', require('./routes/v1/postRoutes'));
app.use('/api/v2/users', require('./routes/v2/userRoutes'));
```

 

 


# Section 10: Data Validation and Error Handling in Express.js (with `express-validator`)

 

## Why Input Validation is Critical

-   Prevent malformed or malicious data from entering the system.
    
-   Improve API reliability and security.
    
-   Return clear error messages to clients.
    

 

## Install express-validator

```bash
npm install express-validator
```

 

## Basic Validation Example

### `routes/userRoutes.js`

```javascript
const express = require('express');
const { body, validationResult } = require('express-validator');
const router = express.Router();
const userController = require('../controllers/userController');

router.post(
  '/',
  [
    body('name').notEmpty().withMessage('Name is required'),
    body('email').isEmail().withMessage('Valid email is required')
  ],
  (req, res) => {
    const errors = validationResult(req);
    if (!errors.isEmpty()) {
      return res.status(400).json({ errors: errors.array() });
    }
    userController.createUser(req, res);
  }
);

module.exports = router;
```

 

### Request Example

**POST `/api/users`**

Body:

```json
{
  "name": "",
  "email": "invalidemail"
}
```

Response:

```json
{
  "errors": [
    { "msg": "Name is required", "param": "name" },
    { "msg": "Valid email is required", "param": "email" }
  ]
}
```

 

## Common Validators

| Validator | Description |
|   |   |
| `body('field').notEmpty()` | Required field |
| `body('email').isEmail()` | Must be valid email |
| `body('age').isInt({ min: 0 })` | Integer, optionally with range |
| `body('url').isURL()` | Valid URL |
| `body('password').isLength({ min: 6 })` | Password length validation |

 

## Sanitization Example

```javascript
body('email').normalizeEmail(),
body('name').trim().escape()
```

-   `trim()`: Remove extra spaces.
    
-   `escape()`: Prevent HTML injection.
    
-   `normalizeEmail()`: Normalize email format.
    

 

## Abstract Error Handler (Reusable Pattern)

### `middlewares/validate.js`

```javascript
const { validationResult } = require('express-validator');

module.exports = (req, res, next) => {
  const errors = validationResult(req);
  if (errors.isEmpty()) return next();

  return res.status(400).json({
    errors: errors.array().map(err => ({
      field: err.param,
      message: err.msg
    }))
  });
};
```

 

### Usage Example

```javascript
const validate = require('../middlewares/validate');

router.post(
  '/',
  [
    body('name').notEmpty().withMessage('Name is required'),
    body('email').isEmail().withMessage('Valid email is required')
  ],
  validate,
  userController.createUser
);
```

 

## Complex Validation Example

```javascript
router.post(
  '/register',
  [
    body('username').isAlphanumeric().withMessage('Username must be alphanumeric'),
    body('password')
      .isLength({ min: 6 })
      .withMessage('Password must be at least 6 characters')
      .matches(/[A-Z]/).withMessage('Password must contain an uppercase letter')
      .matches(/[0-9]/).withMessage('Password must contain a number')
  ],
  validate,
  authController.register
);
```

 

## Global Error Handling (Server-level)

### Example:

```javascript
app.use((err, req, res, next) => {
  console.error(err);
  res.status(err.status || 500).json({
    error: {
      message: err.message || 'Internal Server Error'
    }
  });
});
```

 

## Response Format Suggestion (Best Practice)

```json
{
  "status": "error",
  "errors": [
    { "field": "email", "message": "Valid email is required" }
  ]
}
```

 


 


# Section 11: File Uploads and File Handling in Express.js (Multer, Local & Cloud Storage)

 

## File Upload Handling in Express

### Use **Multer** — a Node.js middleware for handling multipart/form-data, used for file uploads.

 

## Install Multer

```bash
npm install multer
```

 

## Basic File Upload Example

```javascript
const express = require('express');
const multer = require('multer');
const app = express();

const storage = multer.diskStorage({
  destination: function (req, file, cb) {
    cb(null, 'uploads/'); // Save files in uploads/ folder
  },
  filename: function (req, file, cb) {
    const uniqueSuffix = Date.now() + '-' + Math.round(Math.random() * 1E9);
    cb(null, uniqueSuffix + '-' + file.originalname);
  }
});

const upload = multer({ storage: storage });

app.post('/upload', upload.single('file'), (req, res) => {
  res.json({ filename: req.file.filename, path: req.file.path });
});

app.listen(3000, () => {
  console.log('Server running on http://localhost:3000');
});
```

-   `uploads/` folder should exist in the project root.
    

 

## Upload Multiple Files

```javascript
app.post('/upload-multiple', upload.array('files', 5), (req, res) => {
  res.json({ files: req.files });
});
```

 

## Accepting Specific File Types (Example: Images Only)

```javascript
const upload = multer({
  storage: storage,
  fileFilter: function (req, file, cb) {
    const allowedTypes = /jpeg|jpg|png|gif/;
    const isValidExt = allowedTypes.test(file.originalname.toLowerCase());
    const isValidMime = allowedTypes.test(file.mimetype);
    if (isValidExt && isValidMime) {
      cb(null, true);
    } else {
      cb(new Error('Only images are allowed'));
    }
  },
  limits: { fileSize: 2 * 1024 * 1024 } // 2MB limit
});
```

 

## Serving Uploaded Files

### Serve statically:

```javascript
app.use('/uploads', express.static('uploads'));
```

Access file:

```bash
http://localhost:3000/uploads/filename.jpg
```

 

## File Validation and Security

-   Check file types (`fileFilter`).
    
-   Set size limits (`limits`).
    
-   Store files outside `public/` folder to restrict direct access if needed.
    
-   Rename files uniquely to avoid collisions.
    
-   Sanitize file names.
    

 

## File Upload with Cloud Storage (Example: AWS S3)

### Install SDK

```bash
npm install aws-sdk multer-s3
```

### AWS S3 Example Upload

```javascript
const AWS = require('aws-sdk');
const multerS3 = require('multer-s3');

AWS.config.update({
  accessKeyId: 'YOUR_AWS_KEY',
  secretAccessKey: 'YOUR_AWS_SECRET',
  region: 'YOUR_AWS_REGION'
});

const s3 = new AWS.S3();

const upload = multer({
  storage: multerS3({
    s3: s3,
    bucket: 'your-bucket-name',
    acl: 'public-read',
    metadata: (req, file, cb) => {
      cb(null, { fieldName: file.fieldname });
    },
    key: (req, file, cb) => {
      cb(null, Date.now().toString() + '-' + file.originalname);
    }
  })
});
```

### Usage:

```javascript
app.post('/upload', upload.single('file'), (req, res) => {
  res.json({ fileUrl: req.file.location });
});
```

 

## Other Cloud Options

-   **Cloudinary:** For images and videos (with built-in CDN).
    
-   **Firebase Storage:** For serverless environments.
    
-   **Azure Blob Storage / Google Cloud Storage:** Enterprise-grade solutions.
    

 

## Example Folder Structure for Uploads

```bash
/uploads
  ├── user-profiles/
  ├── documents/
  ├── product-images/
```

Organize uploads by type for easy maintenance.

 
    

 


# Section 12: Performance, Security, and Rate Limiting in Express.js

 

## Core Focus Areas

-   Security against attacks (XSS, CSRF, HTTP headers).
    
-   Performance optimization (compression, caching).
    
-   Rate limiting to prevent abuse.
    

 

## 1\. HTTP Security with Helmet

### Install Helmet

```bash
npm install helmet
```

### Usage

```javascript
const helmet = require('helmet');
app.use(helmet());
```

### What Helmet Does

-   Sets HTTP headers like:
    
    -   `Content-Security-Policy`
        
    -   `X-Frame-Options`
        
    -   `Strict-Transport-Security`
        
    -   `X-Content-Type-Options`
        
    -   Prevents clickjacking, XSS, MIME sniffing.
        

 

## 2\. Enable CORS (Cross-Origin Resource Sharing)

### Install CORS

```bash
npm install cors
```

### Basic Usage

```javascript
const cors = require('cors');
app.use(cors());
```

### Configure CORS

```javascript
app.use(cors({
  origin: ['https://yourfrontend.com'],
  methods: ['GET', 'POST', 'PUT', 'DELETE'],
  credentials: true
}));
```

 

## 3\. Rate Limiting (DDoS and Abuse Prevention)

### Install express-rate-limit

```bash
npm install express-rate-limit
```

### Basic Usage

```javascript
const rateLimit = require('express-rate-limit');

const apiLimiter = rateLimit({
  windowMs: 15 * 60 * 1000, // 15 minutes
  max: 100, // limit each IP to 100 requests per window
  message: 'Too many requests from this IP, please try again later.'
});

app.use('/api/', apiLimiter);
```

 

## 4\. Compression for Faster Responses

### Install compression

```bash
npm install compression
```

### Usage

```javascript
const compression = require('compression');
app.use(compression());
```

### What It Does

-   Reduces response body size using Gzip or Brotli.
    
-   Boosts load speed, especially on slow networks.
    

 

## 5\. Prevent HTTP Parameter Pollution

```bash
npm install hpp
```

```javascript
const hpp = require('hpp');
app.use(hpp());
```

-   Prevents HTTP parameter pollution attacks (`/search?sort=asc&sort=desc`).
    

 

## 6\. Sanitize Input to Prevent NoSQL Injection and XSS

### NoSQL Injection Protection

```bash
npm install express-mongo-sanitize
```

```javascript
const mongoSanitize = require('express-mongo-sanitize');
app.use(mongoSanitize());
```

### XSS Protection

```bash
npm install xss-clean
```

```javascript
const xss = require('xss-clean');
app.use(xss());
```

 

## 7\. Handling Caching

-   Use `Cache-Control` headers for static files or API caching.
    

```javascript
app.use('/public', express.static('public', {
  maxAge: '7d', // Cache static files for 7 days
}));
```

 

## 8\. Prevent Brute Force on Auth Routes

Apply tighter rate limits on sensitive routes:

```javascript
const authLimiter = rateLimit({
  windowMs: 10 * 60 * 1000,
  max: 5, // Max 5 attempts in 10 minutes
  message: 'Too many login attempts, try again later.'
});

app.use('/api/auth/login', authLimiter);
```

 

## 9\. Secure Environment Variables

-   Use `.env` to store secrets.
    

```bash
npm install dotenv
```

```javascript
require('dotenv').config();
```

`.env`

```ini
DB_PASSWORD=yourpassword
JWT_SECRET=yourjwtsecret
```

 

## 10\. Best Practice Summary

-   ✅ Use **Helmet** for HTTP header security.
    
-   ✅ Enable **CORS** properly.
    
-   ✅ Use **express-rate-limit** to throttle abusive requests.
    
-   ✅ Apply **compression** for performance.
    
-   ✅ Sanitize inputs using **xss-clean**, **mongo-sanitize**, and **hpp**.
    
-   ✅ Use **.env** for sensitive configurations.
    
-   ✅ Serve static assets with caching when needed.
    


 


# Section 13: Testing Express.js Applications (Unit, Integration, End-to-End)

 

## Why Testing is Critical

-   Ensure reliability.
    
-   Prevent regressions.
    
-   Automate quality checks in CI/CD pipelines.
    

 

## Testing Types

| Type | Focus | Tools |
| --- | --- | --- |
| **Unit Testing** | Single functions/modules | Jest, Mocha |
| **Integration** | API endpoints, DB, services | Supertest + Jest |
| **E2E Testing** | Full app workflow | Cypress, Playwright |

 

## Recommended Stack

-   **Jest** — Test framework and runner.
    
-   **Supertest** — HTTP assertions for Express.
    
-   **Mock Libraries** — e.g., jest-mock, mockingoose (MongoDB).
    

 

## Install Testing Libraries

```bash
npm install --save-dev jest supertest
```

 

## Configure Jest

Add in `package.json`:

```json
"scripts": {
  "test": "jest"
}
```

Or create `jest.config.js`:

```javascript
module.exports = {
  testEnvironment: 'node'
};
```

 

## Basic Unit Test Example

### Test a Helper Function

**`utils/math.js`**

```javascript
function add(a, b) {
  return a + b;
}
module.exports = { add };
```

**`tests/math.test.js`**

```javascript
const { add } = require('../utils/math');

test('adds 1 + 2 equals 3', () => {
  expect(add(1, 2)).toBe(3);
});
```

Run:

```bash
npm test
```

 

## Integration Testing with Express + Supertest

### Test an API Route

**`app.js`**

```javascript
const express = require('express');
const app = express();
app.use(express.json());

app.get('/api/ping', (req, res) => {
  res.json({ message: 'pong' });
});

module.exports = app;
```

**`server.js`**

```javascript
const app = require('./app');
app.listen(3000, () => console.log('Server running'));
```

 

### Test File

**`tests/app.test.js`**

```javascript
const request = require('supertest');
const app = require('../app');

describe('Ping Route', () => {
  it('should respond with pong', async () => {
    const res = await request(app).get('/api/ping');
    expect(res.statusCode).toEqual(200);
    expect(res.body).toHaveProperty('message', 'pong');
  });
});
```

 

## Testing Routes with CRUD Example

**Test POST + GET User**

```javascript
describe('User API', () => {
  it('should create a user', async () => {
    const res = await request(app)
      .post('/api/users')
      .send({ name: 'John', email: 'john@example.com' });

    expect(res.statusCode).toBe(201);
    expect(res.body).toHaveProperty('name', 'John');
  });

  it('should fetch users', async () => {
    const res = await request(app).get('/api/users');
    expect(res.statusCode).toBe(200);
    expect(Array.isArray(res.body)).toBeTruthy();
  });
});
```

 

## Mocking Database (MongoDB Example)

### Install

```bash
npm install --save-dev mockingoose
```

### Example

```javascript
const mockingoose = require('mockingoose');
const User = require('../models/User');

it('should mock User.find()', async () => {
  mockingoose(User).toReturn([{ name: 'Test' }], 'find');

  const res = await request(app).get('/api/users');
  expect(res.body[0].name).toBe('Test');
});
```

 

## Testing Error Responses

```javascript
it('should return 400 if invalid input', async () => {
  const res = await request(app)
    .post('/api/users')
    .send({ email: 'not-an-email' });

  expect(res.statusCode).toBe(400);
  expect(res.body.errors).toBeDefined();
});
```

 

## Running Tests

```bash
npm test
```

or

```bash
npx jest
```

 

## Test Folder Structure (Suggested)

```bash
/tests
  ├── app.test.js
  ├── users.test.js
  └── utils.test.js
```

 

## Coverage Reporting

Run with:

```bash
npx jest --coverage
```

Output:

```arduino
File         | % Stmts | % Branch | % Funcs | % Lines
utils/math.js|   100   |    100   |   100   |   100
```

 


 


# Section 14: Deployment and Production for Express.js (PM2, NGINX, Docker, CI/CD)

 

## 1\. Preparing for Production

-   Use `.env` files for sensitive configs.
    
-   Avoid hardcoding ports, DB URIs, secrets.
    
-   Enable production middleware:
    
    -   `helmet`, `compression`, `cors`, `rate-limit`.
        

 

## 2\. Process Management with PM2

### Install PM2 Globally

```bash
npm install -g pm2
```

### Run App with PM2

```bash
pm2 start app.js --name="express-app"
```

### Common PM2 Commands

```bash
pm2 list                   # Show running apps
pm2 stop express-app       # Stop app
pm2 restart express-app    # Restart app
pm2 logs express-app       # View logs
pm2 delete express-app     # Delete app
```

### Auto-start on Server Boot

```bash
pm2 startup
pm2 save
```

 

## 3\. Reverse Proxy with NGINX

### Basic NGINX Config

```nginx
server {
    listen 80;
    server_name yourdomain.com;

    location / {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
}
```

### Steps

-   Install NGINX:
    

```bash
sudo apt install nginx
```

-   Add config to `/etc/nginx/sites-available/yourdomain.com`.
    
-   Symlink:
    

```bash
sudo ln -s /etc/nginx/sites-available/yourdomain.com /etc/nginx/sites-enabled/
```

-   Reload NGINX:
    

```bash
sudo nginx -t
sudo systemctl reload nginx
```

 

## 4\. HTTPS with Certbot (Let's Encrypt)

```bash
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx -d yourdomain.com
```

Auto-renew:

```bash
sudo certbot renew --dry-run
```

 

## 5\. Dockerize Express App

### `Dockerfile`

```dockerfile
FROM node:18-alpine

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install --production

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]
```

### Build and Run

```bash
docker build -t express-app .
docker run -p 3000:3000 express-app
```

 

## 6\. Docker Compose Example

```yaml
version: '3'
services:
  app:
    build: .
    ports:
      - "3000:3000"
    env_file:
      - .env
```

Run:

```bash
docker-compose up --build
```

 

## 7\. Environment Variables (.env)

```dotenv
PORT=3000
DB_URI=mongodb://...
JWT_SECRET=...
NODE_ENV=production
```

Load with:

```javascript
require('dotenv').config();
```

 

## 8\. CI/CD Basics Example (GitHub Actions)

### `.github/workflows/deploy.yml`

```yaml
name: CI/CD Pipeline

on:
  push:
    branches: [ main ]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v3

      - name: Setup Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '18'

      - name: Install dependencies
        run: npm install

      - name: Run tests
        run: npm test

      - name: Deploy to server
        uses: appleboy/ssh-action@master
        with:
          host: ${{ secrets.SERVER_HOST }}
          username: ${{ secrets.SERVER_USER }}
          key: ${{ secrets.SERVER_SSH_KEY }}
          script: |
            cd /var/www/express-app
            git pull
            npm install --production
            pm2 restart express-app
```

 

## 9\. Deployment Checklist

-   ✅ Environment variables configured.
    
-   ✅ Enable rate limiting, helmet, compression.
    
-   ✅ Use NGINX for reverse proxy + HTTPS.
    
-   ✅ Use PM2 or Docker for process management.
    
-   ✅ Configure CI/CD for auto-deployment.
    
    

 


# Section 15: Real-time Communication in Express.js with Socket.IO (WebSockets)

 

## Why WebSockets?

-   For real-time bidirectional communication.
    
-   Use cases:
    
    -   Chat apps
        
    -   Notifications
        
    -   Live updates
        
    -   IoT streams
        
    -   Multiplayer games
        

 

## Install Socket.IO

```bash
npm install socket.io
```

 

## Server-side Setup

```javascript
const express = require('express');
const http = require('http');
const { Server } = require('socket.io');

const app = express();
const server = http.createServer(app);

const io = new Server(server, {
  cors: {
    origin: '*', // Change this to your frontend origin in production
    methods: ['GET', 'POST']
  }
});

io.on('connection', (socket) => {
  console.log('New client connected:', socket.id);

  socket.on('message', (data) => {
    console.log('Message from client:', data);
    io.emit('message', data); // Broadcast to all clients
  });

  socket.on('disconnect', () => {
    console.log('Client disconnected:', socket.id);
  });
});

app.get('/', (req, res) => {
  res.send('WebSocket server running');
});

server.listen(3000, () => {
  console.log('Server listening on http://localhost:3000');
});
```

 

## Client-side Example (HTML + JavaScript)

```html
<!DOCTYPE html>
<html>
<head>
  <title>Socket.IO Client</title>
</head>
<body>
  <h1>Socket.IO Test</h1>
  <input id="msgInput" placeholder="Type a message..." />
  <button onclick="sendMessage()">Send</button>
  <ul id="messages"></ul>

  <script src="https://cdn.socket.io/4.5.4/socket.io.min.js"></script>
  <script>
    const socket = io('http://localhost:3000');

    socket.on('connect', () => {
      console.log('Connected as', socket.id);
    });

    socket.on('message', (msg) => {
      const li = document.createElement('li');
      li.innerText = msg;
      document.getElementById('messages').appendChild(li);
    });

    function sendMessage() {
      const input = document.getElementById('msgInput');
      const msg = input.value;
      socket.emit('message', msg);
      input.value = '';
    }
  </script>
</body>
</html>
```

 

## Namespaces (For Grouping Different Logics)

```javascript
const chatNamespace = io.of('/chat');

chatNamespace.on('connection', (socket) => {
  console.log('Chat client connected:', socket.id);
});
```

Client connects via:

```javascript
const socket = io('http://localhost:3000/chat');
```

 

## Rooms (For Private Groups)

```javascript
io.on('connection', (socket) => {
  socket.on('joinRoom', (room) => {
    socket.join(room);
  });

  socket.on('message', ({ room, message }) => {
    io.to(room).emit('message', message);
  });
});
```

 

## Example Room Chat Flow

1.  User joins room `room123`:
    

```javascript
socket.emit('joinRoom', 'room123');
```

2.  Send message to that room:
    

```javascript
socket.emit('message', { room: 'room123', message: 'Hello group' });
```

3.  All users in `room123` receive:
    

```javascript
socket.on('message', (msg) => {
  console.log('Room message:', msg);
});
```

 

## Production Considerations

-   Use Redis adapter for scaling sockets across multiple servers.
    

```bash
npm install socket.io-redis
```

-   Secure WebSocket with HTTPS.
    
-   Handle reconnections and errors gracefully.
    



 


# Section 16: Express.js Best Practices, Clean Architecture, and Scalable Project Structure

 

## Goals

-   Build scalable, maintainable, and production-ready Express apps.
    
-   Implement Clean Code and SOLID principles.
    
-   Decouple business logic from infrastructure (DB, framework).
    

 

## Recommended Folder Structure

```bash
/src
 ├── config/         # Configurations (DB, CORS, etc.)
 ├── controllers/    # Request handlers
 ├── models/         # DB models (Mongoose, Sequelize, etc.)
 ├── routes/         # Route definitions
 ├── services/       # Business logic layer
 ├── middlewares/    # Auth, error handling, validators
 ├── utils/          # Helpers, utilities, constants
 ├── jobs/           # Cron jobs, background tasks
 ├── app.js          # App setup
 └── server.js       # Server start file
```

 

## Example File Responsibilities

| Folder/File | Responsibility |
|   |   |
| `/config/` | DB, environment, CORS, 3rd party configs |
| `/controllers/` | HTTP request handling |
| `/models/` | Schema definitions (MongoDB, SQL) |
| `/routes/` | API endpoints |
| `/services/` | Business logic (decoupled from controllers) |
| `/middlewares/` | Error handling, auth, validation |
| `/utils/` | Common functions, constants |
| `/jobs/` | Scheduled tasks (e.g., node-cron) |

 

## Controller Example

```javascript
const userService = require('../services/userService');

exports.getUsers = async (req, res, next) => {
  try {
    const users = await userService.getAllUsers();
    res.json(users);
  } catch (err) {
    next(err);
  }
};
```

 

## Service Example (Business Logic)

```javascript
const User = require('../models/User');

exports.getAllUsers = async () => {
  return await User.find();
};
```

 

## Central Error Handler

**`middlewares/errorHandler.js`**

```javascript
module.exports = (err, req, res, next) => {
  console.error(err);
  const status = err.statusCode || 500;
  res.status(status).json({
    error: {
      message: err.message || 'Internal Server Error'
    }
  });
};
```

In `app.js`:

```javascript
const errorHandler = require('./middlewares/errorHandler');
app.use(errorHandler);
```



## Async Error Wrapper (DRY Pattern)

```javascript
const asyncHandler = fn => (req, res, next) =>
  Promise.resolve(fn(req, res, next)).catch(next);
```



## Separate Route File Example

**`routes/userRoutes.js`**

```javascript
const express = require('express');
const router = express.Router();
const userController = require('../controllers/userController');
const asyncHandler = require('../middlewares/asyncHandler');

router.get('/', asyncHandler(userController.getUsers));

module.exports = router;
```

In `app.js`:

```javascript
const userRoutes = require('./routes/userRoutes');
app.use('/api/v1/users', userRoutes);
```


## Config Management Example

**`config/db.js`**

```javascript
const mongoose = require('mongoose');

const connectDB = async () => {
  await mongoose.connect(process.env.MONGO_URI);
  console.log('MongoDB connected');
};

module.exports = connectDB;
```

In `server.js`:

```javascript
require('dotenv').config();
const connectDB = require('./src/config/db');
connectDB();
```


## Key Best Practices

### ✔ Folder Structure

-   Keep `controllers`, `services`, `routes` isolated.
    

### ✔ Environment Config

-   Use `dotenv` with `/config` management.
    

### ✔ Error Handling

-   Centralized middleware-based error management.
    

### ✔ Async/Await Everywhere

-   No `.then().catch()` in modern code.
    

### ✔ Validation

-   Use `express-validator` in middleware.
    

### ✔ Security

-   Apply helmet, CORS, rate limiting, sanitize inputs.
    

### ✔ Logging

-   Use `winston` or `pino` for logs instead of `console.log`.
    

### ✔ Linting

-   Enforce code style with ESLint + Prettier.
    

### ✔ Testing

-   Separate unit and integration tests with Jest + Supertest.
    


## Extended Architecture Option

For very large apps:

-   Apply **Clean Architecture** or **Hexagonal Architecture**.
    
-   Example Layers:
    
    -   **Entity Layer:** Pure business models (no DB/framework).
        
    -   **Use Cases / Service Layer:** Business rules.
        
    -   **Interface Layer:** HTTP, CLI, WebSocket handlers.
        
    -   **Infrastructure Layer:** DB, external APIs, file systems.
        


## Deployment-Ready Checklist

-   ✅ Secure with CORS, Helmet, Rate-Limit.
    
-   ✅ Error handling and logging in place.
    
-   ✅ Env vars via `.env`.
    
-   ✅ Health-check endpoint (`/api/health`).
    
-   ✅ Proper CI/CD pipeline.
    
-   ✅ PM2 or Docker for process management.
    

    
