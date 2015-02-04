Preview Handlers Revisited
Bradley Smith - 2010/09/17, updated 2013/10/14
---

If you encounter problems previewing certain types of documents (e.g. MSG 
files), make sure the following is true:

1. The solution platform matches the preview handler architecture;
   i.e. x64 on 64-bit OS with 64-bit Office
    or; x86 on 32-bit OS with 32-bit Office

2. You run the project WITHOUT attaching the debugger.

3. You embed the supplied app.manifest file when building the project.