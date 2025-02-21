---
layout: default
title: 2 - Slow Motion & Cropping
nav_order: 6
parent: Workshop Activities Windows
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

<img src="images/ms-videoeditor/cc-basics/logo.png" style="float:right;width:180px;" alt="ClipChamp logo">

# Slow Motion and Cropping
In this exercise, you will create and edit a movie in Clipchamp, including using splitting and duplicating a video clip, making a slow-motion video clip, cropping a video clip, and importing audio to overlay your clip. If you have any questions or get stuck as you work through this, please ask your instructor for assistance.  Have fun!

1.  Let’s start by downloading the Mountain biking video and save it to your computer: [https://bit.ly/3vrLJj0](https://bit.ly/3vrLJj0){:target="_blank"}. If the video starts playing you will have to right mouse click on the video & select “**Save Video As...**” and save it to the **Desktop** folder on your computer

2.  Open Microsoft Video Editor if you have not already done. 

3.  Open Cipchamp if you have not already done so.
    -   Click on the **Create a New Video** icon.
    -   Beside the import media button, give your video project a name (“**test bike**” would be just fine).
    -   Click “**OK**”
    
    <img src="images/create-new.png" style="float:right;width:200px" alt="Create a New Video button">

4.  In the “**Project Library**” pane, click the “**+ Import media**” button and select “**Browse files**”
    -   Select “**Downloads**” on the left navigation pane and then select “**bike.mp4**”
    -   Finally, click on the file and select  “**Open**” on the bottom right of the dialogue box.
      
5.  **Drag** the bike video you just imported from the **Project Library** to the **Timeline** at the bottom of the window:

      <button onclick="toggle('gif1')">Show / Hide Animation </button>
<div id="gif1">
      <img src="images/cc-slow1.gif">
      </div>
    
6.  Now you’ll make a slow-motion video clip with the “**bike**” video:
    -    **Move the white cursor** to the point in the video just before the rider starts to jump (see video below).
    -    Let’s isolate a short clip to slow down. Start by right clicking and selecting the **Split button**.
    -   **Select** the second video in the timeline, and **move the white cursor** to the point in the video where the bike lands (see video below).
    -   Click the **Split button** again. Now your clip should be isolted.
<img src="images/split-slo.png" style="width:400px;" alt="split">
    -   Next, **Click** on the **middle of the 3 video clips** in the timeline.
    -   To slow down the clip you just selected, press the **Speed** button on the right side. 
    -   Then **drag** the slider to **0.25** <br>
        <img src="images/speed-slo.png" style="width:300px;" alt="speed">

          <button onclick="toggle('gif2')">Show / Hide Animation </button>
<div id="gif2">
      <img src="images/cc-slow2.gif">
      </div>    
      
7.  Crop or zoom in on a video clip:
    -   **Click** on the **middle of the 3 video clips** in the timeline.
    -   To Crop, press the **crop symbol** button towards the right.
    -   Adjust the view of the video by moving the corners in. <br>
  <img src="images/crop.png" style="width:300px;" alt="Crop">

8.  Congratulations, you're done! Feel free to add a title & credits to your video if you want. Your video should look something like this: [https://goo.gl/gkqx8b](https://goo.gl/gkqx8b){:target="_blank"}

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

   [NEXT STEP: Adding Audio and Free Music](cc-audio-music.html){: .btn .btn-blue }
