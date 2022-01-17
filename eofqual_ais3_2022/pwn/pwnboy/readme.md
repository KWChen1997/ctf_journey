While I was a little boy I always want to pwn a game console, and today my dream finally comes true! (...or not?)

Challenge
The challenge is a open-source project:

https://github.com/sysprog21/jitboy
commit hash: 335079cc82e73f5b51291cba577130c708757f26 (latest)
Your goal is to pwn jitboy with a custom GameBoy ROM.

Challenge server will request for ROM data and run the emulator by jitboy /path/to/temp/rom.gb (take a look at run_gameboy.py)

nc edu-ctf.zoolab.org 13337

Debugging
A Ubuntu 20.04.3 virtual machine is also provided for debugging purpose, it runs the service on port 13337, the environment is almost identical to the challenge server. (check USAGE.md in the zip)

Ubuntu_pwnboy.zip (~4.2GB)
Although some offsets for solving the challenge may be different if you directly run the binary with jitboy rom.gb on Ubuntu (server use xinetd to spawn process), it could be solved with a simple trick in your exploit :)

p.s. flag is located at /

p.p.s. I encourage you to build from source for debugging
