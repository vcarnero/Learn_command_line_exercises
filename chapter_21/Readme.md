
#What is your shell set to?
When I first put 'env' a lot of output. After scrolling through everything I found
  SHELL=/bin/bash
  
#What directory are you in (don't use pwd this time)?
'env' produces a lot of output, contained within it is:
  PWD=/Users/veronica/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_21
  
#What is your home directory set to?
  HOME=/Users/veronica

#Can you set your environment to have DEBUG set to true?
  export DEBUG="True"
       echo $DEBUG
       env | grep DEBUG 
  
