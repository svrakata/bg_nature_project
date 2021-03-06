# BULGARIAN NATURE PROJECT

## Description
Presantational web platform with overview of the bulgarian nature

## Tech stack:
* Typescript
* ReactJS
* NodeJS (or based on Node server tech)
* MongoDB

## Domain name -- ??

## Design
* Research on other presentational / nature sites - (list examples)
* Informational architecture --> pages, navigation


## Architecture

### Stage 1:

Make server / login logic / db layer / and basic client

bgnature.com
cms.bgnature.com

* Basic server with NodeJS/Express that will lay the foundation for the api 
* DB: MongoDB --> how to separate sever logic from db logic
* Basic CMS: needs user permissions, interface, data generation logic, rich text editor supporting cyrilic and latin languages.
* Basic client side - separated from the CMS (presentational only)


#### Folder structure
* root
    * backend
    * frontend
        * cms
        * client

## Usage:

Running ```npm run dev``` from the root directory starts the client the cms and the server.

Client port is 3001.  
Cms port is 3002.

You can change the ports in the .env file in the corrensponding folders.

#### Authetification - useful materials:
* [YT video with very good explanation](https://www.youtube.com/watch?v=2PPSXonhIck)
* [github article on JWT expiration](https://gist.github.com/soulmachine/b368ce7292ddd7f91c15accccc02b8df)
* [Token Based Authentication for Single Page Apps](https://stormpath.com/blog/token-auth-spa)

#### Configuration
* [The twelve-factor app config](https://12factor.net/config)