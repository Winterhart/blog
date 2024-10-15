---

title: Linux Journey

---


My first computer was a `Windows 7`. It was great. I bought it at 12 years old in a Walmart. It was a Compaq laptop.

A year later, I bought a [Macbook Unibody](https://en.wikipedia.org/wiki/MacBook_(2006–2012)#/media/File:Macbook_white_redjar_20060603.jpg). It was perfect, I've played Minecraft on it and it was perfect for high school. 

It was a tank and lasted **from 2008 to 2014.** I had to upgrade the `RAM` and change the `disk` for an `SSD`.

In my last year of high school, I also bought a MSI laptop for gaming. Rolling with two computers became the norm. One for "work" and one for gaming.

The unibody finally died and I had to buy another laptop. At the end of 2015, I bought a [MacBook Pro 15 inch.](https://support.apple.com/en-ca/111935) It was quite expensive at the time for a student. (and still is)
The performances were great, however, I was missing the weight and size of the Unibody. The laptop felt too large and too heavy.


## It fell apart

In summer 2016, I decided to switch to a 13 inch and sold the MBP15. I bought a [Macbook Pro 13 inch](https://support.apple.com/en-ca/111959). Maybe it was a bad batch but the performances were not acceptable.
Installing a `js` project took minutes and everything felt slow. The CPU seems to always be overloaded. I rapidly returned the laptop to Apple and told the seller it was too slow, he looked at me quite surprised.

At this moment, I've decided to try something else than Apple for a while.

## New Beginnings

I bought a [Lenovo Laptop](https://www.newegg.ca/graphite-black-lenovo-thinkpad-e560-mainstream/p/N82E16834321418?Item=N82E16834321418) with `Windows` and I had an iPad mini for school. Looking back on it today, it was a terrible setup.
The laptop was heavy, bulky and slow and the iPad Mini was too weak for any computer task. 

It seems today that I was only tolerating this poor setup because it was a new beginning and it felt okay to not have everything right at the start.

It's around this time that I have also restarted building PCs. An old HP motherboard with a PSU, cheap case and a `RX 470` and I had a good enough gaming PC.

I also started to `dual boot` `Windows` and `Linux`

I bought a Samsung S8, a few months after I was fully in this new ecosystem!


## The Wandering

I call this period **The Wandering**, because I've tried many many distro, laptops and desktops.

From 2016 to 2020, I've had many computers and tried many distros

![centos-example](/centos-7-example.JPG)

Most of the time in dual boot with `Windows`. The systems were never lasting more than 1 year. You see a new distro that looks great or a new package manager in the new distro seems more safe.


After, few days trying you've convinced yourself that this time it's going to be the *final distro* and that this one will be: **stable**, **easy to use** and **safe**. 

**It's distro hopping madness**


This [repo](https://github.com/Winterhart/CentOS7-Setup) is one of the vestige from this **wandering** period.

Distro I've tried:

- `Centos 7`
- `Ubuntu and many Ubuntu flavours`
- `Pop OS`
- `Debian`
- `Arch`
- `Fedora`
- `Manjaro`
- `OpenSUSE`


### Stability

A mistake from my side, or an update that made the whole system fail, the `Windows` OS was something killing my `dual boot` config. 
Often, it was a simple mistake on my side. Often, an aggressive update to the core Linux would spoil the driver.

### Security

It was always difficult to confirm that the setup was safe enough. Is my Firewall configured correctly? Can I trust this unpopular package on the distro package manager? Where should all my passwords be saved?


### Ease of Use

Once your keyboard shortcuts are set up. `Linux` can be quite usable. I remember using [Ranger](https://github.com/ranger/ranger) and a couple terminal based applications for navigation. It was great.

## Building PC

It's during that time (2017) that I've built an amazing PC. I wanted to try something exotic and wanted to try a `dual CPU` build.

I bought two used dual `Xeon` CPU from Ebay, an [ASRock motherboard](https://www.newegg.ca/asrock-ep2c602-dual-intel-xeon-e5-1600-2600-4600-v2-series/p/N82E16813157352?Item=N82E16813157352) a massive [case](https://www.newegg.ca/black-thermaltake-suppressor-e-atx-mid-tower/p/N82E16811133279?Item=N82E16811133279), an EVGA SuperNova `850W` and `32 GB `of RAM.

![dual-xeon-w](/dual-xeon.jpeg)

I've learned a lot. I initially bought cheap fans and the workstation was too loud for me. I've decided to try to put only **Noctua** fans and it worked perfectly.

`Windows` had a hard time figuring out what was going on and I had more blue-screen-of-dead than on a usual PC. Also to play GTA V I had to force the game to run on only one CPU.

Once the details were ironed out, the workstation became my main workstation. I still have it today! The only thing I've changed is the `GPU`.

![task-manager](/dual-xeon-task-manager.png)

Today, it's used to play games anywhere in the house, I think it's called a game streaming PC.

Back in 2017, I've also needed a laptop for school so I bought a very thin [HP Business laptop](https://www.newegg.ca/p/N82E16834265660?Item=9SIA7RD4604177) and ran Linux on it (mostly Manjaro).

## The last straw

The end game setup: my last build was on a Razer Blade 14. It was a great laptop, it felt like a Macbook pro. I got the laptop from 2019 to 2020

![razer-14](https://i.pcmag.com/imagery/reviews/01dnlPma5zFUPFMEpVuAjDx-2.fit_scale.size_1028x578.v1623424646.jpg)


I was on `OpenSUSE`. The `recovery` feature was extremely useful and fixed some of the stability issues for a while. The setup was more mature than in the beginning.
I had a solid recovery option. Good security in place, a password manager, a good user/root setup and automatic task with `systemd`.


It was mainly used to work on my side project: build and secure Kubernetes Cluster on [Hetzner](https://www.hetzner.com/). The project is available at: <https://github.com/Winterhart/hetzpuff>

Working full time during the week, it's always tough to find time for side projects, but I had a four hour block on a Saturday. 
I've booted up and got an update request. I pressed `"Y"`, rebooted and my wifi was gone. **DAM!**

Lucky me, I had the recovery setup. I could just rollback and get it to work again. Few months ago, I had a similar issue and the recovery worked!

This time is was dead 💀. Whatever recovery point I was trying I couldn't get it back.

I was at my father-in-law's house during COVID and didn't have my regular cables, adapter... I started to search his house for ethernet cable and adapter, and then where to plug my laptop in his router. 
Then you need to start searching, who got the same issue on `OpenSUSE` + `Razer Blade 14` (good luck 😂).

It took a big part of the 4 hours, **if not all**. If I remember correctly, I end up completely switching to another driver for the WIFI.


## Retro Time

It was spring 2020, I started to drink espresso, which might have helped with retrospection, who knows.

I remember being incredibly frustrated and thinking: 

> I don't want to spend **any** time fixing my OS. ZERO TIME!


Reflecting back from the time I've moved out of the Apple ecosystem. I realized it was chaos.

Counting the number of distro, installations, customization (`KDE` vs `GNOME`), `hack` to make `X` software work, computer switch, fix after update; the hours lost were simply too large to continue. 
I was not a student anymore and I wanted to work on projects not OS.

At work, I had a Macbook Pro, 16 inch 2019 and it was extremely stable. I never had any issues for months, even with dozens of enterprise software, custom ERP configuration and a large amount of dev tools. 

It never crashes. It could handle updates and stayed fast. (when you think about it it's not that abnormal from a `FreeBSD` descendant)

At that time I decided that it was time to give Apple another chance. I bought a Macbook Pro 13 inch, 2020.

## Good Times

The productivity went up!

![gif-prod](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExeHo1M21vNGJycmtqbzF5M2o4NnI2cmtldWRxbnpwajRlajhjMWZ5OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/OFlyPwkf6KpxVQi39f/giphy.gif)


It never crashes, I've never had to fix or restore anything. It's also way easier as you don't have to switch OS or keyboard shortcut from work to personal laptop.


As soon as you realize that your time = 💰, you go for **stability over customization** for your OS.
**My side project time stays on my side projects** 😘


I only have good feedback about the ecosystem. Since then I bought another Macbook Pro, 14 inch on M3, my spouse also moved from `Android`,`Windows` to fully Apple. 

I still love Linux but for servers and projects + they usually run in `Docker` containers.


### Why did I leave Apple?

I moved out of the Apple ecosystem because of a bad batch of Macbook Pro. My trust in the ecosystem took years to come back.

It's interesting how the MBP is the driver to buy an iPhone and the iPhone is the driver to buy AirPods, Watch... 

Without a good MBP, the ecosystem falls apart for me. The MBP is the bedrock.

## What if it starts to fall apart?

It's a question that I've started to think of, what if it starts to fall apart. 

What reason could make it "fall apart" for me?

- Another bad batch of MBP for few years
- Frequency of MBP replacement become too high (e.g. after two years it's super slow)
- An unremovable AI software that captures everything you do
- No access to a terminal on the machine
- [...]

**The current backup plan:** try a BSD distro on a very common/popular laptop (hardware-wise)


<br/>
You've made it this far 🎉 Thanks!



