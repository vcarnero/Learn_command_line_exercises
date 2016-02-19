chapter 9 touch

#Unix: Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

I received the error because I had an open file in my directory, so I could not delete that directory.

# English questions: Can you touch blah.txt, Let's create foo.txt
 touch
 
 >veronica(master) Veronica Carnero
  Charlies-MacBook-Pro:chapter_9 $touch blah.txt
  
  veronica(master) Veronica Carnero
  Charlies-MacBook-Pro:chapter_9 $ls
  Readme.md    blah.txt     ch9testtouch iamcool.txt
  
  veronica(master) Veronica Carnero
  Charlies-MacBook-Pro:chapter_9 $cat ch9testtouch/
  cat: ch9testtouch/: Is a directory
  
  veronica(master) Veronica Carnero
  Charlies-MacBook-Pro:chapter_9 $create foo.txt
  bash: create: command not found
  
  veronica(master) Veronica Carnero
  Charlies-MacBook-Pro:chapter_9 $touch foo.txt
  
  veronica(master) Veronica Carnero
  Charlies-MacBook-Pro:chapter_9 $ls
  Readme.md    blah.txt     ch9testtouch foo.txt      iamcool.txt

# Explain what happens if you touch an existing file
 when you touch an existing file it updates the access date / modification date of a file.
