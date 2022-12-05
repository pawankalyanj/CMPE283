# CMPE283 Assigment - 1
# Question 1: 
I worked alone on this project.

# Question 2: Steps followed:
1. Download and install Virtualbox.
2. Download the VMimage of 64 bit Ubuntu Desktop.
3. Create Ubuntu VM using the Ubuntu image downloaded. Enable Nested Virtualization
4. Run the Ubuntu VM.
5. Compile the Module file 283-1.c and Install the module using insmod
6. Run the command dmesg to view all system logs. Check that the pin based control logs are present.
7. Add The code to read and print the VMX configuration for process-based, secondary process-based, entry and exit MSRs has been added. The revised code can be found in the file CMPE283-1.c.
8. To generate an updated ko file, compile the module using Makefile.
9. Using rmmod cmpe283-1, uninstall the previously installed module.
10. Install the updated module with insmod./cmpe283-1.ko.
11. Print the logs using dmesg
<img width="1458" alt="vmx-capabilities-all (1)" src="https://user-images.githubusercontent.com/98665897/200442649-abb66f32-c2b3-41f5-815a-a1bab340cfb2.png">
