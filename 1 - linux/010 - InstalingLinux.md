Instaling Linux

Instaling linux on a computer is a simple process. In this guide we will cover all the necessary knowladge.

* Make Boot drive
* Use boot drive to install linux
* return the drive to normal (optional)

## Context information (optional read)

What is an OS

if you want to undestan a bit more about what instaling an operating system is what is linux and why we have to do the fallowing steps read on.

Windows , Mac OS and Linux are all Operating Systems. Operating System is a peice of software (program) that what controles the hardware(physical Parts like Cpu, Gpu, memory) on the computer so other programs work. It serves a **tranlator** so when one progam (aka app) like calculator does not need to be programeed for every possible hardware part. Calculator talks to the OS and the Os Talks to the hardware.

Operating System are complicated and do many things like translating as said above but also take care of essencial programs that users need so they can use other app are resposable for. like keeping time, talking to periferals keboard or mouse...

Operating Sustem is vague term for the progam that do that kind of thing its kind of like and motorveicle most people think of cars but trucks 4 wheel bikes and SUV's are diferent all motorveicles. It depends on prefece and needs of the user. For this reason theres no point in tring to perfectly pindown what it is or what makes part of it. We all know what a motorveicle is no point is fithing over the details.

## why are Opering Systems important

Operating System have to achive many tasks:

* security
* Being simple to use even for non tech people
* Not break
* Working with as much programs as possible
* being easy for the use to adap to its needs

when theres so many requirments we must make consesions... What the consetions are were Linux and the open source communioty difere from windos and Mac OS. 

This big compannies see the user as a means to an end, they make the os so it works peopel use it and so they make money. The end goal is monetary gain. In partiucalr they chose to the there users as dumb. They then make choises here that restric the users 
..

# Making the boot drive

In this precess is we **place a operating system on a usb drive** and then use that usb drive to start the computer, aka boot the computer from the USB , this will mean that you can test the OS witout instaling it. You can even just use the drive to use a linux os on other computers. 

The big disadvantage of this is that usbs are slow so all the OS will be loaded into the ram memory with is fast but scarese. But when you start to make complex task like instaling and running programs as soon as thres not enough ram things will slow down as the sytem is forced to use the usb (slow) memory.

For testing the OS seing how it looks and fills and works, and using simple aplications like browsing internet and wring text files it will be very fast.

1. [Download](https://pop.system76.com/) Pop OS Image (any disto will work)
2. [Download](https://www.balena.io/etcher/)  and belena Etcher
3. Insert the usb
4. Install and run Belena etcher
5. On belena etcher select usb and image and press next.

Start by downloading the image you want to build, just go to google and serch the distro you like pop a good one so is ubunto. Don't lose to much time with it as all distros are more or less the same.

> it does not matter if you install belena or place the usb in frist no need to worry =)

Belena Etcher is the software that will write that image to a USB and make sure it can be booted from.  Its a simple program you chose what drive you want to make bootable and what image you want to place in it and press next. This will take a few minutes once is doen your bootable drive is ready.

> **Warning:** Be carefull to chose the right drive... if you install on the wrong one you will delete data that was in it.
> 
> Make sure you only have one usb in, the one you want to make into a boot drive, so there no mistakes. Belena mormaly knows you want to do it to a usb and not the computer memory but you should cheak anyway that its the right drive.

## Booting from the drive and Instaling linux

1. Turn off secure boot
2. Turn of Fast start up
3. Make the bootble drive fist in the queue
4. test OS
5. install the OS

> **Warning :** Turning off secure boot will affect your Windows install, if it's encrypted. Encrypted Windows can only boot in secure mode - reddit user [alexeiz](https://www.reddit.com/user/alexeiz/)

The process of **turning off Secure Boot and Fast Boot** depends on the bios. Google how it works for your motherboard if you have a tower or laptop model if you have a laptop. Make sure to not skip this steps
In genereal you just need to find a option to **disable safe boot** and togle it off same with the **Fast Boot**. Then you **find the boot queue and place usb on number one** finaly **save and exit**. Your pc sould boot normaly into linuz instead of windows.

Test the distro and see if you like it. Can also cheak that the pc as sound and can connect to the internet. If all seams well press the install icon. Its pretty much next, next, next... untill its done.

Again make sure you are instaling the OS in the right drive and also you will be required to insert a password. Its important you rember this password.

## Switching your Desktop envirment

Can use The comand to change you desktop envirment make sure you have internet first. No need to reinstall a diferent distro.

```
sudo apt install kde-standard // will install KDE
sudo apt install xfce4 xfe4-goodies // xfce
```

The fallowing is a Pop OS Guide on how to change to these envirments and others.

[Desktop Environment (Change) - System76 Support](https://support.system76.com/articles/desktop-environment)
