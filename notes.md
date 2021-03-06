# Notes
**Terms**
* constructivist - educational theory acknowledging people have prior experiences/knowledge prior 
  * contrary to realist? (observer-independent reality)

**Anaconda commands**
* pwd - print working directory (you are here)
* dir - show files in folder
* cd [directory name] - change directory
* cd .. - go back up a level
* mkdir [directory name] - make directory
* -r - recursive
* -np - no-parent (stay in domain)
* -l - links beyond domain
* -w [seconds] - wait time between requests to the server
* --limit-rate=[bandwidth limit]

## Problems
* wget isn't downloading anything
  * have to invoke wget using **wget.exe** not just wget

![error](https://github.com/kieranheffernan/week-2/blob/master/error2.PNG)

* R Studio won't download
  * Must download from web, not Anaconda
* Need to download Rtools
  * Including putting Rtools on the PATH by running `writeLines('PATH="${RTOOLS40_HOME}\\usr\\bin;${PATH}"', con = "~/.Renviron")` in Rstudio
![Rtools](https://github.com/kieranheffernan/week-2/blob/master/rtools.PNG)
