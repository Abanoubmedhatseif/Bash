#Lab 1

## Using sed utility
## 1- Display the lines that contain the word “lp” in /etc/passwd file.
## 2- Display /etc/passwd file except the third line.
![q1,2](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/66ce128e-9306-4105-9267-28019172637f)
## 3- Display /etc/passwd file except the last line.
![q3](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/7ee02fdd-3636-4de4-8291-ce5f7c97d788)

## 4- Display /etc/passwd file except the lines that contain the word “lp”.
![q4](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/d8d678e7-e71a-4e32-85e2-0f65be815cf3)

## 5- Substitute all the words that contain “lp” with “mylp” in /etc/passwd file.
![q5](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/de566322-2155-4320-b465-7ad5e6d7c00f)


## Using awk utility

## 1- Print full name (comment) of all users in the system.
![q1](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/a9d70495-862d-4d91-b64d-633735942f81)

## 2- Print login, full name (comment), and home directory of all users. (Print each line preceded by a line number)
![q2](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/95aea90c-a821-409b-984e-a407fc339589)


## 3- Print login, uid and full name (comment) of those uid is greater than 500
![q3](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/17a8bc12-e688-499f-a864-07daa2682ed5)


## 4- Print login, uid and full name (comment) of those uid is exactly 500
## 5- Print line from 5 to 15 from /etc/passwd
![q4,5](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/d6face99-4a78-412b-b5ad-401d672ca8f3)



## 6- Change lp to mylp
##  awk '{gsub(/lp/, "mylp"); print}' /etc/passwd

## 7- Print all information about greatest uid.
## 8- Get the sum of all accounts id’s.

![q7,8](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/db47a4d5-a85b-4e8e-9d79-4eb726c618c5)


 
 #Create a script that asks for user name then send a greeting to him.
![Screenshot from 2023-11-29 14-03-11](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/24d39f98-a4e6-4a40-8a93-25e5f6890111)

 ##Create a script called s1 that calls another script s2 where:
 ##In s1 there is a variable called x, it's value 5
 ##Try to print the value of x in s2 by two different ways.
 
![Screenshot from 2023-11-29 14-42-27](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/d787ed5c-e8e3-406c-b20d-e222ebc037b4)

 
 ##Create a script called mycp where:
 ##It copies a file to another
 ##It copies multiple files to a directory.
![Screenshot from 2023-11-29 15-01-46](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/6bc5d7a4-2c8f-44bd-8e54-a596d7fda353)
![Screenshot from 2023-11-29 14-53-08](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/3bcb7e9b-6ae2-493e-8fa8-95b4ca2f93c9)

 
 ##Create a script called mycd where:
 ##It changed directory to the user home directory, if it is called without arguments.
 ##Otherwise, it change directory to the given directory.
 
 ![Screenshot from 2023-11-29 15-18-16](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/bb328ee1-ccf9-4016-9125-fd065a65061e)

 ##Create a script called myls where:
 ##It lists the current directory, if it is called without arguments.
 ##Otherwise, it lists the given directory.

 ![Screenshot from 2023-11-29 15-20-57](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/f5b6f9d6-0b38-45b7-9605-f0709d6fd7b6)



 ##Write a script called mycase, using the case utility to checks the type of character entered by a user:
     ##Upper Case.
     ##Lower Case.
     ##Number.
     ##Nothing.
![q1](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/8b57974c-338b-4143-ba89-5a4a7004dfa9)

     
 # Enhanced the previous script, by checking the type of string entered by a user:
  ##Upper Cases.
  ##Lower Cases.
  ##Numbers.
  ##Mix.
  ##Nothing.
  ![q2](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/96f28066-4250-46a3-8044-e4b38635c203)

 ##Write a script called mychmod using for utility to give execute permission to all files ##and directories in your home directory.

![q3](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/71799981-eca2-41fd-9b76-d11708b5d13a)

 
 ##Write a script called mybackup using for utility to create a backup of only files in your ##home directory.
![q4](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/e3ce779e-5626-4b40-bd8a-02aaa809c363)

 
 ##Write a script called mymail using for utility to send a mail to all users in the system. ##Note: write the mail body in a file called mtemplate. 

![q5](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/213c7525-43ac-4ef3-98e8-1f6d4795a005)

 
 ##Write a script called chkmail to check for new mails every 10 seconds. Note: mails are ##saved in /var/mail/username.
 
![q6](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/526a6958-88fc-4426-bc6d-7394cf2d7f91)


 #What is the output of the following script
##typeset –i n1
##typeset –i n2
##n1=1
##n2=1
##while test $n1 –eq $n2
##do
##	n2=$n2+1
##	print $n1
##if [ $n1 –gt $n2 ]
##then
##	break
##else
##	continue
##fi
##n1=$n1+1
##print $n2
##done

#infinite loop

##Create the following menu:
           ##Press 1 to ls
           ##Press 2 to ls –a
           ##Press 3 to exit  

 ![q8](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/f93c41f6-9243-4e4d-aacc-857b90444e3d)
      
##Using select utility then while utility.
       ##Write a script called myarr that ask a user how many elements he wants to enter in ##an array, fill the array and then print it.

![q9](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/a55dce3e-707f-4505-967c-f1367bddffbd)

      
  ##Write a script called myavg that calculate average of all numbers entered by a user. ##Note: use arrays

![q10](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/69e10104-913b-4df6-b377-29214206919e)
     
##Write a function called mysq that calculate square if its argument.


![q11](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/f8822276-9e64-41f4-92a7-a268dc4bd00a)

