# OS Project 2 (Group 12)
**Team Collaborated Project - Synchronous Virtual Device**
## Source Code Folders
* `./data`         : input/output data
* `./ksocket`      : the device moudule including the funtions used for kernel socket
* `./master_device`: the device moudule for master server
* `./slave_device` : the device moudule for slave client
* `./user_program` : the user program `master` and `slave`


## Executing Procedures
1. switch to super user (`$sudo -i`)
2. execute `./compile.sh` to compile codes and install all modules
3. follow the input instructions in the specs. i.e.
`./master ../data/file1_in mmap`
`./slave ../data/file1_out fcntl 127.0.0.1`

## Notice
* Make sure that you are under the path `./user_program` when you execute user programs.
* Though the execution order of user program `master` and `slave` does not matter, it is recommended executing `master` first to have more accurate transmission time.
