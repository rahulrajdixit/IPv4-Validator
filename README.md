# IPv4-Checker

## **Please Note**
- This is a simple tool to check if a given IP Address is valid or not, and if it is a valid one, then it just provides some general information about it. Java will be required to run this program on your system.
- The the tool does not have any dependencies for calculations involving the IP Addresses. Only certain libraries are being used for the frontend generation.
- The methods were developed by me just out of curiosity, to understand how an IP Address could be validated. Hence, there is a possibility of finding errors.
- I had made this tool some time back. If anyone wants to improve the code, then please feel free to contribute.

## **Introduction**
This is a simple IPv4 (IP Address) Checker. This small tool can:- 
> 1) Help find out the details regarding the IP Address (Class, Subnet Mask). 
> 2) Analyse the given IP Address and then determine any kinds of errors in the input/format/etc.

This tool was made just for fun and out of curiosity, in my 2nd year (2019) of B.Tech. It was just developed to understand the logic behind the IP address-validity checking in different softwares and applications. There is a possibility that my apporach to validate the IP Address is wrong.

------------------------------

## **How to use it?**
1. Given that Java is installed and working on your system, download the zip file and extract it. The program files should be in `IPv4-Checker-main` folder.
2. Open CMD or Terminal and come to the directory where the program files are present. The directory location would mostly be `C:\Users\username\Downloads\IPv4-Checker-main\IPv4-Checker-main>` .
3. To run the program, we first need our java compiler (javac) to convert our source code (`IPv4GUI.java`) to bytecode (`IPv4GUI.class`). For that, we use the following command:-
```java
javac IPv4GUI.java
```
4. The bytecode is now generated by the java compiler. Now, use the following command to start the tool:-
```java
java IPv4GUI
```
5. You can now see the Graphical-User-Interface of the tool is now available. Try out different values and test if the IP Address is valid or not. Some of the values could be:-
> Valid Values 
> - 192.168.1.4 
> - 10.10.0.1
> - 127.0.0.1

> Invalid Values
> - 1.1.1.999.
> - 673.5.35.abc
> - 2A:5D:3B:5E:7B

## **Outputs**
### **Example 1**
Here, the input is: 192.168.1.4, which is a valid input.

<img width="438" alt="frame1" src="https://user-images.githubusercontent.com/61109976/160288935-ab9660f2-98df-4db2-8676-d68df6f19db5.png">

As the input is valid, the program confirms the same, and identifies the `class` and `Subnet Mask` or the IPv4.

<img width="452" alt="frame2" src="https://user-images.githubusercontent.com/61109976/160288941-1443ac1c-526c-4503-89d0-ebb7a4cd5a40.png">

### **Example 2**
Here, the input is: 1.1.1.999., which is an invalid input.

<img width="439" alt="frame3" src="https://user-images.githubusercontent.com/61109976/160288951-5f413072-328f-473b-b983-0eb37659b42d.png">

For this input, as the IP address is invalid, the tool lists some issues for the input. The back `<= Go Back` button can be used to go back, and try giving any other input or trying to correct the current input.

<img width="454" alt="frame4" src="https://user-images.githubusercontent.com/61109976/160288953-36c71bab-df55-479f-8529-da7a96536f52.png">

