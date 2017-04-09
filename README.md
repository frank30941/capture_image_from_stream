# capture_one_image_from_stream
capture one image from stream using ffmpeg.

Video protocols 
HTTP:
  ffmpeg -i {HTTP://XXX.XXXX.XX/XXX} {loacl/path/img.jpg}
RTSP(TCP、UDP):
  ffmpeg -rtsp_transport {tcp or udp} -i {RTSP://XXX.XXX.XX/XXX} {loacl/path/img.jpg}
