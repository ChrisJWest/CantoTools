
# CantoRead #

Welcome! CantoRead is a straightforward Windows Form application for reading written Cantonese. I am not a software engineer and only did this over a very short time period during a break from school. Therefore, there are some bugs, but you should be able to work around them.



To run the application, download the Executable Folder and run CantoRead.exe. It should show you a screen like this (but no text):

<img width="958" alt="CantoRead" src="https://github.com/ChrisJWest/CantoTools/assets/40185957/0e9f0e99-d75a-4250-a896-9405bd2af53a">

To load in a book, select from the drop down next to load book, and then click load book. To load in books (or other text files), you will need to make changes to your local bookmark file. It should look something like this:

MenCantBePoor1 C:\Users\porti\source\repos\CantoText\CantoText\TestBook.txt 0
Rhapsody1 C:\Users\porti\source\repos\CantoText\CantoText\TestBook2.txt 1
Rhapsody2 C:\Users\porti\source\repos\CantoText\CantoText\TestBook3.txt 0

Replace the filepath with the link to your text file, and the number with the page you would like to start from. By default it should be 0. No books have been included by default with the application, so you will have to add them yourself before loading.

When reading, in order to save a bookmark, click "Save". This will overwrite the bookmark file so that the next time you load it will load from that page.




In order to use the known word functionality, you need to use "HK_WordList.csv" and "HK_WordListBackup.csv". These contain, in csv form, parsed Cantonese words and your learning status (1 is learning, 2 is known). By default, if words are not found here then they are assumed to be unknown. I've included my wordlist as a start, but you should start with whatever you know, even if it's just the basics. The reader application will update your known and learning words, keeping a backup as well. Learning and unknown words are represented by different colors in the application (blue is learning, purple is unknown). To set words to different statuses, highlight the word in the application and then type either 0 (unknown), 1 (learning) or 2 (known).



There is also a word-saving feature. If you highlight a word and would like to save it for later, click "Save Word". Then, at the end of your session, click "Export" and it will overwrite the "TodayWordList.txt" file with your saved words and definitions, which you can then use in any flashcard app or notes, etc.

For instance:

政治 - zing3 zi6 - politics is the process of making decisions applying to all members of each group.
開拓 - hoi1 tok3 - to open up; to develop; expand to new areas, for businesses usually


Again, the application is not perfect and you will have to play around with it to make it work for you, but it gets the job done in general. Hope you find it useful!



