## To run:
python camera_image/scripts/ip_camera.py -u http://192.168.100.2:8080/video

replace ip address with your camera's. 

## To test frame rate:
rostopic hz --window=1000 /camera_image
