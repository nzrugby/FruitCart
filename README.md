# FruitCart -- React Demo
A simple demo for React

It's a very simple demo for React beginner. 
This demo can perform following following fucntions:
1. search function. If nothing inputs then all the products will display.
2. add itsms to shop cart.
3. delete the items from shop cart.
4. simple stock management. If out of stock the products cannot be ordered and system will alert no stock.



How to use it?
1. Download all the folders and files to a local folder(created by you. for examele:  d:\js\)
2. Use console to enter the folder you put all source files and folders.
3. type command:  npm init to create package.json (use default setting first)
4. type command:  npm install webpack --save-dev
5. type command:  npm install webpack-dev-server --save-dev
6. type command:  npm install babel-core babel-loader babel-preset-env babel-preset-react --save-dev
7. type command:  npm install react react-dom --save-dev
8. type command:  npm install style-loader css-loader --save-dev

After you finish all above steps you can run this app.  Still in this app directory type 'npm start' first to pack the all the dependent files. Then run 'npm run server' to start the application.
The only thing you need to be aware is webpack.config.js and package.json.  After you download all the files you'd better backup these two files. For they might be modified when you install the following packages. Sometimes the different version may incur the problems.

Because this demo mainly focuses on React components and their communications, layout and CSS are not optimized. You can modify them to make the UI better. Also I used array and json object to simulate the data for simplicity. You can use json file or database to import the data.


The following is snapshot of this demo.
![react1](https://user-images.githubusercontent.com/31294078/35707918-90f213ee-0810-11e8-8cb7-13287f2d405a.jpg)
