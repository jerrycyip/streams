# streams
Basic React.js app implementing video web streaming with CRUD operations for users to create, view, edit, and delete streams.  App also supports user authentication with Google's OAuth API.

## Streams App High Level Architecture
![overall Streams web app architecture](./streams%20app%20architecture.png)

## Project Structure
Note, majority of the code is for creating the Client web app using React.js with redux, while backend server functionality leverages free and readily available JSON web server (see API folder) and RTMP server software (see RTMP folder).  Reference the Client folder for further details on the client web app.  For details on setup of the JSON server (REST API server) see documentation ![here](https://www.npmjs.com/package/json-server) and for details on the RTMP streaming server see documentation ![here](obsproject.com).  Lastly, for the streaming video playback functionality within the client streamer app, I implemented flv (flash video) player given it's simplicity of install -- see documentation ![here](npmjs.com/package/flv.js) for further details.

## Result - Demo
![Streamer App Demo](stream_app_demo.gif)
