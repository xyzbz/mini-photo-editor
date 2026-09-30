# 中文docekr镜像

本项目基于以下项目，汉化后的中文Docker版本。
下载本项目中mini-photo-editor-zh-v0.1.1.zip文件，解压出docker打包镜像（因上传文件超过25M），所以二次压缩。
导入docker本地镜像库，需要设置一下映射端口即可。


演示地址https://img.dawnlife.qzz.io/

已上传docker hub 

docker pull xyzbz/mini-photo-editor-zh



# mini-img-editor

Online webgl2 photo editor  
(https://mini2-photo-editor.netlify.app)  


![Screenshot](screenshot.jpg)  

100% privacy! images are edited locally in the browser, no uploads to backend server.

Current features: 
* Crop
* Perspective correction
* Image resize
* Lights and colors adjustments
* Vignette
* Clarity/ sharpening
* Noise reduction
* Color curves
* Insta-like filters
* Image blender
* Bokeh/lens and gaussian blur
* Heal brush (telea inpaint algorithm)
* Split view before-after
* Color histogram
* Exif/Tiff/GPS info
* Display-P3 color space
* sRGB correct workflow (linear sRGB)
  
  
Notes: 
* file formats support depends on the browser/ platform being used (eg HEIC open natively in MacOS Safari, JPEG-XL and AVIF in Safari and Chrome, ...)
* 16-bit images can be opened but shaders and download is currently limited to 8-bit due to webgl limitations

Please leave feature requests in the issues section (ideally showing a real life example) and I'll see what I can do.  
 
 
Powered by [mini-js](https://github.com/xdadda/minijs), [mini-gl](https://github.com/xdadda/mini-gl) and [mini-exif](https://github.com/xdadda/mini-exif)
