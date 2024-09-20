I have been exploring to add koch arm extensions for camera mounts. Mainly to always have them at fixed positions relative to the robotic arm, due to the reason that the results change a lot if the camera positions during evaluation even slightly misallign with the positions used when recording for training datasets.

### Camera Hardware
I have setup 4 cameras, two on the sides, one on the top and one on the gripper. https://www.amazon.com/dp/B0CLRJZG8D?ref=ppx_yo2ov_dt_b_fed_asin_title is the camera i am using. Its manual focus adjustment helps better setup gripper focus to its much closer position.

<img src="https://github.com/user-attachments/assets/0d85f264-9a0e-4fa7-9843-6e3e91b9b37c" alt="drawing" width="200"/>


### 3D Mounts
I have added some 3d models (work in progress)  to mount them easily to the arm:
-  [Gripper_Cam_Mount.stl](https://github.com/meetsitaram/koch-v1-1/blob/main/hardware/follower/STL/Gripper_Cam_Mount.stl) for the gripper cam

![cam_mount](https://github.com/user-attachments/assets/b58e027a-ba2a-40bb-a389-1dd48e1a94ed)

- [Base_With_Cam_Mounts.stl](https://github.com/meetsitaram/koch-v1-1/blob/main/hardware/follower/STL/Base_With_Cam_Mounts.stl) for the side cams, although I haven't yet set this up for my recordings.

- I couldn't find a proper setup for the top cam and just attached the top camera to a reading lamp right now

### Camera View
![4-cam-view](https://github.com/user-attachments/assets/31b007e8-9830-4482-8443-99b86942fcf4)
