# GPU-Accelerated Single-Cell Genomics Analysis with RAPIDS
This resource contains example notebooks demonstrating how to use RAPIDS for GPU-accelerated analysis of single-cell sequencing data.

RAPIDS is a suite of open-source Python libraries that can speed up data science workflows using GPU acceleration.Starting from a single-cell count matrix, RAPIDS libraries can be used to perform data processing, dimensionality reduction, clustering, visualization, and comparison of cell clusters.

Several of our examples are inspired by the [Scanpy tutorials](https://scanpy.readthedocs.io/en/stable/tutorials.html) and based upon the [AnnData](https://anndata.readthedocs.io/en/latest/index.html) format. Currently, we provide examples for scRNA-seq and scATAC-seq, and we have scaled up to 1 million cells. We also show how to create GPU-powered interactive, in-browser visualizations to explore single-cell datasets.

Dataset sizes for single-cell genomics studies are increasing, presently reaching millions of cells. With RAPIDS, it becomes easy to analyze large datasets interactively and in real time, enabling faster scientific discoveries.

# Getting Start with the Jupyter Notebooks:
To help you get started, we have created several Jupyter Notebook that can be easily deployed on Vertex AI using NGC’s quick Deploy feature. This feature automatically sets up the Vertex AI instance with an optimal configuration, preloads the dependencies, runs the software from NGC without any need to set up the infrastructure.

Simply click on the button that reads “Deploy to Vertex AI” and follow the instructions.

Note: A customized kernel for the Jupyter Notebook is used as the primary mechanism for deployment. This kernel has been built on Single Cell Examples container. For more information on the container itself, please refer to this link for more information:

[https://catalog.ngc.nvidia.com/orgs/nvidia/teams/tao/containers/tao-toolkit-pyt
](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/clara/containers/single-cell-examples_rapids)
The container version:

nvcr.io/nvidia/clara/single-cell-examples_rapids:latest
