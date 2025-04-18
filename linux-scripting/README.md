# ⚙️ Linux Administration Task: Improve Command-line Productivity

## Task List

- Create the `/home/student/bin/bash-lab` script file on the `controller` machine.  
  - The initial content should be the **shebang** interpreter directive.  

- Edit the newly created script file to include the following commands and outputs:

| Command                                     | Output Required                           |
|---------------------------------------------|--------------------------------------------|
| `echo "This is my first bash script"`       | Get all the output                         |
| `echo "#####################"`              | Get all the output                         |
| `echo "LIST BLOCK DEVICES"`                 | Get all the output                         |
| `lsblk`                                     | Get all the output                         |
| `echo "#####################"`              | Get all the output                         |
| `echo "FILESYSTEM FREE SPACE STATUS"`       | Get all the output                         |
| `df -h`                                     | Get all the output                         |
| `echo "#####################"`              | Get all the output                         |
| `lscpu`                                     | Get only the lines that start with "CPU"   |

- Save the required output into a file named `output.txt` inside the `/home/student` directory on the `controller` machine.  

- Execute the `/home/student/bin/bash-lab` script and review the output content on the `controller`.  

- Find all occurrences of the string `"ing"` in the `/usr/share/dic/words` file and copy the results into `/root/data`.  
