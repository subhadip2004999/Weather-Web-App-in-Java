# Weather Web App in Java

A small Java-based web application that displays weather information. The project includes HTML and JSP files and is intended to be deployed on a Java web container such as Apache Tomcat.

## Contents

- home.html — Landing page / form to enter a city or view weather
- weather.jsp — JSP page that displays weather results
- WEB-INF/ — Web application configuration (web.xml, classes, libraries)
- META-INF/ — Metadata files
- 566396.jpg — Screenshot or image used in the project

## Features

- Simple UI to enter a location and view weather information
- Server-side rendering using JSP

## Requirements

- Java 8 or later
- A Java Servlet container (e.g., Apache Tomcat)
- (Optional) An internet connection if the app fetches external weather data

## Run / Deploy

Option 1 — Deploy on Tomcat (manual):
1. Copy this project directory into Tomcat's `webapps/` folder (or package as a WAR).
2. Start Tomcat (e.g., `bin/startup.sh` or via your OS service manager).
3. Open a browser and visit `http://localhost:8080/<context>/home.html` or the app context you deployed to.

Option 2 — Run from an IDE (Eclipse/IntelliJ):
1. Import the project as a ``Dynamic Web Project`` (Eclipse) or configure as a web application in IntelliJ.
2. Add a Tomcat server configuration and run the project on the server.

## File structure

Placeholders based on repository root:
```
. (project root)
├─ home.html
├─ weather.jsp
├─ WEB-INF/
├─ META-INF/
├─ 566396.jpg
```

## Screenshot

See `566396.jpg` in the repository for a preview of the UI.

## Contributing

Contributions are welcome — open an issue or submit a pull request with improvements or bug fixes.

## Notes

- This README is a general guide. If the project requires specific build steps, libraries, or an external weather API key, add those details to this README or to a separate documentation file.
