# [CineApp](https://cineapp.netlify.app/)
![img](https://user-images.githubusercontent.com/81650755/227263059-828cf054-b332-4423-9e59-75491a057b54.jpg)


## Overview
Hello 👋, Welcome to my project of CineApp app which was built with React, Redux. This project helps in getting thousands of movie details which are Top Rated, Popular, Upcoming using [TMDB API](https://developers.themoviedb.org/3/getting-started/introduction). This also allows user to search and get movie details based on its name of any language.

Tech Stack used in this project:
- JavaScript Library: **React**
- State Management: **Redux**
- Routing: **React Router**
- API: [**TMDB API**](https://developers.themoviedb.org/3/getting-started/introduction)
- Styling: **CSS**



## Prerequisites for this project
- One should have TMDB API key ready, if you dont know how to get one please refer [TMDB](https://www.themoviedb.org/documentation/api)
 
## Environment variables
Finally one should have file named .env with the TMDB API key and base url of endpoint setup as follows
```js
//.env
REACT_APP_API_KEY = [TMDB API key]
REACT_APP_BASE_URL = https://api.themoviedb.org/3
```
## How to install this project
1. Clone the project using the command `git clone https://github.com/vtejaetaalexa9205/CineApp.git`
2. Move into the file directory you wish to run using `cd {folder_name}`.
3. Use the following command `npm install` or `yarn` to install the dependencies.
4. Now you can run `npm run dev` or `yarn dev` to run the app in the development mode. It can be viewed in browser at `http:localhost:3000`.
6. For bundling, navigate to root directory and try running `npm run build` or `yarn build` which optimises build for better performance


