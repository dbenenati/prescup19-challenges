<img src="../../logo.png" height="250px">

# Winston Wolf
#### Category: Analyze
#### Executive Order Category: Analyze and Investigate
#### <a href="https://www.youtube.com/watch?v=xa9ikuVis-8&list=PLSNlEg26NNpyjtUujhwW16SkJbuE9Pppe&index=32">Video Walkthrough</a>

## Background
You're trying to learn more about a new type of malware, but it won't continue
if it detects that it is running inside of a VM.

You must clean the VM of all references to virtualization so that the binary
will download the malware and thereby give you the flag.

## Getting Started
To begin, you need an existing Windows 10 virtual guest (e.g., on VMWare).

**Caution!** Before beginning the challenge, we strongly recommend taking a
snapshot of the VM in a working state, to serve as a restore point after
completing the challenge.

Once you have logged on to the Windows VM, unpack `WinstonWolf.zip` into your
`Downloads` folder, and follow the instructions in the resulting `README` file.

**Please Note:** This challenge has been modified from its original form to
work locally on your own Windows 10 VM.

The flag is in the form of GPS coordinates (e.g., `##°##′##′′N ##°##′##′′W`).

## License
Copyright 2020 Carnegie Mellon University. See the [LICENSE.md](../../LICENSE.md) file for details.
