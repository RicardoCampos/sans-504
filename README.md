# GCIH Certification / Sans-504 Exam prep


- Create your index as you review the course content. I simply used a Google Sheets document. I started with a noun, then the adjective. e.g. "Passwords, empty (Windows)". Quite often I had a Windows and Linux entry. I had the book then the page next to them e.g. `3-24` was book 3, page 24.
- Find a "cheat sheet" on the Internet for pretty much every tool you used on SANS-504 and print it out. There's plenty of SANS ones,; I would also print the generic ones for TCP/IP/TcpDump, common CLI commands (Windows/Linux) etc
- For Hashcat, ensure you highlight the most common `-m` values (e.g. UNIX/Windows ones) as there's LOADS and they're hard to parse on a cluttered cheatsheet.
- If there isn't a cheat sheet for a command, print out the man page.
- Print out the Windows event numbers. The questions generally tell you  what you're looking for, but you never know.
- Do the Linux Olympics. It will help you immensely in the exam, just simple stuff like `grep` 'ing through log files will cut the time required to answer a question 10x.
- Do the labs again. Don't forget you can bring the workbook into the exam also. Look for commands that are there but not in the course books - add those to your list of cheat sheets to print
- Make sure you do some offensive stuff, Beef as well as Command/SQL injection etc. It was a relatively small book in the course and easy to overlook.
- There's a lot of assumed Windows knowledge, which was lightly covered in the course (there were no Windows Olympics) as I suspect most security professionals come have it (for obvious reasons). I was weak on: Looking for persistence in event viewer (and recognising SID's/ Users and how to tell if they are an admin or not), the many uses of `net` in Windows.
- Look at Alternate Data streams. These weren't covered in my course at all but DID feature in the exam (potentially as a red herring, I don't know)

# Practice tests

- Go through the entire course making your index, and then do the first practice test ASAP after. Note down things you didn't print out, areas you were clueless, etc.
 - A week before the actual exam, do the second practice exam, and find any weak spots in your knowledge.
 - The practice exams are VERY similar to the real one. In fact I suspect some of the questions are the same or so close it's hard to tell (just different IP addresses, usernames etc)


# Sitting the exam

- Skip a question that you don't know the answer to, don't try to guess it. Something might jog your memory in a later question, so you can come back.
- Don't rush, you have plenty of time.
- The live section is VERY similar to the labs on the course (hence why you should repeat them). 
- Since it's multiple choice, if the answer isn't immediately obvious then start by removing the choices that are definitely wrong.

