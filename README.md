END to END ML model for the binary prediction of ASK-1 inhibitors using python script. 

*****

After installing the requirements in an Virtual Environment
or creating a new environment using conda by using "environment_dependencies.yml" file
just open the command prompt or Terminal in the above created virtual environment
run the command given below
### Using Logistic regression Algorithm based prediction
python predict_logReg_rdkit.py test.smi

### OR 
### Using SVM Algorithm based prediction
python predict_svm_rdkit.py test.smi

similarly, for any unknown molecule when just use the command by specifying the path
of "*.smi" file.

python predict_name_of_algorithm.py [specify_path]*.smi


The result will be displayed in the terminal as Molecule to be active or Inactive

 
