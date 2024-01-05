# STL_LDMO_project

## Getting Started
Python implementation of the main results for the paper entitled:
_Conformal prediction of molecule-induced cancer cell growth inhibition challenged by strong distribution shifts_


## Data split
Utilizing the UMAP-based clustering method, 7 clusters were derived for non-outlier molecules, with the outlier set forming its distinct cluster. 
 
<img width="606" alt="cell_split" src="https://github.com/Sahet11/STL_LDMO_project/assets/50385322/607ac164-52c6-49ec-a75e-46e9ca8e2be4">

## Prerequisites
- Python 3.9.7

## Usage

1. Download and store the from the [NCI-60 Growth Inhibition Data](https://wiki.nci.nih.gov/display/NCIDTPdata/NCI-60+Data+Download+-+Previous+Releases). 
   1. The required files contain the endpoints calculated from concentration curves ("CANCER60GI50_Oct2020.LST", for instance) and SMILES ("Chem2D_Jun2016.smi", for instance). 
      Other releases of both files are also available for download.

To run:
```python
jupyter notebook code_Figure5.ipynb
jupyter notebook code_Figure6.ipynb

```

Output:
Figures 5 and 6. 

### License
MIT

### Contact

1. Saiveth Hernández-Hernández, email: saiveth.hernadez@inserm.fr
2. Pedro J.Ballester, email: p.ballester@imperial.ac.uk
