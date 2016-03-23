#What option to ls tells it to output file size in human readable form?

ls -lh

LS(1)                     BSD General Commands Manual                    LS(1)

NAME
     ls -- list directory contents

SYNOPSIS
     ls [-ABCFGHLOPRSTUW@abcdefghiklmnopqrstuwx1] [file ...]

DESCRIPTION
     For each operand that names a file of a type other than directory, ls
     displays its name as well as any requested, associated information.  For
     each operand that names a file of type directory, ls displays the names
     of files contained within that directory, as well as any requested, asso-
     ciated information.

     If no operands are given, the contents of the current directory are dis-
     played.  If more than one operand is given, non-directory operands are
     displayed first; directory and non-directory operands are sorted sepa-
     rately and in lexicographical order.

     The following options are available:

     -@      Display extended attribute keys and sizes in long (-l) output.
     
#Is there a case insensitive option to grep?
  grep -i
#What does the -r and -f options to rm do exactly?
  -r  remove
  -f  force
#What does the ifconfig command do?
  man ifconfig
 The ifconfig utility is used to assign an address to a network interface and/or configure network inter-
     face parameters.
