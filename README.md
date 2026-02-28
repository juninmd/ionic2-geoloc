```markdown
# Ionic2-Geolocation

**Description:** Ionic2-Geolocation is an example project demonstrating the tracking of GPS coordinates and sending the data to a web service.

**Installation:**

1.  Clone the repository: `git clone https://github.com/your-username/ionic2-geolocation.git`
2.  Install dependencies: `npm install`
3.  Configure TypeScript: `npm install --save-dev typescript`
4.  Configure Ionic CLI: `ionic start --type=production`

**Usage:**

1.  Create a new project: `ionic init`
2.  Configure the project with the following:
    *   `config.xml`:  Modify the `location` settings to specify the desired GPS coordinates.
    *   `ionic.config.json`:  Add a `server` URL to the `locations` section to connect to a backend service.
    *   `src/app.component.ts`:  This is the main component responsible for displaying the GPS coordinates.  Ensure the `location` variable is properly initialized with the sensor.
3.  Run the app: `ionic run`
4.  Test the app: Open the app in a web browser to view the GPS location.

**Files:**

*   `resources/`: Contains all resources for the application.
*   `src/app.component.ts`:  Main component for displaying the location.
*   `src/app.component.html`:  HTML template for the location display.
*   `src/app.component.json`:  Configuration for the location sensor.
*   `src/config.xml`: Config file for the location server.
*   `src/ionic.config.json`: Ionic configuration file.
*   `src/tslint.json`: TypeScript linting configuration.
*   `tsconfig.json`: TypeScript configuration.
*   `bower_components`:  (Not used in this example).
*   `angular-cli.json`:  Angular CLI configuration.
*   `package.json`:  Project dependencies and metadata.
*   `readme.md`:  Project documentation.
*   `resource`:  Configuration files.
```