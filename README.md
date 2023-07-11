# MyBlog

MyBlog is a simple blogging application built using Ruby on Rails and Angular. It allows users to create and publish their own blog posts, read and comment on posts from other users, and browse posts based on tags or categories.

## Features
MyBlog is currently under development, and the following features are planned for implementation:

- [ ] User registration and authentication: Users will be able to create accounts and log in to the application.
- [ ] Create and publish blog posts: Authenticated users will have the ability to create, edit, and publish their own blog posts.
- [ ] Commenting system: Users will be able to comment on blog posts, fostering discussion and engagement.
- [ ] Tagging and categorization: Posts will be organized using tags and categories, allowing users to browse content based on their interests.
- [ ] Search functionality: Users will be able to search for specific blog posts or topics.
- [ ] User profiles: Each user will have a profile page that displays their published blog posts and other relevant information.

As development progresses, additional features may be added based on user feedback and requirements.

## Cloning the Repository
To clone the MyBlog repository and initialize its submodules, follow these steps:
1. Open your terminal or command prompt.
2. Change to the directory where you want to clone the repository.
3. Execute the following command:

   `git clone --recurse-submodules https://github.com/CuddlyBunion341/MyBlog.git`
   
   _The `--recursive` flag ensures that the submodules are also cloned and initialized during the cloning process._

4. Change into the API and APP directories and folow their instructions respectively

## API

The MyBlog application includes a separate backend API built using Ruby on Rails. The API handles data storage, retrieval, and business logic. The source code for the API can be found in the following location:

[Blog Backend](/blog-api/)

The backend API provides endpoints for various operations, such as user registration, authentication, creating and retrieving blog posts, managing comments, and handling tag/category information.

## APP

The MyBlog application also includes a frontend built using Angular. The frontend provides a user-friendly interface for interacting with the blogging application. The source code for the frontend can be found in the following location:

[Blog Frontend](/blog-app/)

The frontend is responsible for rendering the blog posts, displaying user profiles, facilitating user interactions (such as commenting), and providing an intuitive browsing experience. It communicates with the backend API to fetch and update data.