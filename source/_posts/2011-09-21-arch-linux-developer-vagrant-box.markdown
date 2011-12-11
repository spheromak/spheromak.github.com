---
layout: post
title: Arch Linux Developer Vagrant Box
published: true
comments: true
categories: Arch Linux
---

[Vagrant][1] is sweet!, but there wasn't a lot of [arch][2] boxes out there that i could find. So heres my [Vagrantfile][3].

if you don't already use [Vagrant][1] you should. If you are doing any dev you should use it! if your an ops person then you should use it, and tell your developers about it. If you are a nerd you should use [Vagrant][1]. Nuf said.

[Arch][2] is also pretty sweet. [Arch Linux][2] has a system approach that rings totally right with me (I feel another post about arch in here someplace). Mainly Arch lets you do what you want how you want which is awesome!

Anyhow I have a little pet project that originally I was gonna do an LFS build up on, but realized arch already had a lot of what I needed. [systemd][5] support, and an not ancient/screwed up ruby install.

* [My build][3] deviates from base arch in these ways:  
  * It's running 3.0.4 Kernel
  * Using [systemd][5] (with option to boot sysv)
  * full developer toolchain.
  * [ABS]("https://wiki.archlinux.org/index.php/Arch_Build_System") the source build system for Arch.
  * Its big! ~1.2GB for a base box is pretty big, but its cause of all the build crap + kernel source

Lastly heres the links to the [base box][4] if you don't want to get it via the vagrantfile.

[1]: http://vagrantup.com/ "Vagrant"
[2]: http://archlinux.org/ "Arch Linux"
[3]: http://pipe.f00bar.com/Vagrantfile "arch_dev Vagrant File"
[4]: http://pipe.f00bar.com/arch_dev-x86_64.box "arch_dev Base Box"
[5]: http://www.freedesktop.org/wiki/Software/systemd "ohai systemd"


