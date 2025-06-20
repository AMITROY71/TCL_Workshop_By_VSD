# TCL_Workshop_By_VSD
# TCL WORKSHOP: FROM INTRODUCTION TO ADVANCED SCRIPTING BY VSD

# Workshop Content

Day 1: Introduction to TCL and VSDSYNTH Toolbox Usage

Day 2: Variable Creation and Processing Constraints from CSV

Day 3: Processing Clock and Input Constraints

Day 4: Complete Scripting and Yosys Synthesis Introduction

Day 5: Advanced Scripting Techniques and Quality of Results Generation

# Tools Used:
Yosys,
OpenTimer,
TCL development suite,
Libraries (associated with TCL)

# Day 1: Introduction to TCL & VSDSYNTH Toolbox usage
## case 1: User not provide .csv file as input argument
<img width="553" alt="image" src="https://github.com/user-attachments/assets/55e5d82a-bc05-418b-a534-8ac817b78fa1" />
<img width="256" alt="image" src="https://github.com/user-attachments/assets/3aed8114-e3c7-4673-a989-eca76a50c560" />

## case 2: Provide .csv file as argument, which doesn't exist
<img width="302" alt="image" src="https://github.com/user-attachments/assets/ae861f27-7758-4722-9eee-b407d943a470" />
<img width="317" alt="image" src="https://github.com/user-attachments/assets/fdf31ab0-43e2-4205-82ce-f4467febc028" />

## case 3: Type "-help" to find out usage
<img width="920" alt="image" src="https://github.com/user-attachments/assets/97a20010-7131-48ce-a380-adc7d7cfe912" />

# Day 2: Variable Creation and Processing Constraints from CSV

Agenda will be converting all inputs into the required format i.e. format[1] & SDC format & passing it to the tool YOSYS.

Tasks involved

1. Create variables

2. To check if directories & files are mentioned in the .csv exist or not

3. Read constraint file for the above .csv & convert it to sdc format

4. Read all files in netlist directory

5. Create the main synthesis script in format [2]

6. Pass this script to Yosys

The below snapshot shows step 1 i.e. creating the variables
<img width="875" alt="image" src="https://github.com/user-attachments/assets/3eea99f3-9c9e-44b2-8bc0-dae7e077dfda" />

