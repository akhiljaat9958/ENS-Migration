# ENS-Migration
Install Node.js, Docker , Git.

1. First of All Install and setup Squid CLI in CMD:-
  npm i -g @subsquid/cli@latest
2. Check Version in CMD:
  sqd --version
3. Make sure the output looks like @subsquid/cli@<version>.
4. Now go to gravator-squid/src/processor.ts and run command in Terminal "sqd typegen" 
    if not installed Run "npm i -g @subsquid/evm-typegen"
5. run in Terminal command in Terminal "sqd codegen"
    if not installed Run "npm i -g @subsquid/typeorm-codegen"
6. if finding error on "@subsquid/archive-registry , @subsquid/evm-processor , @subsquid/typeorm-store" Run Following Commands
    "npm i -g @subsquid/archive-registry"
    "npm i -g @subsquid/evm-processor"
    "npm i -g @subsquid/typeorm-store"
7. Run in Terminal "sqd build"
8. Run in Terminal "sqd up"
9. Run in Terminal "sqd migration:generate"
10. Run in Terminal "sqd process"
11. Run in another Terminal "sqd serve"
Now Done!!!

For Refernce watch this video:- https://www.youtube.com/watch?v=_lMM6h1fBUY

    
