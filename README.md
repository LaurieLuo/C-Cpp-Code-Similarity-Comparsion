## C/C++ Code Similarity Comparision Tool

### Outline:
The core part of the program is built with c++, and the visualization is implemented with web pages.
The code similarity comparison is divided into content comparison and process comparison (AST similarity).   
The content comparison is all written by team members, and the process is limited by technical strength, 
so the open source tool [ast-diff](https://github.com/balayette/ast-diff) on Github is used for customized modification and use.  
The content similarity comparison uses a hash table to count the number of occurrences of C/C++ keywords in the code file, 
and finally obtains the content similarity by calculating the Euclidean distance.   
Finally, the program weights the two similarities to get the total similarity.
### Env:
OS: Ubuntu 20.04 LTS  
clang version 10.0.0-4ubuntu1  
bear 2.4.3  
g++ (Ubuntu 9.4.0-1ubuntu1~20.04.1) 9.4.0  
GNU Make 4.2.1  
cmake version 3.22.3  
PHP 7.4.3 (cli)  
Apache 2.4.41  
### Usage*:
Prepare two compilable C/C++ programs, upload them to the web page one by one, then click to process, and wait a few seconds to get the results.  
### Attention
We worte this as we're freshmen, so there are some stupid codes and stupid structure.
