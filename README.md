# Installation
Just overwrite source code of Abinit with this directory, and recompile Abinit. Please note that I modify the source code based on the version of 10.6.7. Modification part is commented with '! LLZ'. 
# Usage
Two new variables 'getgw' and 'getgw_filepath' are added, whose usage is the same as other 'get' variables.
# Example
In directory `example/`, there is a task setting `bs_calctype` as 1 to read external GW file named as `lalala_GW` set by `getgw_filepath`. This task can be implemented by
`abinit > run.log 2> run.err &`
