
# Umap / Tsne

This repo contains a series of notebook to arrange cultural artifacts and explore patters in metadata.

<p align="center">
        <img alt="t-SNE" width="100%" height="" src="https://raw.githubusercontent.com/sinanatra/tsne/master/data/test_UMAP.png" />
</p>


Requirements
----------

Install PIP requirements with `pip install -r requirements.txt`.


Add a folder of images, in the assets folder, and then edit the `folder` path: `folder = './assets/CUSTOM_DATASET/'` inside the notebooks.

Insert a csv file inside the `./assets/` folder and link it in the specific notebooks when working with text.

Notebooks
-----
- `save_wikidata_images.ipynb` creates a folder of images from a Wikidata query
- `image_tsne.ipynb` creates a tsne map from a folder of images based on visual similiarities
- `image_tsne.ipynb` creates a tsne map from a folder of images based on visual similiarities
- `image_umap.ipynb` creates a umap map from a folder of images based on visual similiarities
- `metadata_umap.ipynb` creates a umap map from a folder of images based on values specified in a custom csv file.
- `image_shortest_path.ipynb` calculates the shortest path from an image to other.



