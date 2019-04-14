# Default starter for Gridsome

### 1. Install Gridsome CLI tool if you don't have

`npm install --global @gridsome/cli`

### 2. Create a Gridsome project with Sass

1. `gridsome create my-gridsome-site` to install default starter
2. `cd my-gridsome-site` to open the folder
3. `npm install -D sass-loader node-sass` to install sass
4. Now you can import .scss files in src/main.js by adding the following line to src/main.js

   > import './assets/styles.scss'

5. `mkdir src/assets` create assets folder inside src folder
6. `touch src/assets/styles.scss` create Sass styles file where your Sass will be edited.
7. `gridsome develop` to start a local dev server at `http://localhost:8080`

**_Happy coding_**
