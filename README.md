
# I created this script for enumerating executables that matches the ones found in the PATH env for further privilege escalation via PATH technique, specifically for tryhackme lab (linux privilege escalation). <br>

just run the script, there are no requirements I used the built in libs. <br>
sorry of it's unreadable I was kinda in a hurry, maybe I'll fine tune the script whenever I find the time. <br>
the python version i was using at the time python 3.11.2 . <br>
## Example:
`python path_env.py`


## Output:

```
[1] starting extracting_executables
[2] finished extracting_executables
--- CalledProcessError Caught ---
Command returned non-zero exit status 1.
However, the command's standard output was captured (partial or full list):
[[--]] extracting writables ----_______-----
[[--]] here are the common executbales : -----
/usr/local/bin/gospider
/home/alo/go/bin/waybackurls
/usr/bin/pcapxray
/usr/local/bin/pcapxray
/usr/local/bin/jadx-gui
/usr/bin/trace
/home/alo/go/bin/nuclei
/home/alo/go/bin/subfinder
/usr/local/bin/localtonet
/usr/local/bin/jadx
/usr/local/bin/subl
/usr/bin/ip-tracer
```
