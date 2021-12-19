# Dating App

Angular 12 / C# .Net 6 Project.

This project is a social dating application with all of the expected features; User profiles, and editing ability, photo upload, 'liking' system and messaging.

## Requirements

There are a couple of requirements after cloning the repository to get this repo working.

- The client requieres a a server.crt and server.key in a folder named ssl within the client directory. This folder has been exluded from
the git repository and needs to be created by the user.

- The appsettings.json file in the API is also excluded. As this project makes use of the Cloudinary API (https://cloudinary.com/) you will need an account
on that service, and to provide Cloudinary settings in this file. These settings are named as follows: CloudName, ApiKey, ApiSecret. More information can be found
on the Cloudinary website.
