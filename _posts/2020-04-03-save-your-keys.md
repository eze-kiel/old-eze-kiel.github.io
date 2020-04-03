---
layout: post
title: Save your keys
date: 2020-04-03 19:00:00 -0200
categories: en security
---
I'm going to tell you a fun story. The story of a guy who does backup, but maybe not as he should do...

## The backups
The guy in question - let's call him Jeff - knows the importance of saving regularly his data, because failure can't be predicted. So he transfers his files to his home's NAS every one or two months. But Jeff is a meticulous guy : he don't want to copy all his /home/, and don't want to have duplicate files and folders. So he copies the importants folders, one after the other. Jeff knows it is not the best technique, some tools can certainly do it for him. He could also develop his own EPICSHELTER-like script to automate his backups. But Jeff is too lazy for both those options.

So he is here, copying his important folders, all his projects (some of them are not even on GitHUB, so he is right copying them!). After this, Jeff is happy, and goes back to watch some stuff on Youtube.

## The incident
2 months have passed since Jeff did his last backup. One morning, he wakes up from a good night, goes to have a coffee, and then turn on his computer. Once on the log in page, he enters his password, but nothing happen. Surprised, Jeff tries his password again. Nothing. Not even an indication saying 'wrong password'. He reboots and retries. Still nothing. So Jeff opens a terminal and see that his hard drive is completely fucked up. How ? When ? He has no idea...

After trying everything, he decides to re-install Ubuntu. Even if he looses some programs and stuff, it is not a big deal : he can re-write his codes, and the most important things have been saved two months ago. While Ubuntu is installing, Jeff thinks about everything he will have to do to have the same setup as before. "First, install regolith, then configure thunderbird with his mail account", he thought. "But I need to re-install pass too if I want to log to Thunderbird !". It was at this moment Jeff knew : he fucked up.
When he manually saved all his important files, Jeff used the file explorer. So he didn't thought about hidden files. Goodbye GPG and SSH keys ! Goodbye passwords ! Goodbye accounts ! Jeff is left without any password, and ways to retrieve them.

## The lesson
I'm writing this post because today, I have been Jeff. For an unknown reason, my Ubuntu partition died during the night (I certainly destroyed something yesterday while moving/removing files to clean my /home). And I completely forgot the save my GPG and SSH keys, thus depriving me of my passwords at the same time. Just because I didn't copied a file. Just few bytes, that need less than a millisecond be saved.

Hopefully, I had my mail password on a physical support (yeah I know, but it saved my life today !). So in a near future, I will be able to get back all my password, thanks to *forgot your password ?* links. But I learned important lessons today :
* SAVE YOUR KEYS !
* Automate backups, and do them more often !
* Don't be lazy, laziness will stab you in the back when you expect it the least
