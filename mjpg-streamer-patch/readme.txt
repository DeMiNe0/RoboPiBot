Date: 2016-07-02
URL: http://custom-build-robots.com

Fix mjpg-streamer to work with kernel 3.18

1. Download mjpg-streamer.
2. Extract the patch and copy all four files into the folder ../mjpg-streamer/plugins/input_uvc/
3. Install mjpg-streamer as normal on your Raspberry Pi

Koos has described and written the patch in the forum www.raspberrypi.org
http://www.raspberrypi.org/forums/viewtopic.php?f=28&t=97983&p=681259

The source of the patch is also available via github:
https://github.com/codewithpassion/mjpg-streamer/pull/4/files