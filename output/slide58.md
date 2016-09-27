#### Option 2: Docker inside a VM

For a long time, you could only run Docker natively on a Linux OS.  To run Docker on Mac or Windows you needed to run a Linux based VM, and then run Docker inside the VM.  Technologies like Docker Toolbox, Docker Machine, and boot2docker all worked to make this easier.  Vagrant can use this model to also support Docker development by first creating a host VM, installing Docker into the VM, and then deploying containers on the VM.  

