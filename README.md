# Buyreverie.in

## How to develop (Local set up)

### Prerequisites
1. [Node.js v16+](https://docs.medusajs.com/development/backend/prepare-environment#nodejs)

2. [Git](https://docs.medusajs.com/development/backend/prepare-environment#git)
3. [PostgreSQL](https://docs.medusajs.com/development/backend/prepare-environment#postgresql)
4. **[OPTIONAL]** if you don't want to install PostgresSQL on local machine, Install [docker-desktop](https://docs.docker.com/desktop/install/mac-install/) and navigate to `devops` folder using terminal and run the command ` docker-compose --project-name reverie up --wait`

### How to start backend and storefront
1. **[One Time Setup]** 
   1. Naviagate to `reverie` and `reverie-storefront` folders using terminal and run the command `npm install`
2. **[Subsequent runs]**
   1. Naviagate to `reverie` and `reverie-storefront` folders using terminal and run the command `npm run dev`

## Local Development guidelines
1. Create a new branch using the name of the feature
2. Checkout your branch
3. Once you're done with development, push your code to your remote issue branch and rise a PR against main branch for review.
4. **Never ever commit any password in this repository.**
