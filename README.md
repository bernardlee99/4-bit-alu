4-bit Arithmetic Logic Unit
======================


Clone into Cadence
---------------------
**All these are done within the ncsu160 directory**
1. Git clone the repo into the ncsc160 repo: ``git clone git@github.com:bernardlee99/4-bit-alu.git``
```
[user@host ncsu160]$ git clone git@github.com:bernardlee99/4-bit-alu.git
Initialized empty Git repository in /home/blee13/ncsu160/4-bit-alu/.git/
Receiving objects: 100% (11/11), 5.09 KiB, done.
Resolving deltas: 100% (1/1), done.
[user@host ncsu160]$ 
```
2. Create the project as you would [In Library Manager: File->New->Library]. For sake of consistency, name it as **4-bit-alu**. Use *Attach to an existing technology library* and select the library [NCSU....]. 
3. After the project is created, there will be a `4#2dbit#2dalu`. Issue the command: ``cp -ar ./4-bit-alu/* ./4#2dbit#2dalu/`` 
4. Check the directory: ``ls -Al ./4#2dbit#2dalu/`` and make sure that .git is within the directory.
```
[user@host ncsu160]$ ls ./4#2dbit#2dalu/
and  cdsinfo.tag  data.dm
```


Task and Responsibilities
---------------------
#### Standard Cell Implementation
- [ ] Bernard Lee
    - [ ] AND
    - [ ] OR
- [ ] Dawson Miller
    - [ ] NOT
    - [ ] XNOR
    - [ ] XOR
- [ ] Fox Lane
    - [ ] NAND
    - [ ] NOR


