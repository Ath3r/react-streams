# React Streaming Website

## Client

The Client is built using React, Redux for state management

## Server

The Server used in the application are JSON server and RTMP server.

RTMP server is used for handling streams and API Server for connecting streams with the front end.

## Usage

### React Front End

```
cd client
npm start
```

The application will start on [localhost:3000](http://localhost:3000).

### JSON Server Back End

```
cd server
npm start
```

The server will start on port 3001.

### RTMP Server Back End

The server will start on port 8000.

```
cd rtmpserver
npm start
```

#### For Streaming

##### Form OBS

> Settings -> Stream

Stream Type : Custom Streaming Server

URL : rtmp://localhost/live

Stream key : STREAM_NAME

Stream key can be taken from the stream id from the website.

This client application was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

RTMP Server is used from the [link](https://github.com/illuspas/Node-Media-Server)
