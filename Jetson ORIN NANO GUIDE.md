# NVIDIA_DLI
Jetson ORIN NANO

While preparing to install the boot image for the Jetson ORIN NANO, I initially attempted to install BalenaEtcher, but encountered issues downloading the setup .exe file. To work around this, I used a VPN to bypass the restriction and successfully downloaded and installed BalenaEtcher.

Next, I flashed the OS image (.img file) onto an SD card and inserted it into the Jetson ORIN NANO to boot the device. However, after booting, I ran into an issue where Chromium wouldn’t launch.

To resolve this, I conducted a web search and found an alternative solution: installing Firefox instead. I followed the method described in the following blog post:
👉 [Firefox Installation Guide](https://m.blog.naver.com/PostView.naver?blogId=zeta0807&logNo=223930848295&navType=by)

After installing Firefox, I faced another hurdle when trying to connect via wired LAN, but by manually configuring the network port settings, I was able to overcome the issue.

