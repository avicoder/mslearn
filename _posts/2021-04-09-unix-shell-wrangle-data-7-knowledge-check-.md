---
    layout: post
    title: Use the UNIX shell to wrangle log data 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/unix-shell-wrangle-data/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/student-evangelism/unix-shell-wrangle-data.svg">
####  1. In our current directory, we want to find the three files with the least number of lines. Which command listed here would work?


<i class='far fa-square'></i> &nbsp;&nbsp;wc -l * > sort -n > head -n 3

<i class='far fa-square'></i> &nbsp;&nbsp;wc -l * | sort -n | head -n 1-3

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;wc -l * | sort -n | head -n 3

<i class='far fa-square'></i> &nbsp;&nbsp;wc -l * | head -n 3 | sort -n
<br />
<br />
<br />

####  2. What will the regular expression Fr[ea]nc[eh] match?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;French, France, Frence, Franch

<i class='far fa-square'></i> &nbsp;&nbsp;Frenche, Franceh, Frenceh, Franche

<i class='far fa-square'></i> &nbsp;&nbsp;France, French

<i class='far fa-square'></i> &nbsp;&nbsp;Freanceh, Fraenche
<br />
<br />
<br />

####  3. The -v option to grep inverts pattern matching so that only lines that don't match the pattern are printed. Which of the following commands will find all files in /data whose names end in s.txt but whose names also don't contain the string net? Examples are shuttles.txt or software.txt but not planets.txt.


<i class='far fa-square'></i> &nbsp;&nbsp;find data -name *s.txt | grep -v net

<i class='far fa-square'></i> &nbsp;&nbsp;grep -v 'net' $(find data -name '*s.txt')

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;find data -name '*s.txt' | grep -v net

<i class='far fa-square'></i> &nbsp;&nbsp;None of the above
<br />
<br />
<br />

####  4. Suppose you want to delete some processed data files and only keep your raw files and processing script to save storage. The raw files end in .dat, and the processed files end in .txt. Which of the following solutions would remove all the processed data files and only the processed data files?


<i class='far fa-square'></i> &nbsp;&nbsp;rm ?.txt

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;rm *.txt

<i class='far fa-square'></i> &nbsp;&nbsp;rm * .txt

<i class='far fa-square'></i> &nbsp;&nbsp;rm .
<br />
<br />
<br />
