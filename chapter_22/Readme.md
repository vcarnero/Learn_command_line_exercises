#Can you set the debug environment variable to true?
I used these commands first to practice

    export TESTING="bada bada bing"
     echo $TESTING
     unset TESTING
     echo $TESTING
     env | grep TESTING
     history | tail 

DEBUG request

    export DEBUG="True"
     echo $DEBUG
     env | grep DEBUG 
     
 
#Can you remove the debug environment variable?

  unset DEBUG
