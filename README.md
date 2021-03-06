# Python Programming Lessons

This repository is intended to be used _by_ and _for_ beginner developers that participate to the lessons.  
It make possible to the teacher and to the students to have a common shared code and references.  

## Topics

- Explain what is Python, how it works, basic concepts
- Write and run your first Python program: "Hello World"
- Kata [Multiply](http://www.codewars.com/kata/multiply)
- Kata ["Best travel"](https://www.codewars.com/kata/best-travel/python)
- Kata ["Can you get the loop ?"](http://www.codewars.com/kata/can-you-get-the-loop)
- Take [this blog post](https://blog.teowaki.com/2016/07/21/fun-with-theresa-mays-first-speech-as-mp-and-the-google-cloud-speech-and-natural-language-apis/) as an idea, it is about Google Speech API.
- How find and use the [DOCS](http://docs.python.org) (Python documentation). (example: str() can raise a TypeError?)
- How to write good code, clean and covered by tests


## Ideas for lessons

- Address book
- Calculator
- Web Scraping


## Tools - Software (all free)

+ [Python 3](https://www.python.org/downloads/) installed on your PC
+ [Visual Studio Code](https://code.visualstudio.com/): a simple (but very flexible) general purpose editor 
+ [SourceTree](https://www.sourcetreeapp.com/): a visual tool to manage Git repositories (it requires an Atlassian account)

## Web sites

+ [GitHub](https://github.com/)
+ [PyCharm](https://www.jetbrains.com/pycharm/): a great IDE with many features for writing Python code (the community edition is free)
+ [CodeWars](https://www.codewars.com/) (you can use your GitHub account) many well organized exercises (kata)
+ [CodinGame](https://www.codingame.com) (you can use your LinkedIn or Google account) as in CodeWars you can see solution of others users
+ [PyBite challenges](https://codechalleng.es/)


### FAQ

**Q. SourceTree returns an error when I try to commit/push my local changes.**  
**A.**  
   Usually it happens because on the remote repository there are changes one one or more files that you have changed also locally.
   Because two different version cannot exists a "merge" of the changes should be done.  
   This operation is called "Resolve Conflicts" and permits to select line by line (where the 2 files are different) if take the line of code from the file A or from the file B, or both.  
   Another way to avoid conflict is to "revert" (or "discard" or "undo") all or part of the changes done. Sometime we have changes that we haven't done intentionally or that we want to cancel.  
   It is possible to mix both the 2 ways to solve the conflicts: merge some files (resolve the conflicts choosing which line will be selected for the final version) and delete some changes.  
 
**Q. How to run the code**  
**A.**  
main.py: this is our "program"  
test.py: this is the test that prove that the program works (or fail)  
Both "main.py" and "test.py" can be run.
If you run "main.py" it just execute the main() program that shows "Python lesson".
If you run test.py it execute a predefined list of tests against the implemented function and shows the results.

### Visual Studio Code

(super simple) 
1. from the menu use the _open folder_ command and select he path of your local project (the directory that contains _main.py_).
2. open _main.py_ or _test.py_
3. Press _F5_ (it is usually the shortcut for _run debug_)

### PyCharm

(not immediate to set)  
To "run" something you need to configure it in the "Configurations".
Both "main.py" and "test.py" can be run.
If you run "main.py" it just execute the main() program showing the welcome text and "Press any key to close".
If you run the test.py it executes all the test cases and return the result in the output console.

**In order to run the program** (main.py or test.py) you have to create a **configuration** for "Python" and select "test.py" to run the test.py 

      
   
## Links
 
 - [Try Git in 15 minutes interactive tutorial](https://try.github.io) 
 - [CodeWars simple Python Kata](http://www.codewars.com/kata/search/python?q=&r%5B%5D=-8&beta=false&order_by=popularity+desc)
