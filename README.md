# voice-lap-timer Support
Support for [http://voice-lap-timer.vercel.app](http://voice-lap-timer.vercel.app).

Questions or suggestions? Please open a request in [issues](https://github.com/kdorff/voice-lap-timer-support/issues).


# voice-lap-timer

Visit [http://voice-lap-timer.vercel.app](http://voice-lap-timer.vercel.app) to use **voice-lap-timer**.

<img src="screenshot.png" alt="voice-lap-timer" width="50%">

Once the app is running, click **Start Listening**. It will then recognize the commands as documented on the page.

# Commands In short
Every time you cross the "Start Gate" say the word "done". At that point, it will tell you how long the previous lap took.

During a lap you can say **bad**, **clean**, or **battery** and it will mark that lap with this specified type.

- **bad** suggests you made a mistake during the lap.
- **clean** suggests you felt the lap went well.
- **battery** suggests changed the battery / installed a new pack during the lap.

You can change the voice commands to use words that work best for you. The updated commands should be rememberd between sessions using browser "local storage."

# Browser Support

**This code currently only works Chrome-based browsers**. See the discussion about supported browsers within [react-speech-recognition-es's README.md](https://github.com/tianjianchn/react-speech-recognition) to learn about using this with other browsers.
