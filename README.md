# microfrontend_host
Frontend Project with Module Federation
This project demonstrates how to use MF to build a modular and scalable frontend application.

Projects Structure
#1
--microfrontend_host
----src
------App.js
------App.css
------index.js
------bootstrap.js
------components
--------Home.jsx
----webpack.config.js
#2
--microfrontend_remote
----src
------App.js
------App.css
------index.js
------bootstrap.js
------components
--------Footer.jsx
--------Header.jsx
----webpack.config.js

Setup
# Install Node.js and npm: 
  Ensure you have Node.js and npm installed on your system.
## Clone the repository:
  Clone this repository in your ocal machine.
### Install dependencies.
  Navigate to the project root directory and run npm install.

Running the Application
# Start the host application:
Navigate to the host directory and run npm start.
# Start the remote application:
Navigate to the remote directory and run npm start.

The host application will load the remote app's components (footer and header) using Module Federation.

