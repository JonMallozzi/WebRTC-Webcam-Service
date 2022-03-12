# WebRTC Webcam Serice

WebRTC PeerToPeer broadcast application that allows for multiple webcams to viewed through a single webpage client with authentication.

Originally forked from [Tanner Gabriel's WebRTC-Video-Broadcast
](https://github.com/TannerGabriel/WebRTC-Video-Broadcast) as a starting point
## Getting started

### Starting the application

Start the application using Node:

```bash
# Install dependencies for server
npm install

# Run the server
node server
```


### Testing the application

The application should now be running on your localhost:4000 and you test it by connecting to localhost:4000/broadcast.html to add a new broadcaster.

After that, you just need to visit localhost:4000 to connect to the server as a client and you should get the video that is streamed from the broadcaster.

## Authors

Gabriel Tanner orignal Repo <br/>
Jon Mallozzi - Added Auth, Multiple Broadcasters, Styling, Mobile Watcher App, and more. Basically turned it into a real aplication for a home security system.

## Support Gabriel for providing the original source

<a href="https://www.buymeacoffee.com/gabrieltanner" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details
