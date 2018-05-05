# website
Pale Black website built with Hugo on Netlify, with content managed in Contentful


## Run

Inject the contentful access token by using a second config file `access-token.toml` with

    [Params]
    access_token = "<ACCESS TOKEN>"

and start the local server with

    hugo server --config config.toml,access-token.toml
