My favorite lab report is lab report 3. I did the exploration of several options for find in the lab report 3. I am going to do some exploration for `grep` this time.

## Count the lines where strings are matched

The command will count the total number of lines where the string patern appears in the file.

Source: [Link](https://www.digitalocean.com/community/tutorials/grep-command-in-linux-unix)


Example1 :

Command: 

```grep -n "company" ch1.txt```

Output:

![Image](1-1.png)

Example2 :

Command: 

```grep -c "stores" ch2.txt```

Output:

![Image](1-2.png)

## To number the lines where the string pattern appears in the file.

Source: [Link](https://www.digitalocean.com/community/tutorials/grep-command-in-linux-unix)

Example1 :

Command:

 ```grep -n "company" ch1.txt```

Output:

![Image](2-1.png)


Example2 :

Command: 

```grep -n "stores" ch2.txt```

Output:

![Image](2-2.png)

## Colorizing Grep results

The command will show the search string in different color from the rest of the text.

Source: [Link](https://www.digitalocean.com/community/tutorials/grep-command-in-linux-unix)


Example1 :

Command:

```grep --color "company" ch1.txt```

Output:

![Image](3-1.png)

Example2 :

Command:

```grep --color "store" ch2.txt```

Output:

![Image](3-2.png)













