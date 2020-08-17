# Virtual Classroom

![OBS Video settings](2020-08-17-10-47-25.png)

If you want to greatly improve your virtual classroom experience and alter what students see, you should give [Open Broadcast Studio (OBS)](https://obsproject.com/) a try. OBS is the free and open source software that many 'professional' livestreamers use. The power of OBS (especially for teaching) is it's use of `scenes` which you can switch between during your lesson. For example; you can have multiple camera's or windows and seamlessly switch between them with one single key command.

> Most instructors will be using a MacBook, probably from a couple of years ago. OBS uses a ton of CPU to encode the video stream. Not all computers can handle that smoothly, especially if you have a couple of applications (code editor, designs software open). I've included some settings at the bottom of this page but you might not be able to use OBS at all if your MacBook becomes laggy.

> I'm running a 13-inch 2017 MacBook model (from AUAS) with 8 GB of memory and a i5 dual-rorse @2.3GHz and with a couple of screens open (browser, code editor) I can barely run OBS.

## OBS Virtualcam

But I'm not livestreaming or recording! How do I use the output of OBS in my classrooms or meetings? That's where a virtualcam is the solution. It makes a _virtual webcam device_ from the output of OBS Studio. For long this was a feature for Windows only but since the pandemic hit there is now an open-source [compatible MacOS plugin](https://github.com/johnboiles/obs-mac-virtualcam) which is available on GitHub.

Have a look at the [install guide](https://github.com/johnboiles/obs-mac-virtualcam#installing) to get it up and running.

> There are a couple of 'known issues' for some applications. Have a look at the compatibility wiki page to see if virtualcam works for your application. Most commonly uses applications for education (MS Teams, Browsers) will work.

## Setting up OBS

Setting up OBS is very personal and you can spend hours and hours configuring it to your liking. To get up and running with OBS I recommend you read the [OBS Studio Quickstart](https://obsproject.com/wiki/OBS-Studio-Quickstart) and the [OBS Studio Overview](https://obsproject.com/wiki/OBS-Studio-Overview) guides.

## OBS Settings

After some tweaking here are some suggested video settings if you are on a MacBook:

### Video settings

`Settings > Video`

```
- Base (Canvas) Resolution: 2560x1440 (default macbook)
- Output (Scaled) Resolution: 1280x720
- Downscale Filter: Bicubic (16 samples)
- Common FPS Values: 30
```

### Output settings

`Settings > Output`

```
- Encoder: x264 (but checked ‘enforce streaming service encoder settings’)
- Do not rescale output
- Rate Control: CBR
- Bitrate: 2000
- Keyframe interval: 0
- CPU usage: veryfast
```

> I'm running a 13-inch 2017 MacBook model (providedb by the AUAS) with 8 GB of memory and a i5 dual-core @2.3GHz and with a couple of screens open (browser, code editor) I can barely run OBS smoothly without the CPU throttling.
