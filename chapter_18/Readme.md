#DO MORE
  grep "new file" *.txt
finds the lines with new and file.
  grep "old file" *.txt 
does a similar thing.
  grep "This is" *.txt
again, similar. Important that "" make it case sensitive so it will find EXACTLY what is inside of double quotes, this is inclusive order.

#Show me the lines in foo.txt that have "ERROR" in them.
  grep ERROR foo.txt
#Show me the lines in bar.txt that have "davinci" in them.
  grep davinci bar.txt

#Can you print all the lines in text files that have your first and last name in them?

  grep 'veronica carnero' *.txt


#Add a comment to the Readme.md that explains what the -i option to grep accomplishes.
(-i) ignores case with grep.
