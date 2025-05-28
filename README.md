# OmniCellX
OmniCellX enables you to provide a browser-based interface to analysis or visualize single cell data.

Features include:
<ul>
  <li><b>Docker-based installation</b>: Simplifies deployment with no configuration needed, ensuring scalability for both small and large datasets.</li>
  <li><b>Dual-mode operation</b>:<li>Analysis mode: Integrates tools for dimensionality reduction, clustering, differential expression, cell-cell communication, and trajectory inference.</li></li>
</ul>

# How to installation
Firstly, users should pull the docker image:
```
docker pull longrw/omnicellx
```
then start an app container:
```
docker run -itd -p 8000:8000 longrw/omnicellx
```
or
```
docker run -itd -p yourIP:8000:8000 -e ALLOWED_HOSTS="yourIP" longrw/omnicellx
```
After installation, user can use omnicellx by `http://localhost:8000/omnicellx/` or `http://yourIP:8000/omnicellx/` through the web browser.

# testdata
