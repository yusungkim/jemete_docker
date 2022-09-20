# JMETER

https://bytemeta.vip/repo/mkbyme/docker-jmeter-vnc-remote

## Run Server
```bash
# Run command with mapping to local port 5901 (vnc protocol) and 6901 (vnc web access):
docker run --rm --name jmeter-gui --volume $(pwd):/srv -p 5901:5901 -p 6901:6901 mkbyme/docker-jmeter-vnc-remote
```

## Access
```bash
http://localhost:6901/?password=12345678@Abc
```

## シナリオ作成 
youtube https://www.youtube.com/watch?v=os_DxIE3moI