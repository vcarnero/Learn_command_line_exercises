

#Let's close this terminal and open a new one.
  exit
  
#Can you reload your terminal?
Click on icon, use spotlight.

#Can you logout?
exit

#DO MORE
=========================================
  man xargs

NAME
     xargs -- construct argument list(s) and execute utility

SYNOPSIS
     xargs [-0opt] [-E eofstr] [-I replstr [-R replacements]] [-J replstr] [-L number] [-n number [-x]]
           [-P maxprocs] [-s size] [utility [argument ...]]

DESCRIPTION
     The xargs utility reads space, tab, newline and end-of-file delimited strings from the standard input
     and executes utility with the strings as arguments.

     Any arguments specified on the command line are given to utility upon each invocation, followed by some
     number of the arguments read from the standard input of xargs.  The utility is repeatedly executed until
     standard input is exhausted.

     Spaces, tabs and newlines may be embedded in arguments using single (`` ' '') or double (``"'') quotes
     or backslashes (``\'').  Single quotes escape all non-single quote characters, excluding newlines, up to
     
============================================
  man sudo

NAME
       sudo, sudoedit - execute a command as another user

SYNOPSIS
       sudo -h | -K | -k | -L | -V
       sudo -v [-AknS] [-g group name | #gid] [-p prompt] [-u user name | #uid]
       sudo -l[l] [-AknS] [-g group name | #gid] [-p prompt] [-U user name] [-u user name | #uid] [command]
       sudo [-AbEHnPS] [-C fd] [-g group name | #gid] [-p prompt] [-u user name | #uid] [VAR=value] -i | -s
            [command]
       sudoedit [-AnS] [-C fd] [-g group name | #gid] [-p prompt] [-u user name | #uid] file ...

DESCRIPTION
       sudo allows a permitted user to execute a command as the superuser or another user, as specified by
       the sudoers file.  See the COMMAND EXECUTION section below for more details.

       sudo determines who is an authorized user by consulting the file /private/etc/sudoers.  By running
       sudo with the -v option, a user can update the time stamp without running a command.  If
       authentication is required, sudo will exit if the user's password is not entered within a configurable
       
==============================================
  man chmod
  
NAME
     chmod -- change file modes or Access Control Lists

SYNOPSIS
     chmod [-fv] [-R [-H | -L | -P]] mode file ...
     chmod [-fv] [-R [-H | -L | -P]] [-a | +a | =a] ACE file ...
     chmod [-fhv] [-R [-H | -L | -P]] [-E] file ...
     chmod [-fhv] [-R [-H | -L | -P]] [-C] file ...
     chmod [-fhv] [-R [-H | -L | -P]] [-N] file ...

DESCRIPTION
     The chmod utility modifies the file mode bits of the listed files as specified by the mode operand. It
     may also be used to modify the Access Control Lists (ACLs) associated with the listed files.

     The generic options are as follows:

     -f      Do not display a diagnostic message if chmod could not modify the mode for file.
     
===================================================
  man chown
  
NAME
     chown -- change file owner and group

SYNOPSIS
     chown [-fhv] [-R [-H | -L | -P]] owner[:group] file ...
     chown [-fhv] [-R [-H | -L | -P]] :group file ...

DESCRIPTION
     The chown utility changes the user ID and/or the group ID of the specified files.  Symbolic links named
     by arguments are silently left unchanged unless -h is used.

     The options are as follows:

     -f      Don't report any failure to change file owner or group, nor modify the exit status to reflect
             such failures.

     -H      If the -R option is specified, symbolic links on the command line are followed.  (Symbolic links
