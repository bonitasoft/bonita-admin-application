# Bonita Admin Application

This repository aggregates all the community development artifacts of the Bonita Admin Application

## Build 

Run `./mvnw clean verify` in a terminal. The result of the build is a BOS Archive in the `target` folder.

## Application content

* An application descriptor for the Bonita Admin Application
* The Bonita layout as a development artifact
* The UI Designer pages development artifacts
The application pages that are not designed with the UI Designer are already embedded in the Runtime bundle.

## Customize the theme

In addition to development pages, you may also customize the default Bonita theme just by creating a new Theme in the Studio.
By the default the Bonita theme is used as starting point, so you just have to update the theme id in the application descriptor with your custom theme id.
