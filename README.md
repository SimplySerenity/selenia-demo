![demo screenshot](https://raw.githubusercontent.com/SimplySerenity/selenia-demo/master/ghstuff/screenshot.png)
This repo is holding the compiled version of a simple react app that streams screenshots from a Hasura endpoint.

The demo works as follows: 
1) [Selenia](https://github.com/SimplySerenity/Selenia) cluster running on DigitalOcean crawls [csusm.edu](https://csusm.edu/)
2) Workers screenshot each page and upload the images to a DigitalOcean space
3) The link of the image is pushed to a Hasura(GraphQL) endpoint
4) The react app pulls the images from the endpoint in realtime
