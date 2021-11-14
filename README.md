# CMPE 283 Assignment 1

## Contributions

### Both

> We connected over a zoom call to complete the assignment. We created a **Ubuntu** boot on the machine. We downloaded the .c and Makefile from canvas. We divided the work of writing the structs and the method calls. We updated the .c file with our codes. We solved the errors along the way and followed the below mentioned steps to list the capability information.

### Himaja Chandaluri

> Researched and wrote the struct's for **procbased primary pins** and **exitctl** capabilities. Wrote code to print these pin capabilities by calling the rdmsr and report_capabilities methods 

### Sravya Ratna Chandra Lekha Mamidi
> Write the struct's for **pinbased** capabilities and **entryctl** capabilities. Write code to print these pin capabilities by calling report_capability and rdmsr functions 

## Steps followed

1. Download the .c and Makefile from Canvas
2. Add `MODULE_LICENSE("GPL v2");` line to the end of the .c file
3. Add capability structs based on SDM information and call rdmsr and report capabilities
4. Run `make` command in the folder that contains the .c and Makefile
5. Execute command `sudo insmode ./cmpe283-1.ko`
6. Execute `dmesg` to list all available capabilities

## Screenshots

![Screenshot from 2021-11-09 19-48-41](https://user-images.githubusercontent.com/67281829/141700585-02f15d9e-bad9-4749-94e8-e35dc459ed0a.png)
![Screenshot from 2021-11-09 19-48-47](https://user-images.githubusercontent.com/67281829/141700590-19928056-efc0-4e8e-a352-775f6d4c016f.png)
![Screenshot from 2021-11-09 19-48-51](https://user-images.githubusercontent.com/67281829/141700593-d7aaf86b-64ff-468b-80db-065ed5639b07.png)
![Screenshot from 2021-11-09 19-48-55](https://user-images.githubusercontent.com/67281829/141700594-a8c4423b-62ff-47a7-9121-504f40e9fceb.png)
![Screenshot from 2021-11-09 19-48-59](https://user-images.githubusercontent.com/67281829/141700595-2048be38-3fc2-4506-bcca-c932eb3aaca7.png)
![Screenshot from 2021-11-09 19-49-02](https://user-images.githubusercontent.com/67281829/141700599-a531f494-b9d8-4ccd-91bb-5ae6081eace0.png)
![Screenshot from 2021-11-09 19-49-57](https://user-images.githubusercontent.com/67281829/141700604-49f1f72a-c634-44ba-acbd-c49d5fda9d67.png)
