## HOW TO WRITE SIMPLE SPA
## IN TYPESCRIPT
##### (WITHOUT FRAMEWORK)
***
![spa_ts](https://user-images.githubusercontent.com/71274666/119955302-9af39e00-bfa8-11eb-87a5-d85a09e34c00.gif)
***
1. Create a folder for your project.
Please, you should remember that folder name cannot consist of several words ("spa", "MyMvc", "app_example" are good);

2. Open your folder by IDE

3. Open terminal in your IDE

4. **npm init -y** 

5. **npm i typescript --save-dev** to install TypeScript

6. **npx tsc --init** to initialize TypeScript

7. Create "webpack.config.js" file

8. Copy configurations and save them

9. **npm i html-webpack-plugin webpack-dev-server webpack webpack-cli ts-loader css-loader style-loader**

10. Create index.ts and index.html

11. In "package.json" create script "start"

12. **npm run start** to check your settings

Note: There are two folders: 'core' and 'pages'. In 'pages' you save each of pages of your SPA: 'error', 'main', 'settings', 'statistics' and the most mainest folder is 'app'.
You also save components and templates of application in 'core' folder. This has two folders: 'templates', which includes all the templates (abstract classes or interfaces) and 'components', which includes all the components based on templates ('header', for example).
