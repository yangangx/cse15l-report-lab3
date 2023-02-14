# 1 
Use the command below to look for files and directories starting with the letters qa. 
In our computer, we have the qatree.txt and qa.txt files as well as a directory by the name qa.

```https://geekflare.com/linux-find-commands/```
Example 1:
command:
```
find ./ -name "ch*"
```

output:
```
.//non-fiction/OUP/Berk/ch2.txt
.//non-fiction/OUP/Berk/ch1.txt
.//non-fiction/OUP/Berk/ch7.txt
.//non-fiction/OUP/Abernathy/ch2.txt
.//non-fiction/OUP/Abernathy/ch3.txt
.//non-fiction/OUP/Abernathy/ch1.txt
.//non-fiction/OUP/Abernathy/ch7.txt
.//non-fiction/OUP/Abernathy/ch6.txt
.//non-fiction/OUP/Abernathy/ch8.txt
.//non-fiction/OUP/Abernathy/ch9.txt
.//non-fiction/OUP/Abernathy/ch15.txt
.//non-fiction/OUP/Abernathy/ch14.txt
.//non-fiction/OUP/Rybczynski/ch2.txt
.//non-fiction/OUP/Rybczynski/ch3.txt
.//non-fiction/OUP/Rybczynski/ch1.txt
.//non-fiction/OUP/Kauffman/ch3.txt
.//non-fiction/OUP/Kauffman/ch1.txt
.//non-fiction/OUP/Kauffman/ch4.txt
.//non-fiction/OUP/Kauffman/ch5.txt
.//non-fiction/OUP/Kauffman/ch7.txt
.//non-fiction/OUP/Kauffman/ch6.txt
.//non-fiction/OUP/Kauffman/ch8.txt
.//non-fiction/OUP/Kauffman/ch9.txt
.//non-fiction/OUP/Kauffman/ch10.txt
.//non-fiction/OUP/Fletcher/ch2.txt
.//non-fiction/OUP/Fletcher/ch1.txt
.//non-fiction/OUP/Fletcher/ch5.txt
.//non-fiction/OUP/Fletcher/ch6.txt
.//non-fiction/OUP/Fletcher/ch9.txt
.//non-fiction/OUP/Fletcher/ch10.txt
.//non-fiction/OUP/Castro/chR.txt
.//non-fiction/OUP/Castro/chP.txt
.//non-fiction/OUP/Castro/chQ.txt
.//non-fiction/OUP/Castro/chB.txt
.//non-fiction/OUP/Castro/chC.txt
.//non-fiction/OUP/Castro/chA.txt
.//non-fiction/OUP/Castro/chV.txt
.//non-fiction/OUP/Castro/chW.txt
.//non-fiction/OUP/Castro/chM.txt
.//non-fiction/OUP/Castro/chZ.txt
.//non-fiction/OUP/Castro/chL.txt
.//non-fiction/OUP/Castro/chN.txt
.//non-fiction/OUP/Castro/chY.txt
.//non-fiction/OUP/Castro/chO.txt
```

Exmaple 2:

commnd:
```
find ./ -name "A*"
```
output:
```
.//non-fiction/OUP/Abernathy
.//travel_guides/berlitz2/Amsterdam-WhereToGo.txt
.//travel_guides/berlitz2/Amsterdam-WhatToDo.txt
.//travel_guides/berlitz2/Athens-History.txt
.//travel_guides/berlitz2/Athens-WhereToGo.txt
.//travel_guides/berlitz2/Algarve-Intro.txt
.//travel_guides/berlitz2/Amsterdam-History.txt
.//travel_guides/berlitz2/Algarve-WhatToDo.txt
.//travel_guides/berlitz2/Amsterdam-Intro.txt
.//travel_guides/berlitz2/Algarve-WhereToGo.txt
.//travel_guides/berlitz2/Athens-Intro.txt
.//travel_guides/berlitz2/Algarve-History.txt
.//travel_guides/berlitz2/Athens-WhatToDo.txt
```

# 2

```https://linuxconfig.org/how-to-use-find-command-to-search-for-files-based-on-file-size```

The above find command was used to search for all files greater than specified size. 
Next, find command example will search for all files with less than 10 Kilobytes in size. Note the use of- sign:

Exmaple 1:
command:
```
find . -size -10k
```
output:
```
.
./non-fiction
./non-fiction/OUP
./non-fiction/OUP/Berk
./non-fiction/OUP/Abernathy
./non-fiction/OUP/Rybczynski
./non-fiction/OUP/Kauffman
./non-fiction/OUP/Fletcher
./non-fiction/OUP/Castro
./non-fiction/OUP/Castro/chQ.txt
./non-fiction/OUP/Castro/chW.txt
./non-fiction/OUP/Castro/chZ.txt
./non-fiction/OUP/Castro/chN.txt
./non-fiction/OUP/Castro/chY.txt
./non-fiction/OUP/Castro/chO.txt
./travel_guides
./travel_guides/berlitz1
./travel_guides/berlitz1/HandRLasVegas.txt
./travel_guides/berlitz1/IntroMalaysia.txt
./travel_guides/berlitz1/HandRIstanbul.txt
./travel_guides/berlitz1/HandRHongKong.txt
./travel_guides/berlitz1/IntroEdinburgh.txt
./travel_guides/berlitz1/IntroDublin.txt
./travel_guides/berlitz1/IntroMadeira.txt
./travel_guides/berlitz1/IntroIbiza.txt
./travel_guides/berlitz1/IntroIsrael.txt
./travel_guides/berlitz1/WhatToHawaii.txt
./travel_guides/berlitz1/HandRLisbon.txt
./travel_guides/berlitz1/IntroLosAngeles.txt
./travel_guides/berlitz1/HandRMallorca.txt
./travel_guides/berlitz1/JungleMalaysia.txt
./travel_guides/berlitz1/WhatToFrance.txt
./travel_guides/berlitz1/HandRLosAngeles.txt
./travel_guides/berlitz1/IntroJerusalem.txt
./travel_guides/berlitz1/HandRMadeira.txt
./travel_guides/berlitz1/HandRIbiza.txt
./travel_guides/berlitz1/IntroIstanbul.txt
./travel_guides/berlitz1/IntroHongKong.txt
./travel_guides/berlitz1/IntroFWI.txt
./travel_guides/berlitz1/IntroGreek.txt
./travel_guides/berlitz1/HandRLakeDistrict.txt
./travel_guides/berlitz1/WhereToHawaii.txt
./travel_guides/berlitz1/HandRJerusalem.txt
./travel_guides/berlitz1/IntroEgypt.txt
./travel_guides/berlitz1/IntroMallorca.txt
./travel_guides/berlitz2
./travel_guides/berlitz2/Algarve-Intro.txt
./travel_guides/berlitz2/Bahamas-Intro.txt
./travel_guides/berlitz2/Amsterdam-Intro.txt
./travel_guides/berlitz2/Athens-Intro.txt
```

Example 2:
command
```
find . -size -1k 
```
output:
```
./non-fiction
./non-fiction/OUP
./non-fiction/OUP/Berk
./non-fiction/OUP/Abernathy
./non-fiction/OUP/Rybczynski
./non-fiction/OUP/Kauffman
./non-fiction/OUP/Fletcher
./non-fiction/OUP/Castro
./travel_guides
./travel_guides/berlitz1/HandRIstanbul.txt
./travel_guides/berlitz1/HandRIbiza.txt
```
# 3

A shortcoming of the ls command is that you can't filter its results by file type, 
so it can be noisy if you only want a listing of directories in a path. 
The find command combined with the -type d option is a better choice:

```
https://www.redhat.com/sysadmin/linux-find-command
```
Example 1:
command:
```
find ./non-fiction -type d
```
output:
```
./non-fiction
./non-fiction/OUP
./non-fiction/OUP/Berk
./non-fiction/OUP/Abernathy
./non-fiction/OUP/Rybczynski
./non-fiction/OUP/Kauffman
./non-fiction/OUP/Fletcher
./non-fiction/OUP/Castro
```

Example 2:
command:
```
find ./travel_guides -type d
```
output:
```
./travel_guides
./travel_guides/berlitz1
./travel_guides/berlitz2
```

# 4 
https://geekflare.com/how-to-use-find-command-in-linux/

his search with -name test is case-sensitive and would ignore file A.txt. 
To ensure that your search is case-insensitive use -iname test:
Example 1:

```
find . -iname "ch4.txt"
```
output:
```
./non-fiction/OUP/Berk/CH4.txt
./non-fiction/OUP/Kauffman/ch4.txt
```
Example 2:
```
find . -iname "chy.txt"
```
output:
```
./non-fiction/OUP/Castro/chY.txt
```





