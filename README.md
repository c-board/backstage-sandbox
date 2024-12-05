# [Backstage](https://backstage.io)

This repository contains a Backstage application, a platform designed to simplify software development by centralizing tools, services, and documentation into a single, unified interface. This instance is specifically set up to test and demonstrate features, plugins, and integrations of Backstage.


**Overview**


Backstage is an open-source platform for building developer portals. It provides a framework to manage your software ecosystem by combining tools, infrastructure, and documentation into a single, intuitive UI.

This application is tailored for testing and experimenting with Backstage features and plugins, making it a sandbox environment for development and evaluation.

**Features**


    Plugin Testing: Easily integrate and test Backstage plugins.
    Catalog Management: Add, organize, and interact with services, APIs, and components.
    Scaffolding: Experiment with software templates for rapid project creation.
    Custom Integrations: Test integrations with third-party tools and APIs.
    User Management: Simulate user roles and access controls.

**Getting Started**

Prerequisites: Ensure the following tools are installed on your system:

    Node.js (version 16 or higher)
    Yarn (package manager)

**Installation**

Clone the repository:

    git clone git@github.com:c-board/backstage-sandbox.git

Navigate to the project directory:

    cd backstage-sandbox

Install dependencies:

    yarn install

**Running the Application**

Start the development server:

    yarn dev

Access the application at http://localhost:3000.

**Usage**

Testing Plugins

- Create or download a plugin in the plugins folder.
- Register the plugin in app-config.yaml or the plugins.ts file.
- Restart the application and navigate to the plugin's page in the UI.

Adding Entities to the Catalog

- Create an entity YAML file following the Backstage catalog model.
- Add the entity using the Register Entity button in the Catalog section.

Experimenting with Templates

- Modify or add templates in the templates folder.
- Use the Scaffolder UI to create new projects from the templates.

Folder Structure

**backstage-test-app/**
- **app/**: Frontend application code
- **backend/**: Backend services and configurations
- **plugins/**: Custom plugins for testing
- **templates/**: Software scaffolding templates
- **config/**: Application configurations
- **scripts/**: Custom scripts for automation
- **README.md**: Project documentation