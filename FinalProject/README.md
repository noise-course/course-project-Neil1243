**ML for Computer Systems Project**

This project reproduces baseline malware classification results using the netML Malware dataset and nPrint features. The repository contains the Jupyter notebook, the Sphinx report, and all code needed to run the experiments. The dataset itself is not included because it is too large, so you will need to download it before running the notebook.

**Dataset Setup**

1. Download `traffic.pcapng.gz` from the netML Malware benchmark page — https://nprint.github.io/benchmarks/malware_detection/netml_malware.html
3. Create a folder named `data` in the root of this repository.
4. Place the file `traffic.pcapng.gz` inside the `data` folder.
5. Keep the filename exactly the same, since the notebook expects this name.

**How to Run the Notebook**

1. Open the notebook in Jupyter or Google Colab.
2. Make sure the `data` folder is present in the same directory as the notebook.
3. Run all cells from top to bottom.
4. The notebook will load and decompress the dataset, extract features, train the models, and produce the plots.

**Included Files**

- The main Jupyter notebook with all code.
- TA pdf of my project report

**Notes**

The notebook has been written so that it can be run with a single pass. No manual editing of paths is needed as long as the dataset is placed in `data/traffic.pcapng.gz`.
