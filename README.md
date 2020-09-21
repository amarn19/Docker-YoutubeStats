## Instructions 
1. Clone repository
2. Run npm install to install node modules
3. Replace API key in the .env file . Instructions to obtain API key found [here](https://www.slickremix.com/docs/get-api-key-for-youtube/)
4. Run npm start to run app
5. Key in YouTube Video ID into search box to retrieve results. You can get the video ID from any YouTube video URL. 

## Instructions to Build and Run Docker Image
1. Follow instructions 1 & 3 above.
2. To build image, cd into directory and run `docker build . -t youtubereactapp:latest`
3. To run container enter `docker run --rm -it -p 3000:3000/tcp youtubereactapp:latest`

## Generic Create React App Stuff
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
