##基于videojs的视频直播播放器
[演示地址](https://fzninja.github.io/#/assembly/fz-live)
####引入相应js和css,在页面添加相应播放器代码既可解析播放m3u8格式直播流,播放器格式如下
		<video id="my_video_1" class="video-js vjs-default-skin" controls preload="auto" width="1000" height="500" data-setup='{}'>
    		<source src="./src/z.m3u8" type="application/x-mpegURL">
 		</video>
 > demo中m3u8路经为视频测试路经,根据自己需求进行更改
