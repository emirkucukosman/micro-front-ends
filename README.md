# Example Micro Front-End Setup

This repo is an example of a Micro Front-End setup with Webpack module fedearation. 
One of the beatuies of Micro Front-Ends is you can run a Solid, Vue, Angular etc. app inside a React app or vice versa
without the host knowing about the remote app's technology stack
<br />
- `host` folder contains the Solid app that hosts the Solid remote app running on port 8080 <br />
- `react-host` folder contains the React app that hosts the Solid remote app running on port 3001 <br />
- `remote` folder contains the Solid app that serves the remote app running on port 3000 <br />

# Get Started
1. Install dependencies for `host` with `cd host && npm install`
2. Install dependencies for `react-host` with `cd react-host && npm install`
3. Install dependencies for `remote` with `cd remote && npm install`

# Start Apps
1. Run the Solid host with `cd host && npm start`
2. Run the React host with `cd react-host && npm start`
3. Run the Solid remote with `cd remote && npm start`
4. Make a change in the remote app, refresh the host app's page and Voilà!
