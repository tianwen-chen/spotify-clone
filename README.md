# Purple-fy: an online music player
This project is a Spotify clone that aims to replicate some of the core features and functionalities of the popular music streaming platform. It provides users with the ability to log in, search for songs, create playlists, and control playback of music. 

## Tech Stack

Next.js: Next.js is used as the primary framework for building the frontend of the application. It offers server-side rendering, routing, and other features out of the box, making it ideal for building complex web applications.

React: React is used for building the user interface components of the application. It allows for the creation of reusable UI components and efficient management of application state.

Tailwind CSS: Tailwind CSS is used for styling the components of the application. It provides a utility-first approach to CSS, making it easy to create custom designs and responsive layouts.

Supabase: Supabase is used as the backend for managing user authentication, storing song metadata, and handling user-generated content such as playlists.

## Getting Started

Clone the repository to your local machine.
Install dependencies using `npm install`.
Create a `.env.local` file in the root directory and add your Supabase credentials.
Start the development server using `npm run dev`.
Open your browser and navigate to `http://localhost:3000` to view the application.

## Main Functionalities
User Authentication: The application supports user authentication using email or GitHub, ensuring secure access to personalized content and features.

Song Upload: Users can upload new songs to their library using the Upload Modal component. 

Search Functionality: Users can search for songs by title

Playback Control: Users can play, pause, skip forward, and skip backward through songs. They can also control the volume of the audio.