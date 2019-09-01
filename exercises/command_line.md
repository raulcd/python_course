# Command Line Exercicses

## Files

* Check current folder
* List files
* Create a simple file with some random content
* Save the file
* Read the file from command line (use several methods to read the file)
* Make subdirectory called bts and not_fun
* Delete the subdirectory called not_fun
* Move the file to the directory called bts

## File permissions

* Change user to root
* Create a file
* Go back as a normal user
* Try to read the file
* Go back to root
* Try to read the file

## Processes

* Create a file named `infinite_loop.py` with the following content

```python
while True:
    pass
```

* Execute the file with `python infinite_loop.py &`
* Check your cpu usage
* Check your processes
* Stop the process run by python

# Networking

* What is google.es IP?
* Can you check if you have connectivity to google.es using the command line?
* Make a GET request to https://httpbin.org/ip, what is the result?
* Make a GET request to https://httpbin.org/uuid, what is the result?
* What happens when you try to download an image from https://httpbin.org/image  ?
* Try to add a header accepting one of the values that it asks for? Tip: search for --header or -H on curl man page
* Once it warns you about binary output try redirecting the output to a file. `> file.jpg`


## Other commands

```
echo hello world
passwd
date
hostname
uname -a
dmesg | more
uptime
whoami
who
id
w
top
echo $SHELL
echo {con,pre}{sent,fer}{s,ed}
man "automatic door"
man ls
man who
clear
cal 2000
cal 9 1752
echo 5+4 | bc -l
yes please
time sleep 10
history
```
