# RS-DAT

The Remote Sensing Deployable Analysis environmenT (RS-DAT) is a framework for setting up an environment for exploration and analysis of remote sensing data on high-performance/high-throughput computing (HPC/HTC) systems and associated storage resources. It builds on the Pangeo ecosystem to seamlessly integrate and extend the Python and PyData ecosystem, including Dask and Xarray, and provides tools for data storage and retrieval on mass storage systems (e.g., dCache at SURF).

## How can I deploy RS-DAT for my use case?
RS-DAT consists of multiple components to allow its use on different computing infrastructures, such as [Snellius](https://www.surf.nl/en/services/snellius-the-national-supercomputer), [Spider](https://www.surf.nl/en/services/high-performance-data-processing) and [Research Cloud](https://www.surf.nl/en/services/surf-research-cloud) offered by [SURF](https://www.surf.nl/en/about), or university computing infrastructures such as [DelftBlue](https://www.tudelft.nl/dhpc/system). Please refer to the [deploy documentation](https://rs-dat.github.io/RS-DAT/deploying/jupyter_dask_on_slurm/) on how to deploy RS-DAT on various computing infrastructures.

## Use cases
RS-DAT has been applied to multiple Earth Observation (EO) use cases. Feel free to explore the [use cases](https://rs-dat.github.io/RS-DAT/examples/) and see if there are relevant examples for your case.
