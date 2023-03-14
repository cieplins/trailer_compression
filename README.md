# trailer_compression
 
This repository contains Python software for movie trailer compression. Algorithm splits the video into scenes, compresses each scene with given CRF and resolution, picks the scene closest to the desired VMAF score and concatenates the scenes into final video. 
Requirements:
ffmpeg, vmaf, moviepy, scenedetect