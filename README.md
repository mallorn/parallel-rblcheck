# parallel-rblcheck

This script runs a parallel RBL lookup against a list of RBLs for a given IP.

There are two options that must be set in the script:

  1.  change $ip to your ip address, enclosed in the parantheses (replace the xx.xx.xx.xx)
  2.  change $max_processes to how many parallel lookups you want to run at a time.  If you have problems with the script failing, try a smaller value


There are some RBLs commented out in the rbl-servers.txt list; these are RBLs that I didn't care about or are good RBLs that I didn't want creating output.

A future version will probably expand the file with lists of good vs bad RBLs, what the return values mean, etc.
