# comp201-lab-1-basic-commands-of-linux-solved
**TO GET THIS SOLUTION VISIT:** [COMP201 Lab 1-Basic commands of Linux Solved](https://www.ankitcodinghub.com/product/comp201-the-main-aim-of-this-assignment-is-to-give-you-some-insight-into-using-basic-commands-of-linux-it-is-required-to-perform-this-exercise-and-submit-your-work-to-blackboard-you-are-required-t/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117680&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP201 Lab 1-Basic commands of Linux Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
The main aim of this assignment is to give you some insight into using basic commands of Linux. It is required to perform this exercise and submit your work to Blackboard. You are required to perform all operations using the Linux shell(using the linuxPool).

1. Download the exercise contents from the blackboard and unzip the compressed file.

• Then you need to copy the contents to the linuxPool machines by using scp command on your local machine. Destination path ”USERNAME@linuxpool.ku.edu.tr:” must not contain any spaces.

scp −r FOLDER NAME USERNAME@linuxpool . ku . edu . t r :

1

• To download a folder from the linuxPool machines to your local machine, you can use scp again by changing the source and target address (you need to run this on your local machine).Once again source and destination paths must not contain any spaces. After ”:” sign, you need to specify the path in linuxpool server starting from the home directory. Then you can state the destination directory in your local machine. For instance ”./” will download the files to current working directory.

scp −r USERNAME@linuxpool . ku . edu . t r : /PATH/TO/LINUXPOOL/FOLDER PATH/TO/

LOCAL/FOLDER

1

2. mv is a Unix command that moves one or more files or directories from one place to another. The most common format of using this command is:

mv [ Option ] SOURCE DESTINATION

1

With the help of mv command rename the assignment folder that downloaded from blackboard and uploaded to the linuxpool to Lab1Assignment.

3. Try to list all files that has ”q” in their name in the Lab1Assignment directory. This list needs to be in human-readable format. This list has to be sorted according to files sizes.Then append this list to q3.txt. Write down commands that you used to create this list and append it to q3.txt.

4. One of the parameter of the ls command is -l which shows all permission of the files in current directory. Use this parameter to see permission of permission.txt file.

5. By using chmod command modify the permissions so that file owner would have read, write and execute permissions; group owner would have read and write permissions; other users would not have any of the permissions. After these modifications append detail information of this file including its

1

Figure 1: linuxpool file hierarchy for part 7

permission information to q5.txt. Append the command or commands that you used to change permission to q5.txt.

6. There are quite a few editor available for linux bash. Use ’vi’ or ’vim’ editor to open q6.txt and write down answers of the questions there.

7. Make a directory named SortedCountries under Lab1Assignment directory. Then under SortedCountries folder make two other directories named as RList and ZList. Write all of these commands to the file q9.txt.

8. There is a text file named countries.txt includes names of all the countries in separate lines. Use a command to find number of countries in this file. Then use terminal commands to get a list of countries inside countries.txt file which starts with the uppercase character ’R’ by piping. Store this list in a text file under /Lab1Assignment/SortedCountries/RList directory. Do the same procedure for country names which starts with the uppercase character ’Z’ and store the list in a text file under /Lab1Assignment/ SortedCountries/ZList directoty. Write all of these commands to the file q9.txt.

9. Concatenate the contents of two files created in part 8 and append them to q9.txt file.

10. After completing previous parts, you should compress your Lab1Assignment folder into zip or tar.gz files, and submit it to the Blackboard.

2
