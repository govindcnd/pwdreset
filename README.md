###############################################################
##The simple script will help generate random password string##
###############################################################
Set up Process
1. Clone / Download the file password_gen
2. Set permission chmod +x to the file password_gen
3. Copy the same to /usr/bin/

############################################################
Usage Notes

1. Share you input string 
2. set the desired length for the password to be generated 

ex: echo "RyZKrQrjWsmzwhvkEa+9sxfGKh/kgUP5AZd+p3/Ne+b+115PaZUL8lQoKBhmy/oX" | password_gen  20


Things 2 Remember:
The desired length should be less than or equal to input string. Else the generated password will be limited to the length of input string. 
Tested Amazon Linux / Centos.
