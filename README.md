This project has been transitioned from a university enterprise account to a personal account to ensure its ongoing development and accessibility.
# AgileHub

AgileHub is an advanced project management tool tailored for agile teams who leverage the scrum methodology to efficiently organize and prioritize their projects. This project represents the culmination of learnings from the React course, a component of the JS Web Module.

## Table of Contents
1. [Technology Stack](#technology-stack)
2. [Application Configuration](#application-configuration)
3. [Credits](#credits)

## Technology Stack

AgileHub is built using a robust set of technologies:

### Front End:
- **React:** A JavaScript library for building user interfaces.
- **React Router:** Declarative routing for React apps.
- **@microsoft/signalr:** Adds real-time web functionality.
- **Tailwind CSS:** A utility-first CSS framework for rapid UI development.
- **Cloudinary:** Cloud service for image and video management.

### Back End:
- **ASP.NET Core 3.1:** A framework for building web applications.
- **Entity Framework Core 3.1:** An ORM for .NET.
- **SQL Server:** A relational database management system.
- **Redis:** An in-memory data structure store, used as a database, cache, and message broker.
- **SignalR:** A library for adding real-time web functionality.
- **Swagger:** A tool for documenting APIs.


## Application Configuration

### Front End:
- **Dependencies Installation:** Run `yarn install` or `npm install` to install all necessary dependencies.
- **Tailwind CSS Setup:** Execute `npx tailwindcss init` to generate a `tailwind.config.js` file. Move this file to the `src` folder for proper integration.
- **Cloudinary Integration:** Create a `.env` file at the project root and define variables for Cloudinary's `cloudName` and `uploadPreset` with the `REACT_APP_` prefix (e.g., `REACT_APP_CLOUD_NAME` and `REACT_APP_CLOUD_PRESET`).

### Back End:
- **Database Connection:** Ensure the connection string in `appsettings.json` is correct. For non-SQLEXPRESS users, replace `Server=.\\SQLEXPRESS` with `Server=.;`.
- **Redis Dependency:** AgileSprint requires a running Redis server for caching. Ensure Redis is installed and configured.

## Credits

AgileSprint utilizes the Watermelon Illustrations Pack from [DrawKit](https://www.drawkit.io/) for its vibrant and engaging visuals.
