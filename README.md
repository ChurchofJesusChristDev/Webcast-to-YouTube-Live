# Church Webcast to YouTube Live

> How to migrate from The Church of Jesus Christ Web Broadcast
([webcast.churchofjesuschrist.org](https://webcast.churchofjesuschrist.org/))
to YouTube Live.

<kbd><a href="https://www.youtube.com/playlist?list=PLZaEVINf2Bq-FCwibjP4T-HNEY2cHKOYN"><img title="Church Broadcast Tutorial Video Series" alt="Church Broadcast Tutorial Playlist Thumbnail" src="https://user-images.githubusercontent.com/122831/151767100-4fc42099-4ed7-4b6f-bbfa-957a7adc02fe.jpeg"></a></kbd>

The church's web broadcast system is being sunset in June 2022. \
The approved alternatives are Zoom and YouTube Live.

Although Zoom is more straightforward to use on a one-off basis,
YouTube Live is a much better **push-button solution** for regular meetings.

# Overview

1. Create a YouTube Account & YouTube Channel \
   https://youtube.com
2. Change the YouTube Channel Settings
   - Branding
   - Privacy Settings
   - Membership & Permissions
3. Apply to YouTube Live (and wait 24 hours)
4. How to set up YouTube Live
5. How to get your Stream Key
6. How to set up Larix (iPhone & Android) 

Once your YouTube Live account is ready you'll be able to access your RTMP stream key
and update the Larix app to broadcast to the new URL
(this is the same process as with other software, such as OBS, for YouTube, Twitch, etc).

_a picture costs 1,000 words..._

# 1. How to create a YouTube Channel

1. Sign in to https://youtube.com
2. Scroll down on the left panel and click "Settings" \
   https://www.youtube.com/account
3. Click "Add or Manage your Channels"
4. Click "Create a Channel"
5. Name your channel, for example: \
   "Star City, Church of Jesus Christ Worship Services"

# 2a. How to Update YouTube Channel Branding

1. Click "Your Channel"
2. In the top right area click "Customize Channel"
3. Select the "Branding" tab
   - Profile Picture should be 186x186 (minimum 98x98) JPEG
   - Banner image should be 2048 x 1152 (or larger) JPEG
   - Watermark (if any) should be 300x300 (minimum 150x150)
4. If you select the "Basic Info" tab you can give a description of the service,
   the official church website, and other services, if you like

Example of a good description:

> 10am Relief Society (Women's Sunday Services) for The Church of Jesus Christ of Latter-Day Saints of the City Ward on the 2nd and 4th Sundays of each month.

# 2b. How to Update YouTube Channel Privacy Settings

1. Click "Your Channel" from the Account dropdown
2. In the top right area click "Customize Channel"
3. Scroll down on the left panel and click "Settings" (this is channel settings, which is different from your account settings)
4. Channel
   - Basic Info => Keywords => Christian
   - Advanced Settings => **Not for kids**
   - Upload Defaults => Title, Description, Tags
     - Example Title: _City Ward Relief Society 10am Sunday Service (2nd & 4th Sundays)_
     - Example Description: _10am Relief Society (Women's Sunday Services) for The Church of Jesus Christ of Latter-Day Saints of the City Ward on the 2nd and 4th Sundays of each month._ \
       _Subscribe and click the bell for all alerts to get email notifications when we start._
   - Upload Defaults => Visibility
   - Upload Defaults => Advanced Settings => **Comments**
   - Permissions => Manage Permissions
   - Community => **Block links**
   - Community => Defaults => Hold all for review

To add moderators you must use their channel URL (the url that they get from clicking "Your Channel" when logged in to their personal account).

# 2c. How to Add YouTube Channel Owners & Managers

1. Click "Your Channel" from the Account dropdown
2. In the top right area click "Customize Channel"
3. Scroll down on the left panel and click "Settings" (this is channel settings, which is different from your account settings)
4. Channel
   - Permissions => Manage Permissions

# 3. Apply to YouTube Live

Applying to YouTube Live will require phone verification and will enable
any features that are only available to verified channels.

1. Sign in to YouTube Studio for your Channel Account
   - Sign in to https://youtube.com
   - Select your Church channel from list under the Account Icon in the upper right \
     **Note**: it may appear under the "Switch Accounts" list
   - Click on your Account Icon in the upper right (again)
   - Select "YouTube Studio"
     https://studio.youtube.com/
2. Click through the annoying pop-ups / "Welcome Wizard"
3. Click "Create" in the upper right
4. Select "Go Live"
5. Click "Enable"
6. You will be require to Verify your account with a phone number. \
   It's fine to use your personal phone number for now. \
   (this can be changed to a church number later). \
   **Note**: if you've recently verified a few accounts, you may need to use a different number)
7. Close the Verify tab to go back to "YouTube Studio" \
   https://studio.youtube.com/

You'll have to wait 24 hours for your Live channel to become active.

# 4. How to set up YouTube Live (streams)

After 24 hours, when your account is active, you'll want to activate some **privacy settings**:

1. Sign in to YouTube Studio for your Channel Account
   - Sign in to https://youtube.com
   - Select your Church channel from list under the Account Icon in the upper right \
     **Note**: it may appear under the "Switch Accounts" list
   - Click on your Account Icon in the upper right (again)
   - Select "YouTube Studio"
     https://studio.youtube.com/
2. Open the Live Settings
   - Click **🎥 Create**
   - Select **Go Live**
   - Select **Right Now** and Start \
     (or Later Date, it doesn't really matter)
   - Select **Streaming software** and Go
3. Edit **Stream Settings**
   - Ultra low-latency \
     (**less delay** between real life and the stream)
   - **Unlist** live replay once stream ends \
     (doesn't show the recording in the public video list - but doesn't delete it either)
4. Edit **Recording Settings**
   - Click "Edit", up by Title
   - Under "Details"
     - Visibility should be "Public" \
       (assuming you want visitors to the channel URL to see when you're live)
     - Uncheck "Allow Embedding"
   - Under "Customization"
     - Uncheck "Live chat" (or limit to Subscribers)

If you want **more privacy**:
- Use **Schedule Stream** each week (rather than a default stream)
- Completely _unlist_ the stream by default (back in channel settings, and stream settings)
- Email the scheduled link out to members each week

That all said, before you can actually "Go Live", you need a Stream Key and broadcast software...

# 5. How to get a Stream URL + Key

🚨 😬 You don't want **dirty content** on your live channel, so read this carefully.

There are a bunch of hooligans out there that enjoy "Zoom-bombing" (pulling distasteful pranks)
and if they get ahold of your stream key, they can publish whatever they want to your channel.

Your unwitting subscribers will get a link to whatever they publish.

Whoever has a laptop or phone that has a stream key should keep it safe:
- 🔐 Password protect the device
- 🔞 Keep out of the hands of mischievous kids (i.e. in the congretation)
- 👮‍♂️ Report to the tech specialist if a device with a stream key is taken

_With all that out of the way..._

1. Sign in to YouTube Live for your Channel Account
   - Sign in to https://youtube.com
   - Select your Church channel from list under the Account Icon in the upper right \
     **Note**: it may appear under the "Switch Accounts" list
   - Click on your Account Icon in the upper right (again)
   - Select "YouTube Studio"
     https://studio.youtube.com/
   - Click **🎥 Create**
   - Select **Go Live**
2. Open the Key Manager
   - Click on the Stream (broadcast) icon in the left menu
   - Look under "Stream key"
   - Look under "Select stream key"
   - Select **Create new stream key** (or **Manage stream keys**)
3. Create a new Stream Key
   - Give the Key a name, such as "Church iPhone"
   - Leave Streaming protocol as RTMP (for most software: Larix, OBS, etc)

What it looks like:

```txt
Stream URL: rtmp://a.rtmp.youtube.com/live2
Stream Key: xxxx-xxxx-xxxx

Stream URL + Key: rtmp://a.rtmp.youtube.com/live2/xxxx-xxxx-xxxx
(same as above, but joined together with a '/')
```

🚨 If you ever need to disable a key because a device was stolen or gotten into
(or you don't trust the person you gave it to), you can simply go back to **Manage stream keys** and remove that key.
