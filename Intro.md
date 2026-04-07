# Web Technologies - Complete Overview

Web technologies are the standards, tools, and frameworks used to build websites and web applications. They include everything from page structure and styling to server logic, databases, security, and deployment.

## 1. Internet and Web Basics

### What is the Web?
- The Internet is the global network of connected devices.
- The Web (World Wide Web) is a service that runs on the Internet.
- Web resources are identified by URLs and transferred using HTTP/HTTPS.

### URL (Uniform Resource Locator)
A URL points to a resource on the web.

Example:
`https://www.example.com:443/products?id=10#reviews`

Parts:
- Protocol (scheme): `https`
- Domain (host): `www.example.com`
- Port: `443`
- Path: `/products`
- Query string: `?id=10`
- Fragment: `#reviews`

### Client-Server Model
- Client: Browser, mobile app, or frontend.
- Server: Handles requests, runs business logic, sends responses.
- Request-response cycle is the core of web communication.

## 2. Core Frontend Technologies

### HTML (HyperText Markup Language)
- Defines page structure and semantics.
- Current standard: HTML5.
- Common semantic tags: `header`, `nav`, `main`, `section`, `article`, `footer`.
- Supports forms, media, tables, metadata, accessibility attributes.

### CSS (Cascading Style Sheets)
- Styles web pages (colors, layout, spacing, typography, animations).
- Key concepts: selectors, box model, specificity, cascade.
- Layout systems: Flexbox and CSS Grid.
- Responsive design tools: media queries, relative units (`%`, `em`, `rem`, `vw`, `vh`).

### JavaScript
- Adds interactivity and dynamic behavior.
- Runs in browser and on servers (Node.js).
- Core topics: variables, functions, objects, DOM, events, async/await, promises.

### Browser APIs
- DOM API (manipulate HTML elements)
- Fetch API (HTTP requests)
- LocalStorage/SessionStorage
- Geolocation, Canvas, Web Audio, WebRTC, Notifications

## 3. Frontend Frameworks and Build Tools

### Popular Frameworks/Libraries
- React
- Angular
- Vue
- Svelte

### Styling Approaches
- Plain CSS
- Sass/SCSS
- CSS-in-JS
- Utility-first CSS (Tailwind CSS)

### Build and Development Tools
- npm / pnpm / yarn (package managers)
- Vite, Webpack, Parcel (bundlers/build tools)
- Babel (transpilation)
- TypeScript (typed JavaScript)
- ESLint and Prettier (linting/formatting)

## 4. Backend Technologies

### Server-Side Languages and Platforms
- JavaScript/TypeScript: Node.js, Deno
- Python: Django, Flask, FastAPI
- Java: Spring Boot
- C#: ASP.NET Core
- PHP: Laravel
- Ruby: Ruby on Rails
- Go: Gin, Fiber

### Backend Responsibilities
- Authentication and authorization
- Business logic
- Database operations
- API creation
- Server-side validation
- Caching and background jobs

## 5. Web Protocols and Communication

### HTTP/HTTPS
- HTTP methods: GET, POST, PUT, PATCH, DELETE
- Status codes:
	- 2xx success (200, 201)
	- 3xx redirects (301, 302)
	- 4xx client errors (400, 401, 403, 404)
	- 5xx server errors (500, 502, 503)
- HTTPS = HTTP over TLS encryption.

### Common Data Formats
- JSON (most common for APIs)
- XML
- Form data (application/x-www-form-urlencoded, multipart/form-data)

### Real-Time Communication
- WebSocket (full-duplex communication)
- Server-Sent Events (SSE)
- WebRTC (peer-to-peer media and data)

## 6. Databases and Storage

### Relational Databases (SQL)
- MySQL
- PostgreSQL
- Microsoft SQL Server
- SQLite

### NoSQL Databases
- MongoDB (document)
- Redis (key-value, caching)
- Cassandra (wide-column)
- Neo4j (graph)

### Data Access Layers
- ORM/ODM tools (Prisma, Sequelize, TypeORM, Mongoose, Hibernate)
- Migrations for schema changes

## 7. APIs and Architecture

### API Styles
- REST (resource-based, HTTP methods)
- GraphQL (client-controlled queries)
- gRPC (high-performance RPC)

### Architecture Patterns
- Monolithic applications
- Microservices
- Serverless (Functions-as-a-Service)
- JAMstack (JavaScript, APIs, Markup)

## 8. Authentication and Security

### Authentication Methods
- Session-based auth
- Token-based auth (JWT)
- OAuth 2.0 / OpenID Connect
- Single Sign-On (SSO)

### Security Best Practices
- Use HTTPS everywhere
- Validate and sanitize input
- Protect against XSS, CSRF, SQL Injection
- Store passwords with strong hashing (bcrypt/argon2)
- Use secure headers (CSP, HSTS, X-Frame-Options)
- Apply least privilege access

## 9. Performance and Optimization

### Frontend Performance
- Minify and bundle assets
- Code splitting and lazy loading
- Optimize images (modern formats, compression)
- Use browser caching and CDN
- Reduce render-blocking resources

### Backend Performance
- Database indexing
- Query optimization
- Caching (Redis, in-memory)
- Load balancing
- Asynchronous processing and queues

### Performance Metrics
- Core Web Vitals:
	- LCP (Largest Contentful Paint)
	- INP (Interaction to Next Paint)
	- CLS (Cumulative Layout Shift)

## 10. DevOps, Deployment, and Hosting

### Version Control and Collaboration
- Git and GitHub/GitLab/Bitbucket
- Branching, pull requests, code reviews

### CI/CD
- Automated build, test, and deployment pipelines
- Tools: GitHub Actions, GitLab CI, Jenkins, Azure DevOps

### Deployment Platforms
- Traditional servers (Nginx, Apache)
- Cloud providers (AWS, Azure, GCP)
- Platform services (Vercel, Netlify, Render, Heroku)
- Containers and orchestration (Docker, Kubernetes)

## 11. Testing and Quality

### Testing Types
- Unit testing
- Integration testing
- End-to-end (E2E) testing

### Common Tools
- Jest, Vitest, Mocha
- Cypress, Playwright, Selenium
- Postman/Newman for API testing

## 12. Accessibility and SEO

### Accessibility (a11y)
- Use semantic HTML
- Keyboard navigation support
- Proper labels for form inputs
- Sufficient color contrast
- ARIA only when necessary

### SEO (Search Engine Optimization)
- Proper page titles and meta descriptions
- Semantic structure and heading order
- Structured data (schema.org)
- Fast load times and mobile-friendly design

## 13. Modern Trends in Web Technology

- Progressive Web Apps (PWA)
- Static Site Generation (SSG)
- Server-Side Rendering (SSR)
- Edge computing and edge functions
- AI-powered web applications
- WebAssembly (Wasm)

## 14. Quick Summary

At minimum, modern web development usually includes:
- HTML + CSS + JavaScript/TypeScript for frontend
- A backend framework and API
- A database
- Authentication and security controls
- Testing + CI/CD
- Cloud deployment and monitoring

Mastering web technologies means understanding both fundamentals (HTML/CSS/HTTP) and modern tools (frameworks, APIs, cloud, and DevOps).