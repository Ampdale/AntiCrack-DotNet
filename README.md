# AntiCrack DotNet
project contains a lot of anti debugging and anti virtualization techniques, etc.... Notice trying Crash Non-Managed Debuggers with a Debugger Breakpoint technique may stop the application from continue checking, if that happens just restart the program.
# Anti Debugging
CloseHandle

Hide Threads From Debugger

IsDebuggerPresent

GetTickCount

OutputDebugString

OllyDbg Format String Exploit

FindWindow (looks for bad window names)

NtQueryInformationProcess: ProcessDebugFlags, ProcessDebugPort, ProcessDebugObjectHandle

Patching DbgUiRemoteBreakin

Debugger.IsAttached

Detection of Hardware Breakpoints

Others....
# Anti Virtualization
Detecting Sandboxie

Detecting Comodo Container

Detecting Qihoo360 Sandbox

Detecting Cuckoo Sandbox

Detecting VirtualBox and VMware

Detecting HyperV

Detecting Emulation

Checking For Blacklisted Usernames

Detecting KVM

Detecting Wine

Making Sandboxie Crash Your Application (this exploit no longer works, it's patched by sandboxie, that's what i get for making things public :), now it works only with older versions of sandboxie)
# Anti Dll Injection
Patching LoadLibraryA

Patching LoadLibraryW

Taking Advantage of Binary Image Signature Mitigation Policy to prevent injecting Non-Microsoft Binaries.
# Preview
<img width="960" alt="AntiCrackDotNet" src="https://user-images.githubusercontent.com/90452585/174461821-1c033bc6-6eaf-441b-b798-196858495e71.PNG">
