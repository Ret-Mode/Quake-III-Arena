This is fork of 3rd Quake engine, with Code::Blocks workspace and few MinGW fixes.

For now Debug/Release works for normal and TA (compiled vm and dlls). Qasm, lcc, qmap and radiant does not (so qvm cannot be compiled yet).
Q3DEST variable could be set in quake3 project properties, so exec goes into game directory directly (so debugging in C::B 
could be done)

I tried to add as little changes as possible; again, I relied on info from 

http://fabiensanglard.net/

and on ioquake3 git account (specially when dealing with VM errors that I couldn't fix on my own)

https://github.com/ioquake/ioq3

Game should be compiled without problems, but DirectSound headers and libs should be present in compiler search 
path (recent mingw editions have those already)
