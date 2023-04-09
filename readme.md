Steps to run the application:  
Step 1: Create a copy of the project  
Step 2: Open anaconda prompt and change current path to StreamlitApp folder (where you can find 'app.py' file)  
Step 3: Create a virtual environment, using the command below-  
conda create -n environment_name python=3.10  
Step 4: Activate the virtual environment, using the command below-  
conda activate environment_name  
Step 5: Use the command below to install requirements for tensorflow-  
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0  
Step 6: Use the command below to install required dependencies-  
python -m pip install -r requirements.txt  
Step 7: Run the application by command-  
streamlit run app.py  