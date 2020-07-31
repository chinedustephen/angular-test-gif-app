# Chilaka Michael Obinna - GiphyAPI Search
A simple, responsive giphy browser. On initial load this site will show all of the most recently trending Giphy gifs based on the API. 

or checkout and run it locally with
`npm install` and `npm run start`

## Build System
- Added Webpack to compile and bundle all file types.
    - Easily bundle all js and css
    - Allows us to use webpack dev server and hot reloading
- Included Babel loader to add support for ES6 code
    - Uses preset-env to support older browsers
- Added PostCss/Autoprefixer for wider browser support

## Project Structure
- Project pieces separated out into containers, components, with matching css structure for better organization
    - Containers made to hold majority of app logic, while components are simplified to render-only items.

## Frontend
- React-Bootstrap 12-col CSS grid added for responsive scaling.
- Redux added for better scaling and state management
    - Probably not necessary with the small amount of state management required right now, but offers greater scalability.
    - Using dispatch feels cleaner than modifying state directly anyways.




