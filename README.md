# Threads App Clone

A simplified clone of the Threads app, built using Nuxt 3 Vue.js, Tailwind CSS, Supabase, Prisma, JavaScript, and PWA. This app allows users to log in with GitHub, create posts with or without images, delete posts, and like/unlike posts.


## Table of Contents

- [Installation](#installation)
- [Setup](#setup)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the Threads app clone, follow these steps:

1. Clone the repository using HTTPS:
   ```sh
   git clone https://github.com/pawdgreyt/threads-clone-nuxt3.git

2. Navigate to the project directory:
   ```sh
   cd threads-clone-nuxt3

3. Install the project dependencies using npm:
   ```sh
   npm install

## Setup

Before running the app, you'll need to set up the environment variables. Create a .env file in the root directory of the project and provide the following variables:

- SUPABASE_URL: URL of your Supabase project
- SUPABASE_KEY: API key for your Supabase project
- BUCKET_URL: URL for the storage bucket (for images)
- DATABASE_URL: URL of your database (used by Prisma)

Example .env file:

    ```sh
     SUPABASE_URL=https://your-supabase-url.supabase.co
     SUPABASE_KEY=your-supabase-api-key
     BUCKET_URL=https://your-storage-bucket-url.com
     DATABASE_URL=your-database-url

## Usage
To start the development server and run the Threads app clone, use the following command:
     ```sh
     npm run dev

## Features

- GitHub Login: Users can log in to the app using their GitHub accounts.
- Create Posts: Users can create posts with or without images, sharing their thoughts and ideas.
- Delete Posts: Users have the option to delete their own posts.
- Like and Unlike Posts: Users can like and unlike posts to show appreciation for the content.



