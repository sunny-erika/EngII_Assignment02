# WriteUp Assignment 02 Erika Wood - in Progress

Assignment Link: https://utah.instructure.com/courses/716072/pages/assignment-02

Download Link for Game.exe: https://github.com/sunny-erika/EngII_Assignment02/raw/main/MyGame_.zip

Mushroom Shape GIF: 

![ReleaseX64MyGame](https://github.com/sunny-erika/EngII_Assignment02/blob/main/WindowCapture_GameExe.gif)

Summary Write-Up:

Code that binds the effect and draws the mesh:

![image](https://user-images.githubusercontent.com/63023478/134995600-1bc59330-d2d8-4f13-9cd5-32edd4538f82.png)

Started with a triangle:

![image](https://user-images.githubusercontent.com/63023478/134995676-2734042a-b1fa-4a59-bafb-d1ef04096d9a.png)

Changed to a rectangle:

![image](https://user-images.githubusercontent.com/63023478/134995727-0251c62d-f6e5-404d-a4e2-f3ee463218ee.png)

And then I created my own shape (mushroom) as shown on the top of the page.

Another task was to use a Direct3D GPU capture in the VS Graphics Analyzer:
- Render target when it is all black (the ClearRenderTargetView() function is highlighted)

![image](https://user-images.githubusercontent.com/63023478/135000704-9280d730-34a6-4f7e-83e9-7cc6c947a666.png)


- render target with the mesh (the Draw() function is highlighted) 

![image](https://user-images.githubusercontent.com/63023478/135000944-829baf53-4633-4d7d-8439-a086c5e34585.png)


- Pipeline Stages tab is selected, and the mesh is visible as "wireframe", where the two triangles are visible

![image](https://user-images.githubusercontent.com/63023478/135001091-2e14919e-fa4c-46fc-93da-d987d71a47d7.png)


In addition the OpenGL GPU capture had to be created in RenderDoc:
- Render target when it is all black (the glClear() function is highlighted, and the Texture View tab is selected)

![image](https://user-images.githubusercontent.com/63023478/134999848-52d6e6c5-db16-4ab5-a65c-fd1c328ddece.png)


- Render target with the mesh (the glDrawArrays() function is highlighted and the Texture View tab is selected)

![image](https://user-images.githubusercontent.com/63023478/134999677-d7a58832-754d-4cb6-9937-9b7d775675f4.png)


- Mesh's two triangles (the glDrawArrays() function is highlighted but the Mesh Output tab is selected, and either the VS Input or VS Output sub-tab is selected)

![image](https://user-images.githubusercontent.com/63023478/134999790-0c84aed7-99aa-43ef-b2c2-2826203932e2.png)

•	Summary of issues I encountered and solutions I found
![image](https://user-images.githubusercontent.com/63023478/135004246-65153403-f9d6-4cef-9e90-4131e18ad2d6.png)

![image](https://user-images.githubusercontent.com/63023478/135004287-b0cef38b-44bf-441b-8103-ac7a167a6d51.png)


