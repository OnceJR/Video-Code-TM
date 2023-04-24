from moviepy.video.io.VideoFileClip import VideoFileClip

def generate_thumbnail(video_file):
    clip = VideoFileClip(video_file)
    thumbnail = clip.save_frame("thumbnail.jpg", t=0.5)
    return thumbnail
