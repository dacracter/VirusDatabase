# VIRUSLIST.md
All viruses are located here.
# DISCLAIMER!!!
NO, I didn't try this myself, I did it with tria.ge.
# 1. Solara Executor
Located in https://github.com/SoIaraExecutor/Solara/blob/main/Solarabootstrapper.exe, don't download this.
**MALWARE:**
**Xworm, Trojan, Rat**!
**Xworm** is a remote access trojan written in C#.
**ACTIVITIES:**
Downloads MZ/PE file,
Drops startup file 2 IoCsm
Executes dropped EXE 1 IoCs,
Legitimate hosting services abused for malware hosting/C2 1 TTPs 2 IoCs.
**MALWARE CONFIG:**
Family: xworm
Version: 5.0
C2: terms-lands.gl.at.ply.gg:1770
Mutex: `IEDKlCyhDzrgbOXA`
Attributes: Install_directory  %AppData%
install_file: USB.exe
aes.plain: `2PdMJ6QjJBphE6Ix7Elemw==`
Proof: ![image](https://github.com/user-attachments/assets/d155cc52-0b6f-4229-8b3e-06f8c04d75e3)

