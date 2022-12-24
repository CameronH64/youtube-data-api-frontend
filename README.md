# Description
This was the final project for one of my computer science elective courses, Introduction to Multimedia Comuting (CSCI 4353). It's a YouTube Data API demonstration frontend made in PyQt5. It's not meant to be a regular usable program, but to demonstrate a few things that the YouTube Data API is capable of within the context of a modern GUI design library, PyQt5.

# Major Features
- Works for all YouTube channels.
- Displays channel profile art.
- Displays channel views, likes, and subscribers, location, and description.
- Displays the most popular recent video (out of the last ten videos).
-- Video title
-- View count
-- Like count
-- Thumbnail art
-- Can download the audio of this video.

# How to Use:
Using this program is simple. All you need is a YouTube channel's channel ID. Copy and paste this channel ID into the text box in the program. The information for that YouTube channel will be displayed.

The download button below can be clicked to download that video's audio. It'll download to the same directory as the application's executable.

## Simple Method to Find YouTube Channel ID
- Navigate to a YouTube channel's home page.
- Copy and paste that URL into this site: https://commentpicker.com/youtube-channel-id.php
- After you complete the captcha, the channel ID should be displayed.

## Alternative Method to Find YouTube Channel ID
For whatever reason you have issues with the above method, this method is more reliable.

- Go to your desired YouTube channel's homepage.
- Inspect element in your browser.
- In the source code, search for "channelid" (press ctrl + F).
- It likely won't come up; this is normal. Refresh the page, and search for it again.
- The second page search result is the proper channel ID.

# Known bugs:
- For some reason, on some computers, the program may crash after downloading a video. Just open the application again to use it again.
