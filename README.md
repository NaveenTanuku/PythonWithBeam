# BigDataExamples

## Apache Beam
### Python

Used Annconda to run all below commands 

1. Command used to check the versions. 
     Python --version
     pip --version 
      if pip is not updated to stable release then we can upgrade by below command 
        pip install --upgrade pip
        
 2. Commands used to create a virtual envirnoment 
       python -m venv C:\Users\S542000\Documents\GitHub\PythonWithBeam\     -- path to the current working python directory 
       then route to the directoty by using the follow command 
        cd C:\Users\S542000\Documents\GitHub\PythonWithBeam\PythonWithBeam\Scripts\activate --path contains activate file
  
  3. To install the apache beam
       pip install apache-beam
       after installation, place a py file in the src folder and an input file in the current directory.
       
  4. To run the above py file with test input file, 
        python -m apache_beam.examples.wordcount --input C:\Users\S542000\Documents\GitHub\PythonWithBeam\PythonWithBeam\sample.txt --output C:\Users\S542000\Documents\GitHub\PythonWithBeam\PythonWithBeam\counts
        --input and output files will be modified according to there paths.
