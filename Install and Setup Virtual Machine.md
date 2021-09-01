# Install and Configure VirtualBox Software on a Windows System

## Installation of VirtualBox

Step 1. Double click the installation file - `VirtualBox-version-number-Win.exe`  (Note: In the file name, `.exe` is called file extension. It tells user what type of file it is. `exe` means it is an executable file. You maybe thinking, all files I have been clicking "executes" a program? But that is not true. When you click a file, the operating system automatically launches the default program, usually an executable file, that can open the type of file. ) You will be greeted by the following screen. Click next. 

![image-20210831210033262](images/image-20210831210033262-16304616366521.png)

Step 2. The configuration process started. Please leave everything as/is in the following screen. 

![image-20210831210128625](images/image-20210831210128625-16304616908242.png)

Step 3. You may freely choose whether to select the second and the third options, but better leave the first and the last options selected. 

![image-20210831210201390](images/image-20210831210201390-16304617234733.png)

Step 4. Click Yes. There is nothing you and I can do here. Then, click through the rest of the processes, until you encounter a prompt. 

![image-20210831210300062](images/image-20210831210300062-16304617816654.png)

Step 5. Click `Install` to proceed. This will be the only prompt you will be encountering during the installation. 

![image-20210831210721220](images/image-20210831210721220-16304620430345.png)

Step 6. After the installation, if you open the program by clicking the icon, the following screen will show up. If you see this, congratulations!

<img src="images/image-20210831211027350.png" alt="image-20210831211027350" style="zoom: 67%;" />

## Create Your First Virtual Machine 

Step 1. Click `New`  to create your first ever virtual machine using VirtualBox software. 

![image-20210831224353636](images/image-20210831224353636-16304678361056.png)

Step 2. Your virtual machine will be saved as a file. Give it a proper name, specify the storage location. For the `Type` option, select `Linux`, and for the version, select `Debian (64-bit)` . Please double check the last two options. 

![image-20210831224720731](images/image-20210831224720731-16304680423178.png)

Step 3. You can specify the memory size of the virtual machine. You can choose whatever amount you like. But it needs to be bigger than `3072 MB` and within the green bar. Why bigger than `3072 MB`? That is the minimum memory requirement according to the [PureOS website.](https://tracker.pureos.net/w/pureos/hardware_requirements/) Why stay within the green range? Because you are creating a virtual computer within your actual computer. Therefore, you should never expect that the (virtual) computer within your (actual) computer can have a better performance. If you are on a WSU-lease laptop, `4096 MB` can be a good choice. 

![image-20210831225822858](images/image-20210831225822858-163046870528010.png)

Step 4. This virtual computer also needs a virtual hard disk storage space. Select the second option. 

![image-20210831230036368](images/image-20210831230036368-163046883827511.png)

Step 5. Let's stay with the suggestion for this one. Your virtual hard disk file will have an extension with `.vdi` 

![image-20210831230145623](images/image-20210831230145623-163046890765112.png)

Step 6. This is about the resulting file size of the `.vdi` file. The first option will be dynamically adjust the size of the file, while the second option will try to create a big file from the beginning. 

![image-20210831230255403](images/image-20210831230255403-163046897752214.png)

Step 7. I am using the following setting. The hardware requirement says the space needs to be at least `15 GB`. But since we are only going to use it briefly, if your computer is running out of space, please use as little as `8GB` . Then click `Create`. 

![image-20210831233359615](images/image-20210831233359615-163047084110717.png)

Step 8. You can scroll down the following screen to review the information about the (virtual) computer you have created inside of your (actual) computer. 

![image-20210831233846688](images/image-20210831233846688-163047112852118.png)

Step 9. Let's give the virtual machine a little more display power. Click `Setting`, in the following dialog box, go to `Display` section, increase video memory to `128MB`. Click `OK` to confirm. 

![image-20210831234214281](images/image-20210831234214281-163047133645620.png)

Step 10. Let's turn on the computer by clicking the `Start` icon! It will take some time for the computer to "boot up". Please watch the following video for a brief introduction of the environment. 

https://youtu.be/L_8bhRZjrUs
