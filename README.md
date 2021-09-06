# NowPlaying.js
A small widget that displays the track that is currently playing. It is responsive, adjustable and will slide the text if it's too long for its container.

![example](https://user-images.githubusercontent.com/51798197/131869081-653f4eb8-e438-49b4-9b61-0abfa5e1ab36.png)

## Demo
Click [here](https://ozturkkl.github.io/NowPlaying.js) to view the demo.

## Usage
Download the repo, it contains the widget. Go to your streaming software and add "Browser Source", direct its url to the repo foler.

Go to setup.js and fill out the required information to customize the widget for your radio.

```js
export default {
    defaultArtist: "My Radio",
    defaultTitle: "No title found...",
    defaultImage: "default.png",
    currentlyPlayingTrack: "https://www.radioking.com/widgets/api/v1/radio/306541/track/current",
    widgetSize: "300px",
    infoWidth: "700px",
    bodyBackground: "#050505",
}
```

*That's it, thanks for checking it out! :D*

## Other useful things to know: 
- You can set the background to green in order to easily set up a color key to remove the background.
- If using OBS, set a custom framerate on the browser source for a smoother slide animation for the text.
- **_widgetSize_** controls the overall size of the widget, **_infoWidth_** controls the length of the artist&track bar.

## License
This project is licensed under the MIT License.
