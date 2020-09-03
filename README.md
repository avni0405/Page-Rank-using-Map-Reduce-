# Page-Rank-using-Map-Reduce

## Quick Tour in Page Rank Algorithm

  It is an algorithm for ranking web pages based on their performance.
  It is used in google to sort the search results.
  It is an iterative graph processing algorithm

## Step to Execute Program

    Create input and output directory in hadoop
      hadoop dfs mkdir /input
      
     Put input.txt file in this directory
        hadoop dfs -put input.txt /input
       
     Create .class file using javac
        javac -cf filename {classpath}
        hadoop classpath can be viwed by running hadoop classpath command
        
      
    Create Jar file
        hadoop jar {nameofjarfile} *.class
       
    run program
        hadoop jar {nameofjarfile} {nameofdriverclassfilename} {/inputdirectoryname} {/outputdirectoryname}
        
## Horray!! Program ran sucessfully!!
