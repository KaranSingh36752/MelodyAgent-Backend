# Spotify Authorization Code

This app displays your Spotify profile information using [Authorization Code](https://developer.spotify.com/documentation/web-api/tutorials/code-flow)
to grant permissions to the app.

## Using your own credentials

You will need to register your app and get your own credentials from the [Spotify for Developers Dashboard](https://developer.spotify.com/dashboard).

- Create a new app in the dashboard and add `http://localhost:8888/callback` to the app's redirect URL list.
- Once you have created your app, update the `client_id`, `redirect_uri`, and `client_secret` in the `app.js` file with the credentials obtained from the app settings in the dashboard.

## Running the example

From a console shell:

    $ npm start

Then, open `http://localhost:8888` in a browser.
