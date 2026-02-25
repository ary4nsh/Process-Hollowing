# Process Injection
In this repository, you will find simple code examples demonstrating the [Process Injection technique](https://attack.mitre.org/techniques/T1055/), which is used for privilege escalation and defense evasion. 

Adversaries may inject code into processes in order to evade process-based defenses as well as possibly elevate privileges. Process injection is a method of executing arbitrary code in the address space of a separate live process. Running code in the context of another process may allow access to the process's memory, system/network resources, and possibly elevated privileges. Execution via process injection may also evade detection from security products since the execution is masked under a legitimate process. 

Sub-techniques:

[Windows]
- Dynamic-link Library Injection
- Portable Executable Injection
- Thread Execution Hijacking
- Asynchronous Procedure Call
- Thread Local Storage
- Extra Window Memory Injection
- Process Hollowing
- Process Doppelgänging
- ListPlanting

[Linux]
- Ptrace System Calls
- Proc Memory
- VDSO Hijacking
