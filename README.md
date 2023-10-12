# ENS-Migration
Install Node.js, Docker.

First of All Install and setup Squid CLI in CMD:-
  npm i -g @subsquid/cli@latest
Check Version in CMD:
  sqd --version
Make sure the output looks like @subsquid/cli@<version>.
Now go to gravator-squid/src/processor.ts and run command in Terminal "sqd typegen" 
    if not installed Run "npm i -g @subsquid/evm-typegen"
run in Terminal command in Terminal "sqd codegen"
    if not installed Run "npm i -g @subsquid/typeorm-codegen"
if finding error on "@subsquid/archive-registry , @subsquid/evm-processor , @subsquid/typeorm-store" Run Following Commands
    "npm i -g @subsquid/archive-registry"
    "npm i -g @subsquid/evm-processor"
    "npm i -g @subsquid/typeorm-store"
Run in Terminal "sqd build"
Run in Terminal "sqd up"
Run in Terminal "sqd migration:generate"
Run in Terminal "sqd process"
Run in another Terminal "sqd serve"
Now Done!!!

For Refernce watch this video:- https://www.youtube.com/watch?v=_lMM6h1fBUY

    
