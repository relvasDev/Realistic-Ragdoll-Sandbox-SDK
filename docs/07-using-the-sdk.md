# Using the SDK
1. Drag your character into the scene, remembering that texturing is not the responsibility of the SDK. The user must have basic knowledge of Unity:

 ![ImportSDK](../assets/UsingSDK/UsingSDK1.png)

2. To open the SDK, go to RRS/Character Creator:

 ![ImportSDK](../assets/UsingSDK/UsingSDK2.png)
 
3. Drag the character in the scene to the Character field in the SDK and click Next:

 ![ImportSDK](../assets/UsingSDK/UsingSDK3.png)

4. Adjust the positions and scales of the ragdoll colliders by clicking on the spheres, turn off symmetry if necessary:

![ImportSDK](../assets/UsingSDK/UsingSDK4.png)

5. Adjust the limits of the ragdoll joints. The yellow axis is the most important. Click on the red spheres to select them and turn off symmetry if necessary:

![ImportSDK](../assets/UsingSDK/UsingSDK5.png)

6. Change the axes until they match the following images:

![ImportSDK](../assets/UsingSDK/UsingSDK6.png)

![ImportSDK](../assets/UsingSDK/UsingSDK7.png)

![ImportSDK](../assets/UsingSDK/UsingSDK8.png)

![ImportSDK](../assets/UsingSDK/UsingSDK9.png)

7. Drag the weapon provided with the SDK into the Weapon field:

![ImportSDK](../assets/UsingSDK/UsingSDK10.png)

8. Drag the animation provided with the SDK into the Weapon Pose field:

![ImportSDK](../assets/UsingSDK/UsingSDK11.png)

9. Adjust the weapon in the character's hand, click on the sphere to select the weapon, and use the SDK buttons to change its position or rotation:

![ImportSDK](../assets/UsingSDK/UsingSDK12.png)

10. Select whether the character is female or not and click Create to create a prefab that will be saved in Assets/RRS_Characters:

![ImportSDK](../assets/UsingSDK/UsingSDK13.png)

The process may take a while:

![ImportSDK](../assets/UsingSDK/UsingSDK14.png)

An AssetBundle of the character will be generated in:
Project folder/ Build/ Workshop/ Character name + _ + ID. Do not rename this folder, it will be sent to the Workshop.

Inside this folder, there must be a png file called Preview with dimensions of 512 x 512. There are two options here:
1. Place the desired image in the folder and rename it to Preview.png;
2. Generate the image in the SDK:

Drag a camera from the scene to the camera field:

![ImportSDK](../assets/UsingSDK/UsingSDK15.png)

(Optional) Drag the animation provided with the SDK to the Screenshot Pose field:

![ImportSDK](../assets/UsingSDK/UsingSDK16.png)

Adjust the camera position and press Screenshot:

![ImportSDK](../assets/UsingSDK/UsingSDK17.png)

The image is now saved in the folder. You can click Finish to complete the Unity part.
 
[⬅️ Previous](06-installing-the-sdk.md) | [Next ➡️](08-workshop-upload.md)


