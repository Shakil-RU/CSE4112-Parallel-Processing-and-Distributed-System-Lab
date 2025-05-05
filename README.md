## CSE4112-Parallel-Processing-and-Distributed-System-Lab
    Name: Shakil Hossan
    28th batch
    Department of Computer Science and Engineering
    University of Rajshahi
Email:shakilhossan113@gmail.com

[Dataset Link for Phone Book search](https://drive.google.com/drive/folders/1eFZ3r-XVNTwzjhnTmLgOx2eHN7_1YpPX)
### Run Command on Ubuntu
- **To run a C Program, go to `Ubuntu` & then run the following commands**
<pre>
<b>mpicc name.c -o name</b>
<b>mpirun -n number_of_processors ./name</b>  
</pre>
- **To run a C++ Program, go to `Ubuntu` & then run the following commands**
<pre>
<b>mpic++ name.cpp -o name</b>
<b>mpirun -n number_of_processors ./name</b>  
</pre>


## Installation of MPI in Visual Studio Code
- **To install MPI, see this [video](https://www.youtube.com/watch?v=bkfCrj-rBjU) & follow every step carefully. If you face the issue "sal.h dependency not found" or something like that, uninstall the MinGW compiler & follow this [video](https://www.youtube.com/watch?v=_-O94qsnOLk)**


### Run Command on Visual Studio Code
- **To run a C Program, go to `Terminal` > `Run Build Task...` in the VS Code & then run the following command**
<pre>
<b>mpiexec -n number_of_processors file_name_without_extension</b>
</pre>
