1. Extract all the files from the zip file
2. Change directory (cd) to the extracted folder, and save any test data into this root folder
3. Create a new virtualenv and install packages from requirements.txt:
 virtualenv cw_env
 cd cw_env
 source bin/activate
 cd -
 pip install -r requirements.txt
4. Copy and paste the following code to open the IPYNB:
 jupyter notebook MLP_testing.ipynb
 jupyter notebook SVM_testing.ipynb
