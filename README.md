# OmniCellX
OmniCellX enables you to provide a browser-based interface to analysis or visualize single cell data.

<b>Features include</b>:
<ul>
  <li><b>Docker-based installation</b>: Simplifies deployment with no configuration needed, ensuring scalability for both small and large datasets.</li>
  <li><b>Dual-mode operation</b>:<ol><li>Analysis mode: Integrates tools for dimensionality reduction, clustering, differential expression, cell-cell communication, and trajectory inference.</li><li>Visualization mode: Offers interactive, customizable visuals for publication-ready figures.</li></ol></li>
  <li><b>Multi-format support</b>: Compatible with diverse single-cell platforms (e.g., 10x Genomics, Smart-seq2).</li>
  <li><b>Efficient data handling</b>: Uses AnnData objects for memory/computational efficiency, scaling to millions of cells.</li>
  <li><b>Customization</b>: Adjustable parameters enable real-time fine-tuning for tailored analyses.</li>
  <li><b>Comprehensive documentation</b>: Detailed guides and tutorials for troubleshooting and advanced use cases.</li>
</ul>

# Deployment and Usage
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
