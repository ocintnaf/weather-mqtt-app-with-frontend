# MQTT Multichannel store and forward system 

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://travis-ci.org/joemccann/dillinger)

Simple publish/subscribe MQTT system implemented with React.js 

## Prerequisites
- npm
    ```
    npm install npm@latest -g
    ```

## Installation

This app requires [Node.js](https://nodejs.org/) v10+ to run.
1) Get a free API Key at [OpenWeathermap](https://openweathermap.org/api) 
2) Clone the respository
    ```sh
    git clone https://github.com/ocintnaf/mqtt-weather-app.git
    ```
3) Install the dependencies
    ```sh
    cd mqtt-weather-app
    npm install
    ```
4) Enter your API Key in `config.js`
    ```javascript
    API_KEY: "YOUR API KEY"
    ```
5) Start the broker 
    ```sh
    cd src/backend
    node broker
    ```
6) Start the React app
    ```sh
    npm start
    ```
    
## Usage
[![Code snippet](https://i.postimg.cc/qvM5RDxZ/Screenshot-2021-10-08-at-16-15-49.png)](https://postimg.cc/ZC2cscgr)

## License

MIT
