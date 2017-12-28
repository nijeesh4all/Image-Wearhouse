# Image Wearhouse
Image wearhouse is a neet and efficient way to oragnise and view internet pictures.It's very user friendly and simple UI design helps you to keep track of your images as you like.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
### Features
	Real Time Search
	Responsive Design
	Simple UI
	Material UI
### Development
#### Prerequisites
**Node JS**
```BASH
sudo apt-get install nodejs
sudo apt-get install npm
```
**Angular-cli and dependecies**

```bash
npm install  
```
in working directory

#### Serving

```
ng serve --open
```
#### Building
```
ng build --out-dir <location>
```
### Launching
You can make use of any backend http server to host this 
#### Apache
copy and paste the contents of build to ```/var/www/html```
#### Express
Setup express to host static files
```
app.use(express.static('public'))
```
Copy and paste the contents of build to public folder

### Built With
	Angular 2
	Angular Material
	Material CSS

