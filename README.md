# [DepthKit](http://www.DepthKit.com) beta 005

![ DepthKit](http://DepthKit.com/images/productshot_2.jpg)

**The RGB+D Filmmaking Toolkit**

**Version 006 for Mac OS X Released on May 13th 2014**

**Version 005 Windows Released on April 16th 2013**

The DepthKit is an experiment in a possible future of film making, where photographic data captured in 3-dimensions will allow for deciding camera angles after the fact, combining the languages of photography and data visualization. This hybrid computer graphics and video would allow for a storytelling medium at once imaginary and photo real.  The DepthKit is a software work flow for augmenting high definition video with 3D scans from a depth sensor, such as an Xbox Kinect, to create a hybrid video and computer graphics. First a recording application allows you to calibrate a high definition video camera to the depth sensor, allowing their data streams to be merged. Secondly a visualization application allows for viewing the combined footage and applying different 3D rendering styles, camera moves, and exporting sequences. 

This software is a science fiction, a seed of a potential future functional just to the point of allowing a community, you, to share in imagining the possibilities.

## Projects
Curious what this looks like? Check out some project created using the toolkit:

 * [RGBD Tumblr](http://rgbd.tumblr.com/)
 * [RGBD Vimeo Channel](https://vimeo.com/album/2024049)

## Background
DepthKit is an ongoing labor of love by the main developers:

* [James George](http://www.jamesgeorge.org), developer 
* [Alexander Porter](http://www.alexanderporter.net), experimental photographer 
* [Jonathan Minard](http://www.deepspeedmedia.com), documentarian 
* [Mike Heavers](http://mikeheavers.com/), web & design
* Jack Armitage, documentation and tutorial videos

Development has been assisted by the expertise, guidance and advice of [Elliot Woods](http://www.kimchiandchips.com) and [Kyle McDonald](http://www.kylemcdonald.com)

## Inspiration
The Toolkit was inspired by many authors, futurists, and theorists who think creatively about the future of imaging, technology and culture:

 * [Towards a Philosophy of Photography](http://www.amazon.com/Towards-Philosophy-Photography-Vilem-Flusser/dp/1861890761) by [Vilem Flusser](http://en.wikipedia.org/wiki/Vil%C3%A9m_Flusser)
 * [Shaping Things](http://www.amazon.com/Shaping-Things-Mediaworks-Pamphlets-Sterling/dp/0262693267) by [Bruce Sterling](http://www.wired.com/beyond_the_beyond/)
 * [Vision Machine](http://pdflibrary.files.wordpress.com/2008/05/paul-virilio-the-vision-machine.pdf) by [Paul Virilio](http://en.wikipedia.org/wiki/Paul_Virilio)

## Support for the Toolkit
The Toolkit has been made possible by the ongoing and generous support of:

* [The Frank-Ratchye STUDIO for Creative Inquiry](http://studioforcreativeinquiry.org/)
* [Eyebeam Art+Technology center](http://eyebeam.org)
* [YCAM InterLab](http://www.ycam.jp/en/interlab/)
* [NYU Interactive Telecommunications Program](http://itp.nyu.edu) 
* [CLOUDS Kickstarter](http://www.kickstarter.com/projects/1636630114/clouds-interactive-documentary)

Very special thanks to the [Art && Code 3D](http://artandcode.com/3d/), [Resonate Festival](http://resonate.io/2013/), and [Eyeo Festival](http://eyeofestival.com/)


## 1) Getting started

The remainder of this README is a guide on how to get started, but we have a few other formats

 * [Video tutorials](http://vimeo.com/album/1977644) 
 * [HTML tutorial](http://DepthKit.com/tutorials.html)

The current manual was written by [Jack Armitage](http://about.me/jarmitage) and edited by the team.

To use the DepthKit you'll need

 * The DepthKit software downloaded and unzipped
 * A Windows or Mac OS X computer with modern graphics
 * An HD video camera
 * A depth sensor
 * A method of mounting the cameras together securely
 * The black and white checkerboard printed on a flat surface 

The DepthKit is compatible with the following operating system and sensor combinations

#### Mac OS X
 * [Asus Xtion pro LIVE](http://www.newegg.com/Product/Product.aspx?Item=N82E16826785030) (Requires [Sensecast drivers installed](http://sensecast.com/files/Sensecast.and.Libs.Installer.v.0.02.dmg) )
 * [Microsoft Xbox Kinect](http://www.amazon.com/Kinect-Sensor-Adventures-Xbox-360/dp/B002BSA298/)

We recommend the Asus sensors over the Kinect because they feature the same resolution, but are smaller in size and don't require wall power allowing for more portability.

#### Microsoft Windows 7
 * Microsoft Xbox Kinect (Only compatible with the older model number, 1414)

#### External Video Camera
The DepthKit can use any HD video camera, including digital SLRs, GoPros, even newer iPhones. We'll be using the Canon 5D MkII DSLR for the purposes of the tutorials, but feel free to use what you have.

#### Lens Choice
In order to match the field of view between your camera and sensor so that the color information adequately covers the depth information we recommend a ~24mm lens on a full frame sensor. A ~16mm lens is adequate coverage for an APS-C sensor like an entry-level Canon DSLR. If you aren't familiar with these terms you should be able to find your [crop factor](http://en.wikipedia.org/wiki/Crop_factor) in the specifications section of your camera manual and you can look up the conversion to full-frame [here](http://www.digicamhelp.com/accessories/dslr-accessories/crop-factor-conversion-chart/). When in doubt, set your zoom lens to its widest setting. Use a wide prime lens for best results. 
	
#### Mounts

![mounts with camera](http://www.DepthKit.com/images/readme/mounts_with_camera.jpg)

The workflow requires the use of hardware to bind the video camera and the depth sensor together. If you'd like to buy a mount from us you can order one for Asus or Kinect through our store <LINK> or buy one of our 3D printed Asus mounts from our [Shapeways store](http://www.shapeways.com/shops/rgbd). For both Kinect and Asus we recommend our lasercut acrylic and aluminum mounts or something that is similarly robust and adjustable.

In the open source spirit, we've also made the plans available online to enable you to make your own mount if you have access to the tools: 

 * **Laser Cutter** Download the laser cutter mount plans for Asus or Kinect <ADD LINK&FILES>
 * **Home Workshop** A [mount](http://www.instructables.com/id/RGBD-Toolkit-Aluminum-Mount-for-Kinect-DSLRvide/) made from angle aluminum with basic tools
 * **Home 3D Printing** Print a mount using [community created files](http://www.thingiverse.com/search?q=RGBDToolkit)

Please add your own mounting solutions and designs – however simple or rudimentary – to [Instructables](http://www.instructables.com/tag/type-id/?sort=none&q=RGBDToolkit) or your 3D printable models to [Thingiverse](http://www.thingiverse.com/search?q=RGBDToolkit) and tag them with "DepthKit" or "RGBDToolkit." For recommendations about designing your own mounts see the FAQ. <LINK FAQ>

![mounts with camera](http://www.DepthKit.com/images/readme/mounts_without_camera.jpg)


If you'd rather just buy a kit, we have a stock pile of the above mounts and are happy to sell one to you. Just email me [at] alexanderporter [dot] net to order one. We accept paypal and ship anywhere!

#### Checkerboard

Print out the [A4](https://github.com/downloads/obviousjim/DepthKit/chessboard_a4.pdf) or [A3](https://github.com/obviousjim/DepthKit/blob/master/chessboard_a3.pdf) calibration checkerboard PDF in black and white on matte paper. Glue or otherwise mount it to something flat and rigid like wood or foamcore. This can be done easily at most print shops – if you do it at home look out for bubbling or warping. It helps to attach a bracket or some way to put it to a stand or the wall.

Once you have all the items in the checklist, you're ready to calibrate the cameras!


## 2) CALIBRATE
The next step is determine the physical position of the two cameras relative to one another mathematically. This allows the software combine mash up the two data streams into one 3D scene.

#### Pick the right environment to calibrate
Calibration requires some ambient infrared light in the room. The sun is a good source but can be too bright if it's direct. The best setting is a living room or studio with large windows where you can get filtered sunlight without it being direct. Bear in mind that windows in newer buildings are often treated with IR-blocking coatings. If neither of those are an option, having access to 'hot lights' that emit heat, such as halogen or tungsten, will work. We've also had good luck with [IR lights](http://www.amazon.com/dp/B0002J1JFE/).

#### Attach the cameras together
**Mount the cameras** Using the mounting solution you chose from above, affix the HD camera to the depth sensor. Shooting requires that the two cameras be securely bound together and not subject to *any* movement in relation to each other. Make sure everything is locked down tight, including the safety catch on your quick release!

**Get an IR diffuser** You'll need something to diffuse the depth sensor’s IR laser projector for one step during calibration the depth camera for the calibration stage. We often use a square of tissue paper, cigarette rolling paper or handkerchief.

**Lock of your zoom** to the widest setting and put a piece of tape over both the zoom ring and the lens body to prevent accidentally zooming later. Zooming after you've calibrated will nullify the calibration.

#### RGBDCapture: Calibrate Lenses 
**Plug in the sensor to your computer and open the RGBDCapture application** depending on which sensor you are using, open the **RGBDCaptureKinect** or **RGBDCaptureXtionPro** application.

**Set your working directory** to a convenient place on your hard drive. All your footage will be stored here. Change it by clicking the text at the top off the RGBDCapture window. The default directory is depthframes, which is inside of your application folder. You’ll definitely want to change this. Observe that the software creates a ‘_calibration’ folder for you inside the project directory. Files are autosaved as you go – so relax, your work will be saved.

**Select Calibrate Lenses tab**, first of the four views on the capture application. It is split in half horizontally; your depth camera stream, if connected via USB, should display on the left, and the right pane should be empty to begin with. If you don’t see the depth camera view, see the troubleshooting page.

**Note about Kinect model number** There are two version of RGBDCaptureKinect application on OS X, one for model #1414 and one for model #1473. Check the bottom of your Kinect to find the model number and open the corresponding capture application.

![Kinect Model No.](http://www.DepthKit.com/images/readme/illus_Kinect_modelNo.jpg)
	
**Capture Lens Properties** In order to accurately calibrate the two cameras, DepthKit needs to understand the subtleties of the camera lenses – imperfect manufacturing processes mean that every lens will be slightly different. These values are called _lens intrinsic parameters_ and describe image size, field of view, optical center of the lens, and any distortion found in the lens. To determine these values we capture and analyze images from both cameras.

**Calibrate Depth Camera** Aim your rig at an area of space which has plenty of ‘visible information’ – featuring different colors, contrasts and depths. Hit the _Self Calibrate Depth Camera_ button at the bottom of the left-hand pane. This will automatically analyze the incoming video stream (great!), and once complete should display results similar to the following results:

![Self Calibrated Depth](http://DepthKit.com/images/readme/calibrated_depth_camera.png)
	
Note the the field of views are symmetrical, and that the principal point is at the center of the depth camera’s fixed 640x480 frame.

To **Capture the HD camera's lens properties** it takes a bit more effort and patience since we don't have a direct software connection to the camera. First, set your camera rig up on a tripod and place your checkerboard on a stand in front, a distance form the camera so that it occupies approximately 1/4 of the frame. Place the board in the top left quadrant, focus, and record a short video from this perspective. Don’t worry if the checkerboard is not exactly horizontal or vertical, but do ensure that the entire checkerboard is in the frame, including the white border around the outside black squares.  Make sure the board is exposed well, evenly lit, and that the lens is focused on it so the corners are crisp. Record a 1-3 second video of this, mindful of keeping the camera very still.

**Repeat this process** at a distance where the checkerboard occupies around 1/9th of the frame, taking 9 more images, making 13 in total.

![Four Up](http://DepthKit.com/images/readme/intrinsicsgif.gif)

Download the clips onto your computer into your project’s working directory, wherever you set it in the first step. It is helpful to add them to a new folder inside ‘_calibration’, called ‘slrIntrinsics’ or something similarly explanatory.

**Set the Square Size (cm)** of the checkerboard inside the application. For reference, use 3.38 if you have used A3 sized checkerboard and 2.54 if you used the A4 sized board. If yours is a different size, measure one square precisely and use that width.

Drag all of the video clips them into the **‘Capture Lenses’** tab’s right-hand window pane. This should automatically start the calibration process. You may need to wait for a few seconds while this takes place; the application selects the middle frame from each video, converts it into a black and white .png which is stored in your working folder's _calibration directory. It uses OpenCV library to determine the checkerboard corners to create a model of the lens.

Once the analysis is complete, the software will display a **‘Total Error’** figure below the checkerboard images. This is the average error across all the calibration images. Alongside this, you can view the individual error margins for each image by scrubbing the mouse from left to right across the calibration image window. A ‘Total Error’ of < 0.200 is desirable. If your calibration has resulted in a larger average error than this, scrub through your image set and look for any outlier images which have an error of > 0.300. Note the filename of any outliers. You can re-perform the analysis at any time, simply by dragging the videos onto the window pane again – this time excluding the erroneous clips. This should improve your Total Error.

![good intrinsics](http://DepthKit.com/images/readme/good_intrinsics.png)
	
If nearly all of your images have high error, you will need to reshoot them. Before you do this, look for elements in your environment which could have caused the error. Is there light streaking across your checkerboard? Check the troubleshooting section for more reasons why you may be getting high error.

Congratulations, you've now sensed the actual structure of your camera lenses to create a model. With this we can now determine the relationship between the two lenses. 

#### RGBDCapture: Calibrate Correspondence
**Navigate to the second tab, labeled Calibrate Correspondence** Now that we have the lens models from the first tab, we can determine the spatial relationship between the cameras. 

If you are using the laser cut mount, you can to pivot the sensor up and down in order to match the field of view (FoV) to the video camera's lens. Ideally the video camera will be able to see everything the depth sensor can see, with a little bit of margin on the top and bottom. 

* Set the checkerboard a few feet away from the camera. 
* Using a live preview mode on your video camera position the top of the board flush with the top of the camera's FoV. Note that the viewfinder and the live preview may differ on some cameras if you are shooting wide format. 
* While looking at the capture application, adjust the sensor's angle on the mount until the view matches, err on the low side to allow the color camera to see a bit more than what the sensor sees. Depending on your lens you may find that your color information appears inside your depth camera’s field of view. There may be some compromises to be made here! The laser cut mounting solution allows for minute adjustment of the depth sensor's angles by loosening the locking (upper) screws. 
* Tighten the upper screws to lock the mount angle – know that from this point onwards it is important to maintain the camera positions relative to each other (hence the fancy mounting system!).

![FoV Adjust](http://www.DepthKit.com/images/readme/Side_Sensor_Kinect_Cam_Close.png)

Now that we've matched the views, we need to take corresponding images of the checkerboard from the two cameras to determine how they sit. Looking back at the capture page, with the checkerboard in each quadrant, you need to capture three images, _one short video clip from the video camera_, _one depth impression_ from the sensor, and one _infrared view of the checkerboard_ from the sensor. This is where the IR light diffuser is important, so make sure that is handy before beginning. A second pair of hands is helpful at this step too.

- First, set the checkerboard centered, in front of the lens.
- Focus the video camera on the board and take a short clip.
- Being very careful not to move the rig at all, go back to the RGBCapture app and click the thumbnail of the depth image on the left. This will capture a snapshot of the image for correspondence to the video clip you just took.
- Diffuse the IR projector with the paper or cloth, its the farthest left lens of on the face of the sensor, the one with the red sparkles coming out. Observe that the graininess disappears from the camera preview, and red dots appear in the corners of the squares on the checkerboard in the preview. Click the second tile to capture an image whilst the red dots are showing.
- If the checkerboard is too dark or no red dots appear, it means you need more ambient IR light. Get closer to the window, or shine a hot light on it from far away. It's important that the board is illuminated evenly and sufficiently.

![IR diffuse](http://www.DepthKit.com/images/readme/illus_diffuse.png)

Repeat this process with the checkerboard at four different depths away from the cameras, making sure to refocus at every plane. The idea is to fill up an imaginary box of checkerboard points in the 3D space in front of the camera. This helps to best interpret the relationship between the two cameras that will work at all distances from the lens. Once you've captured all four sets, download the video clips from the camera and drop them into a new folder in the working directory you set before. One at a time, drag the video files into their corresponding rectangular tiles in the application next to the corresponding depth and IR thumbnails taken from the device. 

With four sets of three images complete, click ‘Generate RGB/Depth Correspondence’. If you get an error it means the algorithm was unable to find an exact fit for the selected checkerboard pairs. Try hitting 'ignore' to excluding a few of the image sets – 'bad apples' may be throwing off the model calculation. Just like before, excluding images may help in this situation. Click ‘Ignore’ on all but one of the images, and attempt to Generate RGB/Depth Correspondence again. When you find an image that allows the process to complete successfully, try combining it with other images. There is some randomness in the algorithm, so it helps to try the same combinations a few times just to see if it “guesses” a better starting place.

![Good Calibration](http://DepthKit.com/images/readme/good_calibration.png)

By pressing the left and right arrows you can cycle through previews of the four checkerboard calibration sets. If it’s correct, you’ll see the checkerboard image data pixels (in black and white) mapped cleanly onto the depth model of the same image. You’ll also see corresponding colored dots floating in space near corresponding to the checkerboard depth planes. Some dots are missing from the grid pattern, as they were removed as outliers while generating the calibration. An ideal calibration will contain dots from at least three different sets of colors. By cycling through all tests checkerboards sets, the checkerboard image should be visibly well aligned to the depth data.

The camera is set up as a video game style WASD first-person camera, using the following controls:
<table>
    <tr>
        <td style="font-weight:bold">Function</td><td style="font-weight:bold">Shortcut</td>
    </tr>
    <tr>
        <td>Move Forward</td><td>w</td>	
	</tr>
    <tr>
        <td>Move Backward</td><td>s</td>	
	</tr>
    <tr>
        <td>Move Left</td><td>a</td>	
	</tr>
    <tr>
        <td>Move Right</td><td>d</td>	
	</tr>
    <tr>
        <td>Move Up</td><td>e</td>	
	</tr>
    <tr>
        <td>Move Down</td><td>c</td>	
	</tr>
	  <tr>
        <td>Rotate Counterclockwise</td><td>q</td>	
	</tr>
	  <tr>
        <td>Rotate Clockwise</td><td>r</td>	
	</tr>
</table>

Once you have a calibration where all the checkerboards depth and image data match up for all the levels, you can move onto recording! As long as your camera and depth sensor lenses stay in position, you won't have to go through the painstaking process again. Phew!

## 3) CAPTURE
**Pre-filming checklist**
Ready to Roll? Navigate to the Record tab in the RGBDCapture application. If connected properly, you will be able to see a preview of your depth camera on the left. Your takes will show on the right side in the format ‘TAKE_MO_DD_HH_MI_SS’, with the numbers corresponding to the time of capture (there will be none before you’ve saved your first take). If it’s still there from the last tutorial, remove the IR projector cover from your depth camera.

**Tethered** When planning your shoot, be aware that your camera operator will not be able to move further from the computer than the depth camera’s USB cable will allow. This distance can be extended with an active USB extender if needed. If you are shooting with an Asus Xtion and a laptop you can go mobile!

**Clap** Each take requires a visual signal to sync the two data streams together. Have someone (or yourself) ready to stand in front of the RGBD rig and clap at the beginning of the each take. It may feel silly at the time, but it is important – it allows you to fine tune the temporal alignment between the video and depth streams later on.

**Rolling**
We follow this convention when on set:

 - RGB DP announces ‘Rolling color...’ and starts recording on the video camera.
 - Data DP announces ‘Rolling depth...’ - and hits **spacebar** in the Record tab of the RGBDCapture application. (Alternatively hit the Toggle Record button). The depth camera preview window should display a red border with a flashing Record button to show that recording is taking place.
 - Clap in front of the cameras to enable alignment later on.
 - __Make magic__
 - hit space bar again to stop recording.

Warning: if you see the 'Toggle Record' button starting to fill with a red bar, it means that some images are failing to save. This usually occurs when the hard drive is nearly full. If this happens, stop recording as soon as possible and wait for the red bar to go down, ensuring that all the footage is written to the drive. If you're recording to an external drive, make sure it's FireWire, USB 3.0, or Thunderbolt.

![unsaved frames](http://DepthKit.com/images/readme/unsaved_frames.png)

When you stop recording you should see your Take appear in the right side of the Record tab. As soon as you finish recording, the application will begin compressing the raw depth data in the background. The progress of this process is shown as a gray bar overlaid on the TAKE description on the top right. It will move all the way to the right when finished. In the meantime, open your working directory. You should see that a TAKE folder has been created with the same timestamp as in the application. Navigate inside this folder and download your DSLR footage into the ‘color’ folder.

It's possible to **preview the recorded depth data** inside of the capture application. In the playback tab, select a Take and hit space bar to play the timeline. Use the same controls from the calibration step to navigate the point cloud as it plays back your capture.

#### Media Bin Preparation 

After a shoot, you'll need to copy the video files into the working directory. For each file you recorded, find the corresponding TAKE folder. Having the camera's clock set correctly is helpful so you can match the time stamps. Within the take directory, put the video file into the color/ folder.

The folder structure for the media bin looks like this:

	WorkingFolder/
		_calibration/
			_matrices/
				6x .yml files generated from the calibration step
 		TakeOne/
			depth/
 				frame_000_millis_00000.png //compressed depth frame, first number is frame # second is millisecond
 				....
			color/
 				MyClip.mov //the movie clip that corresponds to this Take
  				MySLRCLip_Small.mov //optional small version that will be used for offline editing
 		TakeTwo/
 			...

The toolkit allows for the option of having a smaller preview, sometimes referred to as 'offline', version of the video to make visualization fast while keeping export quality top notch. To create an offline video we recommend [MPEG Streamclip](http://www.squared5.com/) or Quicktime Pro 7 to create a 640x360 (assuming you shot in 16:9 aspect ratio) MJPEG @50% speed and remember to include sound. Add _small.mov to the end of the filename and put in the Color folder. This is the clip that RGBDVisualize will load for preview, it will be swapped out automatically when rendering.

Once your files are in place inside their color folders, you’re ready to Visualize.

## 4) VISUALIZE

**Launch RGBDVisualize** You should see the list of takes you just recorded. Only takes with color folders show up, so if you don't see one make sure your folders are complete. Select the take you'd like to visualize and click 'Create new Composition with this Scene.'

Assuming it's the first time loading this scene we need to **create a temporal alignment** by synchronizing the two data streams. You'll be glad you clapped while shooting! On the timeline on the bottom you should see two rows of thumbnails, color and depth. Scrub through them each by clicking on the line of thumbnails and dragging left or right. You'll see previews of the depth data and the RGB video as thumbnails on the top right. With your mouse over the respective timelines can use the arrow keys until you find the clap in both Depth and Color. Once you have the precise moment of the clap selected in both, press "Set Color-Depth Time" on the left. Scrub through the timeline by clicking on the bar with the yellow tickers at the bottom of the main preview pane. You should see the footage playing back with matched temporal synced.

If you make a mistake and find that the time alignment is off, you can highlight the blue marker on the 3rd track of the 'Time Alignment' tab and press DELETE to start over. It's never necessary to set multiple time alignments, so delete the existing ones before the 

![time align](http://www.DepthKit.com/images/readme/time_align.jpg)

Now navigate to the Texture Alignment tab to tweak the X and Y Shift & Scale to align the depth and color information to perfect your alignment.

Just like in the calibrate step, clicking and dragging the mouse rotates the camera. WASD moves you like a first person video game. E and C boom up and down in space while R+Q rotate. Use the "Reset view" button when you get lost in space.

#### COMPOSING 

Each Take can have any number of compositions. A composition lets you render the scene in a different way, with a different in and out point, changing camera perspectives and different rendering styles.

A few tips

- To create more contrast between positive and negative space, change the 'Simplify' level in the Geometry tab.
- To subtract the background from clips, change the Z-threshold.
- The rendering styles are screen-blended onto one another. So you can get a lot of mileage out of combining points, wireframes and meshes together and varying opacities.
- If your interface is getting crowded you can nudge the timeline widths by pulling on the green stripes at the bottom. Shrink them up and the interface will snap back to the bottom giving your render window some more room.

To create a camera track, move the camera to where you'd like to look at the scene and scrub to the point in time you'd like it to be there. Press "Set camera point" on the GUI or press SHIFT+T. You'll notice a blue marker appear on the Camera timeline. You can then move the timeline and the camera to a new location and press SHIFT+T again. By selecting "Lock to Track" or pressing SHIFT+L the camera will travel along this path using your first camera point as an 'in point' and your last as an 'out point.'

You can click and drag the camera points to change their location in time. You can delete them with the Delete or backspace key. By clicking on the triangles to the left or right of the marker and pressing the up or down arrows you can have the camera movement ease in or out represented by a curved arc, or cut (blocky steps.)

The Depth of Field effect can be convincing for simulating a camera language. Draw DOF is selected in the GUI. By setting the Depth Range you can select here the focus plane is in relation to the camera – think of this like turning the focus ring on your camera. Tweak the range and blur to achieve the desired effect. Depth of field keyframes matched to camera moves can create really cool convincing effects simulation racking or tracking focus. The white rectangle on the top left acts as a focus assist by marking the area in focus in black.

Save the composition when you are ready to export or want to experiment with something else. To switch compositions, click the name of the composition at the top and select a new scene.


## 5) EXPORT
Currently you can export out of RGBDVisualize as a PNG image sequences with or without alpha transparency or as a series of textured .OBJ files for use in other programs like Maya, Blender or Cinema 4D.

To export, click on the composition name to view all the scenes. Selecting a scene will show all the compositions in that scene, each of which has a small 'R' button next to it. This stands for Render, and by clicking it you will add this composition to the render queue. If you make changes to that comp you will have to re-add the comp to the queue by clicking the Take in the render queue and re-adding the comp.

Once you've selected all the compositions you wish to render, click the "Start Render Batch >>" button and sit back and relax as all the compositions you've queued up begin to render. Be careful not to press the spacebar – it cancels your render.

#### Export as Image Sequence
The application exports an image sequence by default. Exporting works by rendering a given composition from the perspective chosen in the camera track (what you see in "Lock to Track mode) into a series of PNG frames. The renderer uses the first camera point as an 'in point' and the last as an 'outpoint.'

Render frames are 1920x1080 by default but can be changed on the left-hand side of the app by changing the Frame Width & Frame Height Sliders. There are presets for 720P & 1080P built in below the sliders. Frames are saved into the _RenderBin/ folder underneath the main MediaBin/ (right next to _calibration). Each folder is stamped with the scene, composition and date of export so nothing will ever be overwritten.

The image sequences will be rendered out with the black background as transparent using an Alpha channel for compositing. Except when "Draw DoF" is checked it will remain black. 

#### Export as OBJ Sequence
https://vimeo.com/56143282

In order to export textured OBJ files toggle Export .obj Files on the left-hand panel. This will render out a sequential series of .OBJ files and matching .PNG frames to the _RenderBin/ folder. There will be no accompanying .mtl files included but they can be imported in to Maya. There is a tutorial and import script [here](http://mayapy.wordpress.com/2011/12/19/obj-sequence-importer-for-maya/). Keep in mind that there is no camera tracking or perspective information embedded in these sequences as they are simply texturable 3D files, but it does still use your first and last camera points as in & out points for the render. 


## Troubleshooting
**The application will not launch / crashes / crashes my computer**

 - Maybe your system doesn't support the toolkit. You'll need a computer with accelerated graphics no more than 4 or 5 years old
 - Make sure you have not moved the data/ folder in relationship to the RGBDCapture or RGBDVisualize applications
 - If you are using the Asus Xtion Pro, make sure you’ve installed the [Sensecast drivers](http://sensecast.com/files/Sensecast.and.Libs.Installer.v.0.02.dmg) )
 - If you are still experiencing problems... search the [DepthKit Forum](https://groups.google.com/forum/#!forum/RGBDToolkit)

**My depth camera feed is not showing up in the Calibrate Lenses tab**
 
 - Try disconnecting and reconnecting your depth camera, then restarting the application
 - If you are using Kinect, make sure that you are running the appropriate Kinect capture application (1414 vs 1473), based on the model number on the bottom of the device
 - Occasionally fully restarting the computer has helped with sensors that fail to pick up

**My depth camera’s field of view / principal point don’t match the figures given in the video**

 - If they are only slightly different, don’t worry!
 - Try the process again from scratch by disconnecting devices and relaunching the application
 - Make sure there is information in the scene that falls within the range visible to the sensor (~3’–12’). Check that there is variation in the scene; information in the foreground, middle and background.

**I’m getting high error numbers on the calibrate lenses page**

 - High error may occur when the checkerboard is too close or too far away.
 - Make sure there is no glare on the checkerboard from lights. Even one hot spot from a nearby light could throw off the reading.
 - Make sure that the exposure is set properly on the camera – if the whites of the checkerboards are too bright sometimes you need to shoot it again at a slightly darker exposure. 
 - Make sure you refocused on the checkerboard at every stage and that your aperture is no too low, making the depth of field shallow. 

**My correspondences are not detecting or way off**

 - Confirm that you have a low error on the first stage.
 - Make sure that your set up is totally stable when capturing the correspondence images. A wobbling checkerboard or camera tripod will throw things off.
 - Often this will happen if there is not enough ambient IR light, get closer to a window 
 - Conversely if there is too much or uneven lighting it'll also blow out your checkerboard
 - Try different depths from the camera, being wary moving it too close or too far.

**My recordings are dropping frames**

 - Close any other apps.
 - Make sure you are plugged into wall power
 - If writing to an external hard drive make sure it's USB 3.0 or FireWire 800

**The application crashes when I try to load movie files from the HD camera**

 - Make sure your video files are compatible with the toolkit, H.264 or ProRes MOV’s.
 - Make sure you have the latest version of Quicktime installed
 - Make sure you are running the application from a location where you have write access

**My texture alignment is way off**

 - Try using the X & Y shift and Scale in the Texture Alignment tab to accommodate for slight inaccuracies 
 - You may want to recalibrate, which is fine to do after you've shot as long as the relationship with the camera is still fixed

**My time alignment is way off**
 
 - Delete any markers on the 3rd "Alignment" track on the timeline to start over.
 - Look for a very decisive temporal moment to align to, meaning that there is a specific fast movement which allows for precisely selecting a depth and video frame from close times. Because the cameras have different frame rates and clocks, the alignment will never be perfect but should not drift over time.

 Send any questions to the [DepthKit Google Group](https://groups.google.com/forum/?fromgroups#!forum/RGBDToolkit)







