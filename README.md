# LinkedIn Clone v1

## Description

This project is a clone of LinkedIn built using React with Vite as the bundler. It aims to replicate some of the core features of LinkedIn, allowing users to view posts from others, interact with likes and comments, and manage their own profiles.

## Features

- **Authentication:** Users can sign up, log in, and log out securely.
- **Profile Management:** Users can update their names, profile pictures, cover pictures, and add a title for their profile. They also have the option to remove their profile picture or cover picture.
- **Viewing Posts:** Users can view posts from other users and interact with them by adding likes and comments.
- **Post Updates:** Users can create posts with text only or with text and up to four images. They can delete their own posts.
- **Pagination:** React Query and Intersection Observer are used to handle pagination for posts and comments efficiently.
- **Form Validation:** React Hook Form with Zod as a validator ensures robust form validation.
- **API Requests:** Axios and React Query handle all API requests, providing a smooth user experience.
- **State Management:** Redux and Redux Toolkit are used for managing application state, especially for fetching user data.
- **Styling:** Tailwind CSS is used for styling components, providing a responsive and visually pleasing UI.
- **Date Handling:** Moment.js is used for handling dates, ensuring consistency and accuracy in date representations.
- **Iconography:** Material-UI Icons are utilized for adding various icons and symbols throughout the application.

##  Installation (client)
1. Install dependencies:
   npm install
2. Start the development server:
   npm run dev
3. Open your browser and navigate to `http://localhost:5173` to view the application.
##  Installation (API strapi)
1. Install dependencies:
   npm install
2. go to .env and replace exmaple cloudinary keys with your keys   
3. Start the development server:
   npm run dev
4. Open your browser and navigate to `http://localhost:1337` to view the application.
5. now go to http://localhost:1337/admin/settings/users-permissions/roles choose Authenticated and  give full access to this endpoints and *select all*
- BLOCK-LIST
- COMMENT
- CONNECTION
- CONNECTION-REQUEST
- LIKE
- POST
### select only this endpoints from *users-permissions*
- updateMe
- removeCoverPicture
- removeProfilePicture
- me
## Usage

1. Sign up for a new account or log in with existing credentials.
2. Create and customize your profile with personal and professional information.
3. View posts from other users and interact with them by adding likes and comments.
4. Post updates, share content, and delete your own posts.
5. Explore the application features and functionalities to enhance your learning and practice experience.

## Note

This project is created solely for practice and learning purposes. It is not affiliated with or connected to the official LinkedIn website in any way.

## User Functionalities

- **Profile Management:**
- Update name
- Update or remove profile picture
- Update or remove cover picture
- Add a title for the profile
- **Posts:**
- Create new posts with text only or with text and multiple images (max 4)
- Delete own posts
- Like/unlike posts
- Add/remove comments

## Backend
- strapi cms with custom routes & controllers
- cloudinary for store media  
  This project uses Strapi as the backend, collaborated with eng.MohamedOsamaDev and eng.Mazen Sherif
-[mohamed osama](https://github.com/MohamedOsamaDev)
-[mazen sherif](https://github.com/mazensherif09)

## Postman documentation

-[linkedin-clone postman](https://documenter.getpostman.com/view/33034809/2sA3JJ8hfq)


## License

This project is licensed under the [MIT License](LICENSE).

## Technologies Used
- Vite
- React
- React Router
- React Hook Form
- Zod
- Material-UI
- Redux
- Redux Toolkit
- React Query tanStack
- Axios
- js-cookie
- Moment.js
- React Intersection Observer
- Tailwind CSS
- strapi cms

## Contributors
- [mazen sherif](https://github.com/mazensherif09)
- [mohamed osama](https://github.com/MohamedOsamaDev)
- [Moataz Ali](https://github.com/moo3tazali)
