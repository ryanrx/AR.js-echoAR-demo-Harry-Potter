# AR.js-echoAR-demo-Harry-Potter
Simple web based AR experience with 3D model.

## Register
Don't have an API key? Make sure to register for FREE at [echoAR](https://console.echoar.xyz/#/auth/register).

## Setup
* [Add the 3D model](https://docs.echoar.xyz/quickstart/add-a-3d-model) *Harry_Potter.zip* from the [assets](https://github.com/ryanrx/AR.js-echoAR-demo-Harry-Potter/tree/master/assets) folder to the console. 
* [Add the image](https://docs.echoar.xyz/ar.js/deploy-experience#image-target) *Harry_Potter.jpg* from the [assets](https://github.com/ryanrx/AR.js-echoAR-demo-Harry-Potter/tree/master/assets) folder as the image target for the model.
* [Add the metadata](https://docs.echoar.xyz/web-console/manage-pages/data-page/how-to-add-data#adding-metadata) listed in the the [metadata](https://github.com/ryanrx/AR.js-echoAR-demo-Harry-Potter/blob/master/metadata.csv) file to the hologram.
* Replace the api key and the entry ID in the html file with your own api key and entry ID that can be found in console. 
* Replace the image src in the html file with the actual path to the logo image *harry-potter-logo.jpg*.

## Run
Open *index.html* locally on a server like MAMP or simply import *index.html* into online platform like Glitch or Codepen to try the demo right away.

## Notes
 * When you use browser to try the demo make sure you use HTTPS to avoid any problem on camera accessibility. 
 * Loading Complex model or loading models the first time may take 5-10 seconds to render. Please be patient.

## Screenshots
![ARjs website screenshot](/images/screenshot1.png)
![echoAR console screenshot](/images/screenshot2.png)
![echoAR console screenshot](/images/screenshot3.png)