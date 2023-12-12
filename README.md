#Lab 1

# Using sed utility
# 1- Display the lines that contain the word “lp” in /etc/passwd file.
# 2- Display /etc/passwd file except the third line.
![q1,2](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/66ce128e-9306-4105-9267-28019172637f)
# 3- Display /etc/passwd file except the last line.
![q3](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/7ee02fdd-3636-4de4-8291-ce5f7c97d788)

# 4- Display /etc/passwd file except the lines that contain the word “lp”.
![q4](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/d8d678e7-e71a-4e32-85e2-0f65be815cf3)

# 5- Substitute all the words that contain “lp” with “mylp” in /etc/passwd file.
![q5](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/de566322-2155-4320-b465-7ad5e6d7c00f)


# Using awk utility

# 1- Print full name (comment) of all users in the system.
![q1](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/a9d70495-862d-4d91-b64d-633735942f81)

# 2- Print login, full name (comment), and home directory of all users. (Print each line preceded by a line number)
![q2](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/95aea90c-a821-409b-984e-a407fc339589)


# 3- Print login, uid and full name (comment) of those uid is greater than 500
![q3](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/17a8bc12-e688-499f-a864-07daa2682ed5)


# 4- Print login, uid and full name (comment) of those uid is exactly 500
# 5- Print line from 5 to 15 from /etc/passwd
![q4,5](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/d6face99-4a78-412b-b5ad-401d672ca8f3)



# 6- Change lp to mylp
#  awk '{gsub(/lp/, "mylp"); print}' /etc/passwd

# 7- Print all information about greatest uid.
# 8- Get the sum of all accounts id’s.

![q7,8](https://github.com/Abanoubmedhatseif/Bash/assets/146996493/db47a4d5-a85b-4e8e-9d79-4eb726c618c5)

