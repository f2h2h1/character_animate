#说明    
这是一个基于网页的字符画    
需要浏览器支持video标签 canvas blob    
可以直接打开本地的mp4文件输出字符画    

#实现原理    
使用input标签打开本地视频文件    
使用FileReader和blob，使得video标签可以播放input的视频文件    
把视频渲染到一个canvas标签上    
使用canvas获取视频每一帧的画面    
把每个画面的每个像素转换为灰度值，再根据灰度值转为为字符，最后输出到一个div标签上    

#demo地址    
http://www.kolasyotaka.byethost24.com/character_animate.html    