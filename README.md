![alt text](https://github.com/tojynick/Stylized-Water-Shader/blob/main/Readme%20Resources/Thumbnail.png)

## ⚠️ Attention ⚠️
This package is still **work in progress**. I will add more features, write proper documentation and make the usage easier and more intuitive. For now, **use at your own risk!**

## Getting Started 🚀
You can install the package in Unity's Package Manager.
1. Go to **"Windows"**
2. Open **"Package Manager"**
3. Click **the plus icon** in the top left
4. Press **"Add package from git URL...**
5. Enter https://github.com/tojynick/Stylized-Water-Shader-Unity-URP.git
6. Press **"Add"**
7. Add **"Prototype Pool"** under **"Samples"**
7. Enjoy 💖

## Features ✨
* **Shallow and deep colors**
* **Foam**, both *simple* and *advanced*
* **Transparency and distortions**
* **Waves**
* **Caustics**
* **Mobile optimized!**

### Toggleable Features
* **Distortions** - simulates refraction by reading from opaque texture using distorted UV, **expensive**. *Requires Opaque Texture to be enabled.*
* **Caustics**
* **Waves**
* **Foam Type** - simple or advanced. Simple is cheap, advanced is expensive, but gives you much more control.

## Important Notes ⚠️
### Compatability
The shader is tested only in **Unity 2021** and only with **URP**, so I cannot guarantee it will work properly in earlier versions of Unity or different render pipelines.
### URP Settings
Please make sure that **Depth Texture** and **Opaque Texture** are enabled in your URP settings. Without it the shader will work incorrectly.

## Example 👀
![alt text](https://github.com/tojynick/Stylized-Water-Shader-Unity-URP/blob/main/Readme%20Resources/Beach%20Example.gif)
