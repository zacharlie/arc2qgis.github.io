---
title: "Arc2QGIS"
linkTitle: "Home"
weight: 1
menu:
  main:
    weight: 1
---

{{< blocks/section color="dark" >}}
# Welcome to the Arc2QGIS project.

The aim of this project is to provide a platform for documenting and sharing processes for performing specific spatial data system workflows that may be familiar for users of proprietary systems, to achieve the same outcomes in an Open Source context.
{{< /blocks/section >}}

{{< center cols="10" >}}
{{< blocks/section color="white" >}}
Not sure if this is an accessibility violation, but having multi-lingual landing might help navigate folk to the right parts of the site easier than the language switcher
{{< /blocks/section >}}

{{< tabpane >}}
  {{< tab header="English" >}}
    Welcome
  {{< /tab >}}
  {{< tab header="Español" >}}
    Bienvenido
  {{< /tab >}}
  {{< tab header="Deutsch" >}}
    Willkommen
  {{< /tab >}}
  {{< tab header="עברית" >}}
  ברוך הבא
  {{< /tab >}}
  {{< tab header="日本語" >}}
    ようこそ
  {{< /tab >}}
  {{< tab header="Kiswahili" >}}
    Karibu sana!
  {{< /tab >}}
{{< /tabpane >}}

{{< blocks/section color="light" >}}
## Objective
  
Well this is just the homepage, and I still need to migrate all the content
{{< /blocks/section >}}

{{< blocks/section color="white" >}}
## Motivation  

This site uses hugo and the docsy theme. The setup is a pain in the butt, but it provides a few things over and above the legacy platform. Just for justifying the rationale, here are some elements to consider:

- The previous site was static vanilla html. That's a bit of a challenge to manage larger sets of content, but it also radically increases the barrier for entry for new users. Migrating to a static site generator will help community contributors get going on the system.
- Jekyll would be great for GitHub pages. Just add a theme from the UI and add markdown content. But that simplicity results in a flexibility challenge. If you require additional functionality - custom blocks, content, navigation aids, i18n, or larger document sets, this could be a pain.
- Hugo is FAST, widely used, and very flexible. And I use it in other projects so I get personal benefit and everyone has to deal with it, lol. You can use custom shortcodes and blocks which can extend already robust themes and do many fantastical things though.
- Docsy is a pain to set up, but it has an example site and docker image for compiling and getting going fast. Despite needing extended-hugo-and-node-and-post-css-et-al actual contributors need only modify markdown content really, and the rest can be handled by GitHub actions.
- Docsy is backed and released by Google, is designed for and used on large documentation projects, and has a host of featues that whilst increasing the tie to bootstrap a site, I've (hopefully) handled most of that already and now we have a host of useful functionality, inlcuding OOTB i18n and multilanguage support, a nifty site structure, and a theme, that while not the most pretty and maybe a little bloated, offers great a11y and navigation for large doc sets. Yay us.
{{< /blocks/section >}}

{{< /center >}}

{{< center cols="10" >}}
{{< blocks/section color="white" >}}
## Content
  
Who cares! Let's look at some stuff...
{{< /blocks/section >}}
{{< /center >}}

{{< cardpane >}}
{{< card header="**Imagine**" title="Artist and songwriter: John Lennon" subtitle="Co-writer: Yoko Ono"
          footer="HOPE">}}
Imagine there’s no heaven, It’s easy if you try  
No hell below us, above us only sky  
Imagine all the people living for today…  
  
Imagine there’s no countries, it isn’t hard to do  
Nothing to kill or die for, and no religion too  
Imagine all the people living life in peace…  
  
Imagine no possessions, I wonder if you can  
No need for greed or hunger - a brotherhood of man  
Imagine all the people sharing all the world…  
  
You may say I’m a dreamer, but I’m not the only one  
I hope someday you’ll join us and the world will live as one  
{{< /card >}}


{{< card header="**Right in Two**" title="Written by: Maynard James Keenan" subtitle="Justin Chancellor, Danny Carey, & Adam Jones"
          footer="DISMAY">}}
Angels on the sideline  
Puzzled and amused  
Why did Father give these humans free will?  
Now they're all confused  
  
Don't these talking monkeys know that Eden has enough to go around?  
Plenty in this holy garden, silly monkeys  
Where there's one you're bound to divide it  
Right in two  

Angels on the sideline  
Baffled and confused  
Father blessed them all with reason  
And this is what they choose?  
  
Monkey killing monkey killing monkey over pieces of the ground  
Silly monkeys, give them thumbs, they forge a blade  
And where there's one they're bound to divide it  
Right in two  
  
Monkey killing monkey killing monkey over pieces of the ground  
Silly monkeys, give them thumbs, they make a club and beat their brother down  
How they've survived so misguided is a mystery  
Repugnant is a creature who would squander the ability  
To lift an eye to heaven, conscious of his fleeting time here  
  
Cut and divide it all right in two  
  
Fight over the clouds, over wind, over sky and  
Fight over life, over blood, over air and light  
Over love, over sun, over another  
Fight for the time, for the one, for the rise and  
  
Angels on the sideline again  
Benched along with patience and reason  
Angels on the sideline again  
Wondering where this tug of war will end  
  
Cut and divide it all right in two  
Right in two  
{{< /card >}}

{{< /cardpane >}}
