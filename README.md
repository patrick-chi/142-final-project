# 142-final-project
Development of a supervised learning ANN model applied to the ANI- 1 data set.


### Jupyter Notebook environment configuration
Configure conda first with the following commands:
   
    ```bash

    module load anaconda3
    conda init bash
    source ~/.bashrc
    ``` 
   
   Use Eric's environment which has all required dependencies for the ANI project (torch, torchani, numpy):
   
   ```bash
   conda activate /global/scratch/users/ericwangyz/chem242/ani
   python -m ipykernel install --user --name=ani
   ```
   
   Then you'll see the kernel in Jupyter Notebook:
   
   <img src="./jupyter_kernel.png" width="800" />
   
   **Note**: If you are using Eric's environment, please don't install any other packages to this environment.
    
