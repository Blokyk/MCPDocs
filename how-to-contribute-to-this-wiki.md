---
description: 'If you want to help, here''s your guide'
---

# How to contribute to this wiki

## Setting up the right environnement

{% hint style="info" %}
First of all, if you want a complete, proof-read article about how to install MCP, [the Minecraft Wiki page about it](https://minecraft.gamepedia.com/Mods/Creating_mods/Setting_up_the_MCP_workspace) is way better
{% endhint %}

{% hint style="danger" %}
**As any manipulations on the internet, this should be executed carefully**. I'm not responsible for any damage this might do to your data or the integrity of your computer. 

**I recommend reading everything first before doing anything, and then evaluating if you want to take this risk** \(although there's almost none if you're not computer illiterate to be honest, but you never know\)
{% endhint %}

{% hint style="info" %}
Those instruction are only for Windows right now, but I'm working on porting them to Linux, and they're already quite similar, I just have to check that everything is working as expected 
{% endhint %}

### Getting Java SE Development Kit

If you don't already have Java **8** JDK installed, [you can download it here](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html), but be aware of your architecture \(whatever your system is 32-bit or 64-bit, [here's how to know](https://www.computerhope.com/issues/ch001121.htm)\) 

Once you've downloaded it, just run it and follow the instruction

{% hint style="warning" %}
It is strongly recommended to restart your PC after the installation
{% endhint %}

### Getting MCP

{% hint style="warning" %}
This part is only if you want to start from the official release, so that nothing will really influence you in your research. However, you'll need to adapt your content or justify changes if you choose that option \(oh, and there's [some other things you can do too](http://mcpbot.bspk.rs/help) in this case...\).

If you don't want to start from zero but with my own MCP folder \(with javadoc, refactoring, renaming, etc...\), I'll detail it at the end of this article.
{% endhint %}

Download the last stable release of the Mod Coder Pack \(MCP\) at the [official website](http://www.modcoderpack.com/)

I'll be downloading the version I'm currently working on, MCP 940 \(a.k.a. Minecraft 1.12\)

One it's downloaded, go to your Download folder and right-click on mcp940-1.12.zip, and select "Extract All", and choose a directory like "C:\Users\Public\MCP940"

{% hint style="info" %}
From that point on, I'm going to assume that you put your MCP directory where just specified, so you'll need to change some things if you put it elsewhere \(don't worry, I'll tell you\)
{% endhint %}

After the extraction, just go to "C:\Users\Public\MCP940" and double-click on decompile.bat

And the decompilation should now start. Go take a coffee or go eat something \(or even [download and install Eclipse](how-to-contribute-to-this-wiki.md#getting-and-setting-up-eclipse-ide-for-java) ;\), it shouldn't be too long. If you encounter any error, see [this section of the wiki](troubleshooting/mcp-decompile.bat-errors.md#decompile-bat-errors).

### Getting and setting up Eclipse IDE for Java

Eclipse is the recommended IDE for MCP and, more generally, for any Java applications : It is complete, modulable, open-source, etc... So I'm gonna show you how to install it and link it to MCP

### Installing Eclipse

First, you'll need to download the installer : click on [this link](https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2018-09/R/eclipse-java-2018-09-win32.zip) if your computer is 32-bit and that link if it's a 64-bit \(reminder : [How to determine if you have a 64-bit or 32-bit computer](https://www.computerhope.com/issues/ch001121.htm)\)

Once it's downloaded, just run the installer and follow the instructions \(if any errors, [referer to this page](troubleshooting/eclipse-related-errors.md#can-i-become-who-i-want-to-be)\)

### Setting up Eclipse to work on MCP

Once Eclipse IDE is installed, run it : it will ask you to "Select a directory as workspace". If you choose to use "C:\Users\Public\MCP940" to install MCP, then just copy/paste this into the field : "C:\Users\Public\MCP940\eclipse". If you choose another directory, just modify the path, just be sure to add "\eclipse" at the end of the path \(just like above : ""C:\Users\Public\MCP940" + "\eclipse" -&gt; "C:\Users\Public\MCP940\eclipse"\)

{% hint style="info" %}
After Eclipse opened up, you probably have some error \(at least I did\), so just go to [this page](troubleshooting/eclipse-related-errors.md#errors-when-you-first-link-mcp)
{% endhint %}

And you can now explore the Minecraft source code \(kinda, at least\) ! Now, you probably want to know how you can help documenting functions, classes, fields, etc... Well, here's the time for...

## Contribute to this wiki





