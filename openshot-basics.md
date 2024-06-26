---
layout: default
title: 2-OpenShot Basics
nav_order: 3
parent: Workshop Activities Old
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
<img src="images/openshot-basics-01.png" style="float:right;width:180px;height:180px;" alt="OpenShot logo"> 
# Basics
In this exercise, you will create and edit a movie using OpenShot Video Editor. If you have any questions or get stuck as you work through this, please ask your instructor for assistance.  Have fun!

Pre-class Activity Preparation (if you have not already, please download OpenShot Video Editor). 
- [Download OpenShot Video Editor](https://www.openshot.org/download/){:target="_blank"} (click on the corresponding download format (Linux, OS X, Windows) 

1. If you don’t have a video that you want to edit, let’s start by downloading [this video](http://bit.ly/dsc-goat-video){:target="_blank"}, and saving it to your desktop. It may take 1 or 2 minutes to download.  **Note**: If the video starts playing you will have to right mouse click on the video & select “**Save Video As**...” to save to the Desktop on your computer.

2. Open OpenShot Video Editor by clicking on the OpenShot Video Editor (see the icon that looks like a globe at the top of this page).
- Control/Right click on **New Project** icon 
- Then select “**Project Files**” from the pull down 

<button onclick="toggle('gif1')">Show / Hide Animation </button>
<div id="gif1">
      <img src="images/openshot-basics-02.gif">
      </div>

3. Next click on the “**+**” button at the top of the OpenShot Video Editor screen. 
- Select “**Desktop**” on the left navigation pane and then select “**goats.mp4**” 
- Finally, click on the file and select  “**open**” on the bottom right of the dialog box.

<button onclick="toggle('gif2')">Show / Hide Animation </button>
<div id="gif2">
      <img src="images/openshot-basics-03.gif">
      </div>

4. Drag the video clip you just imported into the timeline at the bottom of the OpenShot Video Editor screen.

<button onclick="toggle('gif3')">Show / Hide Animation </button>
<div id="gif3">
      <img src="images/openshot-basics-04.gif">
      </div>

5. First, play the 90-second video by pressing the play button below the video. (Note: pressing the spacebar will start and stop the video which is very handy while editing)

6. Trim 20 or 30 seconds off the end of the video by selecting the video in the timeline and then moving the mouse pointer over the end of the video clip and then drag the handle to the left. The same can be done at the beginning of the video if you’d like.

<button onclick="toggle('gif4')">Show / Hide Animation </button>
<div id="gif4">
      <img src="images/openshot-basics-05.gif">
      </div>

7. <img src="images/openshot-basics-06.png" style="float:right;width:300px" alt="Split Clip Menu"> Next, let’s split the video at approximately the 15-second mark from the beginning. To do this, select the video in the timeline, then control/right mouse click at about the 15-second mark, and finally, select “**Slice**” and “**Keep both Sides**”.<br>

<button onclick="toggle('gif5')">Show / Hide Animation </button>
<div id="gif5">
      <img src="images/openshot-basics-07.gif">
      </div>

8. The trimmed and split video should now look like the photo below.
![Image of Split and trimmed video footage](images/openshot-basics-08.png)
9. Now make a transition between the split videos:
- **Right mouse click** on the first video clip in the timeline, and from the pop-up menu select **Fade** and then **End of Clip** and then **Fade Out (Slow)**.
- **Right mouse click** on the second video clip in the timeline, and from the pop-up menu select **Fade** and then **Start of Clip** and then **Fade In (Slow)**.

10. Let’s add a title to the video:
- Select the “**Titles**” menu at the top of your computer screen (or on a Mac by clicking “Command + T” or on Windows “ctrl + T”).
- Edit and the title text, and then press the **Save** button.
- Drag and drop the title you just created from the “project files” box in the top left of your screen to the left side of your timeline at the bottom of the screen. 
- To edit the title text, **right mouse click** on the Title in the “Project Files” area in the top left of your screen, and then select **Edit Title** from the popup menu. Edit text as desired.

<button onclick="toggle('gif6')">Show / Hide Animation </button>
<div id="gif6">
      <img src="images/openshot-basics-09.gif">
      </div>

11. Now add credits for your video by dragging and dropping a credit style “**title**” from under the “**Titles**” tab to the end of the video. Edit this same way you edited the title in step #10.

12. Next, let’s mute or reduce the volume of the audio:
- Select a video clip in the timeline.
- Control/Right Click to select “**Volume**” 
- Under the pop-up menu click “**Entire Clip**”. A percentage of audio volume will be listed in the pop-up menu. Select the volume percentage that you desire.

<button onclick="toggle('gif7')">Show / Hide Animation </button>
<div id="gif7">
      <img src="images/openshot-basics-10.gif">
      </div>


13. Once you’re happy with your edited video you’ll need to export it in order to upload it to YouTube, or share it via Google Photos or some other sharing service:
- Press the **Save Project** button in the very top left (third icon from the left) of the OpenShot Video Editor window.  Give your movie a descriptive name. Select the folder where you want to put your video and press the **Save** button.
- Once the video is saved you can select the **export** button
- It will take a few minutes for OpenShot Video Editor to export your video.

14. Congratulations, you’ve created and edited a video in OpenShot Video Editor! If you want to post your video to YouTube, just upload the file to your YouTube account.


<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: OpenShot Green Screen](openshot-green-screen.html){: .btn .btn-blue }
