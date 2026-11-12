# 🖥️ Web Application for Computer Hardware Sales

This project is a full-stack web application developed as part of a university course assignment. It enables browsing and purchasing of computer hardware through a modern, user-friendly interface. The app includes user registration, authentication, product management, and order tracking.

## Technologies Used

- **Backend**: [NestJS](https://nestjs.com/) (Node.js framework)
- **Frontend**: [React](https://reactjs.org/)
- **Database**: MySQL
- **Language**: TypeScript
- **API Testing**: Postman

## Project Structure


<!-- project-tree:start -->
<p>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app" title="hardware-shop-app"><img src=".github/readme-tree/00.svg" alt="hardware-shop-app" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/src" title="src/"><img src=".github/readme-tree/01.svg" alt="src/ — NestJS back end" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/src/main.ts" title="src/main.ts"><img src=".github/readme-tree/02.svg" alt="src/main.ts — bootstrap" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/src/app.module.ts" title="src/app.module.ts"><img src=".github/readme-tree/03.svg" alt="src/app.module.ts — wires TypeORM entities, services and controllers" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/src/controllers/api" title="src/controllers/api/"><img src=".github/readme-tree/04.svg" alt="src/controllers/api/ — REST endpoints: articles, cart, auth, admins" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/src/services" title="src/services/"><img src=".github/readme-tree/05.svg" alt="src/services/ — business logic per domain (incl. order mailer)" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/src/entities" title="src/entities/"><img src=".github/readme-tree/06.svg" alt="src/entities/ — TypeORM entities mapped to MySQL tables" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/src/dtos" title="src/dtos/"><img src=".github/readme-tree/07.svg" alt="src/dtos/ — request bodies per domain" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/src/middlewares/auth.middleware.ts" title="src/middlewares/auth.middleware.ts"><img src=".github/readme-tree/08.svg" alt="src/middlewares/auth.middleware.ts — JWT check on protected routes" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/src/misc" title="src/misc/"><img src=".github/readme-tree/09.svg" alt="src/misc/ — role guard, @AllowToRoles, ApiResponse" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/config" title="config/"><img src=".github/readme-tree/10.svg" alt="config/ — database, JWT, mail and storage settings" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/front-end" title="front-end/"><img src=".github/readme-tree/11.svg" alt="front-end/ — React client (TypeScript)" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/front-end/src/index.tsx" title="front-end/src/index.tsx"><img src=".github/readme-tree/12.svg" alt="front-end/src/index.tsx — client entry point" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/front-end/src/components/App" title="front-end/src/components/App/"><img src=".github/readme-tree/13.svg" alt="front-end/src/components/App/ — root component" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/.DATABASE/aplikacija.sql" title=".DATABASE/aplikacija.sql"><img src=".github/readme-tree/14.svg" alt=".DATABASE/aplikacija.sql — MySQL schema and sample data" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/.POSTMAN/aplikacija_test_postman.json" title=".POSTMAN/aplikacija_test_postman.json"><img src=".github/readme-tree/15.svg" alt=".POSTMAN/aplikacija_test_postman.json — Postman collection for the API" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/tree/master/.DOCUMENTATION" title=".DOCUMENTATION/"><img src=".github/readme-tree/16.svg" alt=".DOCUMENTATION/ — documentation, presentation, Figma link" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/package.json" title="package.json"><img src=".github/readme-tree/17.svg" alt="package.json — Nest scripts and dependencies" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/ormconfig.json" title="ormconfig.json"><img src=".github/readme-tree/18.svg" alt="ormconfig.json — TypeORM connection" align="top"></a><br>
<a href="https://github.com/LazarDavidovic98/hardware-shop-app/blob/master/tsconfig.json" title="tsconfig.json"><img src=".github/readme-tree/19.svg" alt="tsconfig.json" align="top"></a><br>
</p>

<sub>Every row is a link to that file or folder on GitHub. Purple: folders, green: source code, grey: configuration, data and docs.</sub>
<!-- project-tree:end -->

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone ovde ide SSH
   cd ovde_ide_naziv_aplikacije
2. **Install dependencies**:   
   npm install
3. **Import the database**:
- Use MySQL tools
- Create a database, e.g., aplikacija
- Import the aplikacija.sql file from .DATABASE/
4. **Run the app**:
   npm run start  
The server should now be running on http://localhost:3000.

**Detailed documentation is available here**: [Documentation](.DOCUMENTATION/Documentation.md)  
**You can also view the project presentation**: [Presentation](.DOCUMENTATION/Presentation.pdf)  



