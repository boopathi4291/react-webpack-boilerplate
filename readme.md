npm init -y

npm install --save react react-dom jquery popper.js bootstrap bootswatch and others in dev dependencies

create config folder inside make webpack for common dev and prod

create vendor.js in root folder to combine the all vendor(bootstrap ,jquery and others) and polyfils

create main.js for bootstrapping

create .babelrc for transpiling the react code into javascript

create src/app appcomponent.jsx for startup component

configure the script object in package.json for devand prod running
