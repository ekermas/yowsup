docker build -t yowsup -f Dockerfile .
docker run -d --name yowsup yowsup tail -f /dev/null
docker exec -it yowsup /opt/yowsup/yowsup-cli demos --debug --login 79067894485:hKEag9s8mZiKitx3Z90pI9ULK+s= --yowsup --output json