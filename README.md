GETINFO
=======

## Help

getinfo

    Usage: getinfo ...
    
    Load shell scripts to fetch and check variables/configurations in
    shell scripts.
    
    Loading files and fetching variables:
    
      -l FILE... : Load files.
      -L FILE... : Load files (optional).
      -g VARS... : Get variable value.
      -G VARS... : Get variable value trimed and '#' comments removed.
    
    Documenting variables:
    
      -a VAR=HELP...   : Set variable help.
      -s               : Print variable help summary.
      -p all|VARS...   : Print variables and their values.
    
    Checking variables:
    
      -c VAR[=CHECKER] : Check variables (By default whether set).
    
    The following checkers are defined:
    
      s  : Is not empty.             yn : Can be "y" or "n".
      d  : Contains a directory.     f  : Contains a file.
    
    New checkers can be defined by creating functions/scripts with
    the following interface: getinfo_c_NAME VARIABLE VALUE, which
    return 1 and an error message in case of error.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
