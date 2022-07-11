---
layout: post
title: A perfect distro choice
subtitle: Choose a distro
tags: [question]
---

## What is "distro"?
Distro full form distribution. Here, distro refers GNU/Linux variety and flavours. Put your fun in real computing world, wander new features or even more better, with GNU/Linux.

## Why GNU/Linux and distro is important?
As today, most of computers have always preinstalled Windows Operating System. However, Windows isn't a great learning platform even if you're a low-level developer or not. Windows is closed-source software, means you can't see it's source code. Trying to reverse engineering the source code, may result Microsoft can sue you for legal reasons. In fact, you don't own your own the copy of Windows operating system, if you ever read EULA (End User License Agreement), Microsoft clearly says,
> The software is licensed, not sold. Under this agreement, we grant you the right to install and run one instance of the software on your device (the licensed device), for use by one person at a time.
Even you buy a Windows copy today, the same EULA will be applied, "The software is licensed, not sold", what means that you paid for Windows to get a copy of this piece of software, however it's still owned by Microsoft and they completely reject the proof that your paid for this.

EULA license doesn't make any sense, in general it more like they'll take all of your money, but still it's not your money. In my opinion fasten user by these ways, isn't the right way to do business, they just want to sell their product no matter what. Not owning a single piece of software makes similar, "You don't use Windows, Windows uses you.".

## What GNU/Linux licenses does about it?
GNU/Linux doesn't apply any kind of EULA license (EULA basically intended for closed source softwares). Instead it uses, free licenses, aka Open-source license(s). The most common and popular Open-source license is GNU Public License or GPL. Most of GNU/Linux distros even Linux kernel uses GPL (v2.0) license, applying this license means, you're free to use this piece of software with some criterias.

In a nutshell GPL says...
- The freedom to run the software for any purpose.
- The freedom to study the source code and change the software for any purpose.
- The freedom to share the software with others.
- The freedom to share your own modified versions of the software with others.

These are the main points of GPL. However, there's certain things you should know, (i) GPL requires you must distribute the source code. (ii) Forked or modified version must release the source code and the credits of real author (iii) Same license. You can't modify GPL nor use any other license over it. (iv) If you used a piece of software that is under GPL, you must release the source code of the software where you used the code.

These certain rules are extremly good towards open source. As because it not only blocks companies from sue a piece of popular open source project and make proprietary distribution, but also blocks some cheeters to use open source project and use to own their software (for example using a small base code without giving author credits or not making it open source or both).

## What now, there's about thousands of GNU/Linux distros.
When talking about picking up a distro, lots of people even I alos suffer to choose one of them and stick. However, I was able to make a list about it, after some distro hopping.

There's main two points, you must know before furthur hack.
(i) Simple, lightweight, customizable.
(ii) Eye-candy UI, "quite" lightweight, customizable.
(iii) Easy to use, eye-candy, not lightweight in general, customizable.

After these, there's one thing you must know that all GNU/Linux distros are pretty much same. They all uses Executable and Linking Format (formally ELF) for programs. File and folder structure and basically same, nothing changes, file system mostly uses ext4 or ZFS by default (by the way, you can choose different file system as long as they're not obsolete or not used as a general file system) Windows however can't be compare with this, they're totally different.

Below is the list, that I've made in mind of uses and comfortability.

[Arch Linux](https://archlinux.org/) - A simple, yet configurable from ground zero. Have AUR (Arch User Repository) where various people can put software pre compiled. Recommended for programming, gaming, video editing, etc. It's a rolling release distro, might be unstable in some points.

[Debian](https://www.debian.org/) - A stable distro which is pre-configured by the installer, attentionally follows open source culture. Have large collection of software, drivers, etc. Even have "non-free" repos for proprietary drivers, etc. Recommended for general uses, programming, and privacy releated work. It ships with quite old version of software, which isn't a problem at all. Debian also have a unstable branch, it's mainly for testing purposes, and have rolling newer version of software.

[Devuan](https://www.devuan.org/) - A stable distro whcih is a fork of Debian GNU/Linux, mainly because to remove systemd as an init system. If you know the fight about init systems then you might know how people follows UNIX philosophy, especially (do one thing and do it well). I've already wrote a post about this previously, where I try yo little bit explain what's going on. If you want your system be rock solid but without systemd (as you don't want to bother to remove systemd from Debian), Devuan is great choice for you. One known issue is that, since Devuan is maintained by a very small community, there's a lack of package repos which have a great bandwidth, to fix it you can just follow [this](https://pastebin.com/uTMc2kTf). Recommendation is same as Debian. Don't do any sky jumping while installing it, as the installer is pretty straightforward.

[EndeavourOS](https://endeavouros.com/) - A rolling release based distro, which is based on Arch Linux. Have eye-candy look, with various desktop enviornments, so you don't have to configure anything, most of time, it's ready to go GNU/Linux distro. However a backdraw is that, it comes with a lot of packages which you may never going to use, so before picking up Endeavour, make sure you like "bloats" as previously wrote. Recommended for gamers, daily users, programmers etc. Comes with almost every major desktop enviornments including KDE, GNOME, XFCE, Budgie, Cinnamon, LXDE, LXQT, Sway, i3, etc.

[Void Linux](https://voidlinux.org/) - A rolling release based distro, which also offers quite stability towards newer software. Unlike Arch, it's probably most lightweight GNU/Linux distro, that have XFCE preinstalled and all other stuff within ~900 MiB. This GNU/Linux distro is known for lightweight and systemd free. It uses runit as an init system, and have both GLIBC and MUSL library for core libraries. Recommended for general uses, newer softwares within stable disto, programming, privacy work. You've two options, base installer and XFCE preinstalled version, both are nice. If you're newer in Void Linux, try XFCE version.


## Which GNU/Linux distro would you pick up, or what distro do you use from these?
I use Devuan with XFCE DE. However, I also use LXDE sometimes during my hardware issues. Current PC (Intel Pentium, 2-cores with 4 GiB of ram) make sense to use XFCE and LXDE, somehow. Before I used Void Linux, however, I recenly discovered a bug with lightdm-gtk3-greeter that the DE goes black after login and staying idle state for a while (which lock your systen if there's no human activity and that's where the bug come out, for that I always need to restart either change TTY which is a pain), after this, it made me to move on Devuan for stability reason.

It's not up to me to give to decision what GNU/Linux you should use, I can only advice some distros which I think are the better out there. 