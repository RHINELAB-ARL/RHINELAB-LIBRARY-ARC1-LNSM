# RHINELAB-LIBRARY-ARC1-LNSM
RHINELAB logistical library archive, serial 1, designated for lecture notes (LN) and study materials (SM). 

## Shorthand
For now, we have the following shorthands for directory. The inner level would be free choices. 
- `DIR-1` is for **personal notes and recollections**, mostly free spaces for RHINELAB members. 
- `DIR-2` would be for external notes taken or retrieved from people, or materials from faculties, body of training/learning, and documentations related. 

Large files are tracked by LFS. For now, the following type files are tracked: 
```shell
* text=auto eol=lf
*.gif filter=lfs diff=lfs merge=lfs -text
*.png filter=lfs diff=lfs merge=lfs -text
*.jpg filter=lfs diff=lfs merge=lfs -text
*.jpeg filter=lfs diff=lfs merge=lfs -text
*.pdf filter=lfs diff=lfs merge=lfs -text
```
For people using `DIR-1` i.e. RHINELAB members with personal notes, please follow the creation of new folder as:
```shell
DIR-1/
├── index.xxx # (stub files, this is just the index I will add)
└── YOUR_NAME_AND_SIGNATURE/ # <- this is your new folder
    ├── notes.txt # <- your notes will go in here. 
    ├── notes2.md
    └── ... # other files
```
Here, `SIGNATURE` can be anything that distinguish you for your own sake in such. For good-deed under assumption, **do not modify other people's note**, and stay within your own folder. Thank you for your understanding. 