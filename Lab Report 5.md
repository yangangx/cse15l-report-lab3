<<<<<<< HEAD
My favorite lab report is lab report 3. I did the exploration of several options for `find` in the lab report 3. I am going to do some exploration for `grep` this time. I feel those commands are useful for me. I did this task by searching how to use `grep` command from online. I also can use ChatGTP to know how to use those commands. I like to search from online, beacuse I can know more about the how to use those commands and more explanation from different website. By looking the different website can make me more understand  about how to use those commands and what those commands do.
=======
My favorite lab report is lab report 3. I did some exploration for `find` in lab report 3. I am going to do some exploration for `grep` this time. I feel those commands are useful for me. I did this task by searching how to use `grep` command online. I also can use ChatGPT to know how to use those commands. I like to search online because I can learn more about how to use those commands and get more explanations from different websites. Looking at the different websites helps me understand how to use those commands and what those commands do. First, I have to find some files. Then, I looked at the content of the file to choose some strings that I wanted to use for those commands. I choose some strings that are not too many or too few in the txt file. Because if the string is too many or too few in the file, the output will be too many or too few. The string `company` is not too many or too few in `ch1.txt`, and the string `store` is not too many or few in `ch2.txt`, so I use `company` for `ch1.txt` file and `store` for `ch2.txt`. For the command, Print lines beginning with a certain character, I use the character `I`. The number of lines beginning with the character `I` is not too many or few, so I use the character `I`.
>>>>>>> 01399eb14f47a6d577fc3885c2c09f02ac485f42

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

The command will show all lines where the search string are matched with the numebr infront of each line.

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

## Print lines beginning with certain character.

The command will print all lines begining with certain character.

Source: [Link](https://www.digitalocean.com/community/tutorials/grep-command-in-linux-unix)

Example 1 :

Command:

```grep ^I ch1.txt```

Output: 

![Image](4-1.png)

Example 2 :

Command:

```grep ^I ch2.txt```

Output:

![Image](4-2.png)
