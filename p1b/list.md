# TODO
1.  kernel
   - syscall.c  add [SYS_getreadcount]    sys_getreadcount,
   - sysfile.c implement int getreadcount(void)
   - sysfunc.h add int getreadcount(void)
2. User
   - user.h add  int getreadcount(void)
   - usys.S add SYSCALL(getreadcount)
3. Include
   - syscall.h add #define SYS_getreadcount



