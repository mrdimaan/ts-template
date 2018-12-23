## Typescript template
To use this you Should Have tslint and typescript installed globally.

### While Develpement
Use `npm start` after `npm i` to run the app. the app will recompile and restart automatically after making changes on a file in src folder.

### For Production
Use `npm run build` to just compile the code.
Then if you use pm2 you can config `pm2.config.json` file and `pm2 start pm2.config.json`.
If you just want to run it without using pm2 just `node dist/index.js`.
