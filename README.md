# copypasta
 Scripts to copy and paste files and folders from the terminal. It uses a clipboard system to copy.

![](https://github.com/codelif/copypasta/blob/main/res/demo.gif)

## Requirements
1. python3
2. rsync

## Installation
1. Add the scripts (`copy` and `paste`) to your PATH.
2. Done (read note please)

**Note**: Please note that ``paste`` program also exists in GNU coreutils. So if you use that command then rename this ``paste`` to something else you prefer. eg. ``pastef`` - **paste f**ile.

Otherwise ensure that the PATH folder you put these scripts has higher priority over the one which contains ``paste`` GNU program. <br>
You can do so by putting this in your shell config
``export PATH=/scripts/folder:$PATH``

**Note 2**: ``paste`` script in this repo is not a substitute for the one in GNU coreutils. (duh) 
