# SIL801
Influence of celebrity media choices on their followers

Collaborators : Nikhil Verma, Nipun Gupta

Instructions to use the jar:

Set proxy int the terminal (if proxy) by: a. export http_proxy=http://username:password@proxyhost:port/ b. export https_proxy=https://username:password@proxyhost:port/

Keep the media domains file in the same directory as the jar.

Use command: java -jar UrlExpander.jar "NUM_THREADS" "PathOfTweetsFile" "PathOfOutputFile"

NUM_THREADS: Keep it so as to obtain CPU usage around 100%, for 4 cores and 8 GB RAM, 500 is suitable PathOfTweetsFile: Path of the file to be processed PathOfOutputFile: Path of the output file, an empty file need not be created

split.sh: it splits all text files in the current folder

run.sh runs code for all data files, keep mediaDomains and jar in the same directory


