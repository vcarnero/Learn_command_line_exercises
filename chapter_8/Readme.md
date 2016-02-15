chapter 8

#Explain what the pushd and popd commands do, in your own words, in the Readme.md

pushd took me to the corresponding directory location.

popd took me to the directory that I was originally in before using the pushd command.

#For the Do More section, explain what directories you visited

#Below is an example of the different directories I jumped to and back from

veronica(master) Veronica Carnero
Charlies-MacBook-Pro:Learn_command_line_exercises $ls
README.md chapter_2 chapter_4 chapter_6 chapter_8
chapter_1 chapter_3 chapter_5 chapter_7

veronica(master) Veronica Carnero
Charlies-MacBook-Pro:Learn_command_line_exercises $pushd chapter_8
~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_8 ~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises

veronica(master) Veronica Carnero
Charlies-MacBook-Pro:chapter_8 $ls
Readme.md temp

veronica(master) Veronica Carnero
Charlies-MacBook-Pro:chapter_8 $popd
~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises

veronica(master) Veronica Carnero
Charlies-MacBook-Pro:Learn_command_line_exercises $pushd chapter_2
~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises/chapter_2 ~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises

veronica(master) Veronica Carnero
Charlies-MacBook-Pro:chapter_2 $popd
~/workspace/davinci_coders_t1_2016/homework/Learn_command_line_exercises
