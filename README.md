# SPPU-Sem-VIII-Practical-LPV
The zip file contains codes for LPV Practical of SEM VIII i.e. combine of HPC and DL. THe zip file doesn't contains the dataset so please do get your dataset from kaggle and change the name of dataset and path in your code accordingly.

# Running HPC code
- For C++ <br>
  * Compiling = g++ -fopenmp file_name.cpp -o file <br>
  * Running (Terminal) = ./file <br>
  * Running (CMD) = file.exe <br>

- For Cuda <br>
  * Compiling = !nvcc -arch=sm_70 File_name.cu -o file
  * Running = !./file
