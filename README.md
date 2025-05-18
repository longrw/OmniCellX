# OmniCellX
OmniCellX enables you to provide a browser-based interface to analysis or visualize single cell data.

```
docker pull longrw/omnicellx
```
then
```
docker run -itd -p 8000:8000 longrw/omnicellx
```
or
```
docker run -itd -p yourIP:8000:8000 -e ALLOWED_HOSTS="yourIP" longrw/omnicellx
```
