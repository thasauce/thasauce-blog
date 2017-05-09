---
author: Ramaniscence
categories:
- OverClocked ReMix
date: 2006-06-04T04:36:57Z
forum:
- "12"
guid: "349"
id: 1262
title: ReMixing OverClocked ReMix
topic:
- "2815"
url: /2006/06/04/remixing-overclocked-remix/
---

Yesterday Dhsu approached me about heading an OCR Project, but not a project like RotC or the recently released [BotA](http://sf2.ocremix.org). This project would be an OCReMix ReMix project where people create and submit CSS altercations for OCR that could be utilized via Firefox&#8217;s userContent.css or Stylish/GreaseMonkey extension. 

I wasn&#8217;t entirely familiar how possible that kind of thing would be, as I wasn&#8217;t really familiar with altering CSS via Stylish. So I went to work to seeing just how much I could get done, and the result were pretty suprising&#8230;.
  
From the thread over @ [OCReMix:](http://www.ocremix.org/phpBB2/viewtopic.php?t=85377)

Remember when OCR4 came out and everyone was crying about how much it hurt their eyes? Well, I offer you a solution:

<http://ramaserv.thasauce.net/images/OCRCSS/OCR4-Contrast/preview.png>  
<http://ramaserv.thasauce.net/images/OCRCSS/OCR4-Contrast/preview-forums-index.png>  
<http://ramaserv.thasauce.net/images/OCRCSS/OCR4-Contrast/preview-forums.png>  
<http://ramaserv.thasauce.net/images/OCRCSS/OCR4-Contrast/preview-forums-thread.png>

No, that&#8217;s not a sneak preview at OCR5. That&#8217;s a [near] complete reskin of OCR4.

<table width="90%" cellspacing="1" cellpadding="3" border="0" align="center">
  <tr>
    <td>
      <strong>About OCR4 wrote:</strong>
    </td>
  </tr>
  
  <tr>
    <td class="quote">
      OCR4<br /> represents a clean-up of the PHP, XHTML, CSS, and XSLT codebase that<br /> OCR3 initiated. The site is now completely XSLT templated, outside of the forums, and the design itself is dictated entirely by CSS.
    </td>
  </tr>
</table>

DJP was in no way lying.

The only elements I couldn&#8217;t move were:
  

  
-&#8220;Welcome to [www.ocremix.org](http://www.ocremix.org/)&#8221;
  

  
-The java naviation menu
  

  
-Most images (well, I could hide them all but&#8230;ya&#8217;know)
  

  
-iframes

However, the forum CAN and WAS hidden.

The entire site is skinned except for the alphabetical mix pages. There
  
are probably errors here and there, because I haven&#8217;t gone over the
  
entire site yet, but for the most part all core elements are done.

This CSS features:
  

  
-removed top ads
  

  
-no sidebar for the forums
  

  
-[near] complete reskin of the entire site

The CSS file can be found [here](http://ramaserv.thasauce.net/images/OCRCSS/OCR4-Contrast/style.css), and can be used via userContent.css or Stylish Firefox extension.

As for the project itself, I wanna make sure I have a completed CSS file (song navigation included) before I actually start pitching it. I&#8217;ve already setup directories to host images for the scripts, and you can bet you&#8217;ll see a post before the end of the week.