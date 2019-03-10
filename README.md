## 说明
- 这是一个基于网页的字符画
- 需要浏览器支持 video 标签 canvas blob
- 可以直接打开本地的 mp4 文件输出字符画
- 推荐使用 edge 或火狐打开

## 实现原理
1. 使用 input 标签打开本地视频文件
2. 使用 FileReader 和 blob ，使得 video 标签可以播放 input 的视频文件
3. 把视频渲染到一个 canvas 标签上
4. 使用 canvas 获取视频每一帧的画面
5. 把每个画面的每个像素转换为灰度值，再根据灰度值转为字符，最后输出到一个 div 标签上

## demo地址
http://www.kolasyotaka.byethost24.com/character_animate.html
