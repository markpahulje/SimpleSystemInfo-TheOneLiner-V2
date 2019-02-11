SimpleSystemInfo-TheOneLiner-V2.ps1

This Powershell script boils down essential non-identifying anonymous system information into 1 line for a post, quote or tweet. 

Example outputs; 

1. Microsoft Windows 10 Pro 1803 (10.0.17134.320), Intel Core i7-2760QM CPU @ 2.40GHz * 4, 32GB DDR3 RAM, Intel(R) HD Graphics Family 2GB VRAM * 3, 1TB HD @ 5,400 RPM
2. THINKPADW530 [42763JZ], Microsoft Windows 10 Pro 1803 (10.0.17134.320), Intel Core i7-2760QM CPU @ 2.40GHz * 4, 32GB DDR3 RAM, Intel(R) HD Graphics Family 2GB VRAM * 3, 1TB HD @ 5,400 RPM
3. Microsoft Windows 10 Pro 1803 (10.0.17134.191), Intel Core i7-4600U CPU @ 2.10GHz * 2, 8GB FBD2 RAM, Nvidia GeForce RTX 2080 Ti 8G SDRAM * 1, 128GB SSD

No more cobbling this together, let's adopt a universal standard. 

Grabs  HD RPMs from P/Invoke ("kernel32.dll") from hard drive manufactures driver information. This gets the most accurate RPMs available, if supplied. No other script is doing this so far.
Added memory type
Adds GPU info, with proviso reports max GPU RAM size, type and description found for brevity

Updates at https://metadataconsulting.blogspot.com/2018/10/Powershell-Simple-System-Info-The-One-Liner-Version-2-includes-HD-RPM-and-GPU-info.html
