# Manual for Meta Spark Studio Augmentations

## 1. Introduction
This manual provides comprehensive instructions for using the Meta Spark Studio Augmentations project. Aimed at users who wish to create or modify augmented reality experiences, this guide will take you through the process from setup to publishing.

---

## 2. Getting Started
Before beginning, ensure you have Meta Spark Studio installed on your computer and you have access to a smartphone compatible with the Meta Spark Player app for testing your AR experiences or a personal Facebook account.

---

## 3. Project Setup
To work on an AR poster project:

1. Navigate to the desired poster's AR folder (e.g., "poster A AR").
2. Inside the folder, you will find assets such as materials, the project file (`.arproj`), scene files, and textures.
3. The interface presents the project in a scene editor, where you have a 2D view by default.

---

## 4. Editing Projects

### Finding and Editing Properties:

#### Properties Panel:
On the right side of the Meta Spark Studio interface, the properties panel allows you to adjust the properties of selected objects, such as position, scale, rotation, and visibility.

#### Textures:
Textures can be found in the 'Assets' panel of the Meta Spark Studio interface. To access them:
- Click on the 'Assets' panel, typically located at the bottom of the interface.
- Look for a section labeled 'Textures' where all imported texture files are listed.

#### Materials:
Materials are also located in the 'Assets' panel:
- Within the 'Assets' panel, navigate to the 'Materials' section to find all the materials created or imported for your project.

### Managing Assets and Materials:

#### Reorganizing Assets:
Click and drag an asset to a new location within the 'Assets' panel to reorder it. Create folders to group similar assets together if necessary for better organization.

#### Adjusting Material Assignments:
Drag and drop a material from the 'Assets' panel directly onto an object in the scene to apply it. To change the material of an existing object, select the object and then in the 'Properties' panel, click on the material preview to choose a different material.

### Editing in 2D:

The 2D view is suitable for layout and positioning tasks. You can drag elements around the canvas to reposition them. For editing that involves depth, switch to the 3D view for more accurate adjustments.

### Positioning Objects:
To position objects in your scene:
- Select an object to reveal the gizmos for interactive movement, rotation, or scaling.
- Use the gizmos to move the object in the scene or adjust the values in the properties panel for precise positioning.

### Steps for Editing Textures and Materials:

To change a texture, locate the texture in the 'Assets' panel, right-click and choose 'Replace' to upload a new image.

To adjust materials, select the material in the 'Assets' panel and use the inspector to modify properties such as Diffuse, Specular, and Normal maps.

### Adding and Managing Audio:
Meta Spark Studio supports various audio formats, including MP3, WAV, and M4A. To add and manage audio:
- Import audio files (M4A format) into the 'Assets' panel.
- Drag and drop audio files from the 'Assets' panel onto objects in the scene or use the audio player feature to control playback in the properties section. 

### Adding Videos and Animations:
- To use videos or GIFs in Meta Spark Studio, convert them into a sequence of images (frames). This can be done using online converters or video editing software.
- After conversion, import the series of images into the 'Assets' panel in Meta Spark Studio.
- To animate these images, use the animation feature in Meta Spark Studio. This involves creating a new animation sequence and add your images to it.
- Set the display duration for each image to control the speed of the animation. This timing should mimic the original frame rate of the video or GIF for a smooth playback.
- You can control the animation using the properties panel or the Patch Editor for more advanced interactions.

### Implementing Buttons and Interactive Elements:
To create interactive experiences with image-based buttons using the Patch Editor:
- Import the image you want to use as a button into the 'Assets' panel.
- In the scene, add a plane and apply the imported image as a texture.
- Open the Patch Editor and create an interaction patch. Connect the object to an 'Object Tap' patch, and then link it to the desired action, like 'Switch' or 'Animation', to define what happens when the button is pressed.

---

## 5. Testing Your Project
Testing is an essential step to ensure that your AR experiences function as intended. Meta Spark Studio offers convenient options for testing on a device.

### Testing on a Smartphone:
- Use the 'Test on Device' feature in Meta Spark Studio to send your AR experience to a connected smartphone.
- For testing via the Meta app:
  - Make sure you have the Meta Spark Player app installed on your smartphone.
  - After using 'Test on Device,' open the Meta Spark Player app on your smartphone to view and interact with your AR experience.
- For testing as a Facebook preview:
  - Ensure you have a Facebook account linked to Meta Spark Studio.
  - Use the 'Test on Device' feature and choose the option to send a preview to your Facebook account.
  - Open the Facebook app on your smartphone, and you should find the AR experience available as a preview in your Facebook 'notifications' section.

---
## 6. Publishing Your AR Project
Once your AR project has been thoroughly tested and you're satisfied with it, you can publish it for others to experience on Facebook.

### Steps for Publishing:
1. In Meta Spark Studio, navigate to the 'Publish' button, typically located in the lower-left corner of the interface.
2. Follow the prompts to submit your AR project. This will involve providing details like the project name, description, and a thumbnail image.
3. After submission, your project will go through a review process by the Meta team. Once approved, it will be published and made available for use.

### Finding Your Published AR Experience on Facebook:
- After your AR project is published, it can be accessed on Facebook, particularly when users are creating stories.
- To find your AR experience, users can go to the effects section while creating a story on Facebook and type in the effect name. Your AR experience will be listed among other available effects if they follow you or have used your effect before.

---

#### Tips for Effective Editing:

- Always save your changes frequently to avoid losing any work.
- Use layers to organize elements of your AR scene for easier management and editing.
- Utilize the Patch Editor to create interactive elements without coding by connecting visual 'nodes' that represent functions or actions.
