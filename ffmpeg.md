# use this command to screen record using ffmpeg on ubuntu

ffmpeg -video_size 1920x1080 -framerate 30 -f x11grab -i :0.0 recording.mp4
