# tsanfleuron_glacier_data

This Git hosts some file example, and a juypter notebooks that reads them, associated with the unpublished paper "Ice volume and bedrock estimation using geostatistical methods and GPR measurements : Application on the Tsanfleuron and Scex Rouge glacier, Swiss alps"

## Dependencies

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following packages.

```bash
pip install numpy pickle pandas matplotlib jupyter-notebook
```

## Files

The folder "data" contains :
- the DEM acquired in ASCII format
- the Conditionning points used for simulation in ASCII format

The folder "simulations" contains :
- one exemple of bedrock simulation for the MPS and SGS, and the Kriging.
- one exemple of flow accumulation  for the same MPS and SGS simulation, and the Kriging.
- the mean SGS and MPS simulation, with the point by point standard deviation.
All the simulations are in binary format.

The notebook presents how to read the files and display them. 

## License
[MIT](https://choosealicense.com/licenses/mit/)