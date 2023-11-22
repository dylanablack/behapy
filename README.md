# behapy
Behavioural neuroscience data wrangling and analysis tools

## Installation

Execute the following from the project folder in a shell with conda on the path:

```bash
conda env create -f environment.yaml
conda activate behapy
pip install -e .
```

## Examples

There is a MedPC event reading example in the examples subfolder. This example by default assumes MedPC data files are in the same folder as the notebook file.

## Processing steps

### Converting source data to bids

```{bash}
tdt2bids session_fn experiment_fn source_dat
```

### Visualise the data for QC. 

```{bash}
ppd .
```

### Preprocess the data.

Process the data using the preprocess executable from within BIDSROOT. 

```{bash}
preprocess . 
```



