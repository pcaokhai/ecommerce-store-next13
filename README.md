# Multi-store Ecommerce with Dashboard

## Introduction

This is a [nextjs](https://nextjs.org/) 13 based web application that comprises a dashboard backend that allows to manage stores and a frontend to display products for each store

## How to run

You need to install latest [nodejs](https://nodejs.org/en) to run the application

1. clone the project

2. Go to the project folders (ecommerce-admin-api and ecommerce-store), type:

npm install

3. Create .env following the format in .env-sample, add the api keys([nextauth](https://next-auth.js.org/), [cloudinary](https://cloudinary.com/), database url - use [PlanetScale](https://planetscale.com/) for example)

 - to create table, cd to ecommerce-admin-api, then type:
    npx prisma generate
    npx prisma db push

4. Go to the project folders (ecommerce-admin-api for backend and ecommerce-store for frontend), type the following command to run

npm run dev
