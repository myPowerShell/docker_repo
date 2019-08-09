# firefox

Local build/run:
sudo docker build . -t firefox
docker run -it --rm firefox



Remote build/run:
sudo docker build -t="mypowershell/firefox" github.com/mypowershell/firefox
sudo docker run -it --rm mypowershell/firefox

