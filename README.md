# Social network
Social network with React, Redux, Redux-thunk, NodeJS, Express, MongoDB

Heroku link: [https://sheltered-forest-35138.herokuapp.com/](https://sheltered-forest-35138.herokuapp.com/)

# To Start
## Create a default.json file in config folder

```json
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret"
}
```

## Install server dependencies

```bash
npm install
```

## Install client dependencies

```bash
cd client
npm install
```

## Run both Client & Server from root

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it on the client side.

Open [http://localhost:5000](http://localhost:5000) to view it on the server side.

The page will reload if you make edits.\
You will also see any lint errors in the console.
