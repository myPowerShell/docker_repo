# firefox

Local build/run:
sudo docker build . -t firefox
docker run -it --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix firefox



Remote build/run:
sudo docker build -t="mypowershell/firefox" github.com/mypowershell/firefox
sudo docker run -it --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix mypowershell/firefox

