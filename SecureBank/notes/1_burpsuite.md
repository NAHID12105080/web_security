start burpsuite

```bash
chromium --user-data-dir=~/chromium-proxy --proxy-server=127.0.0.1:8080 --ignore-certificate-errors --proxy-bypass-list="<-loopback>" &
```
