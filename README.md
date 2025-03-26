# txtUDL
A bit of a personal front-end/ui project for myself. I take a lot of notes in simple text files and use notepad++ a lot.

So this is a Notepad++ User Defined Language for .txt files to make it automatically do some formatting without the need of a markup language extension. Instead, you simply import this .xml in as a User Defined Language, and you can either manually set specific files to be interpreted by this UDL or you can set it to open all of your .txt extension files this way.

Designed to make it easier to read and write my personal notes.

To use it you have to donload the .xml, click the Language dropdown, hover User Defined Lanugage > Define Your Language.
Then click Import, and click Save As to have that language appear in the Languages dropdown. Just make sure you don't save it as anything with "Markdown" or else notepad will do a weird switch to Markdown(Preinstalled). It still works but it's weird. So that's why I save it as Txt Markup.
If you have any .txt files it won't apply until you close and reopen them or select the language manually for each, but it should apply to any .txt files you open afterward.

<img width="169" alt="to do screenshot" src="https://github.com/user-attachments/assets/cd7764a5-a671-4c31-bfb8-f3848a05d91e" />

<img width="189" alt="to do screenshot 2" src="https://github.com/user-attachments/assets/021c0998-4cb9-4ddc-99b3-a699160fef8c" />

<img width="341" alt="to do screenshot 3" src="https://github.com/user-attachments/assets/4ffdcdeb-3c39-4d9b-af07-b895865c1e0d" />

<img width="290" alt="image" src="https://github.com/user-attachments/assets/3d617701-1640-422a-a444-d038349da412" />

Features:
* 3 types of heading delimiters (delimiters all highlight text until the end of the line):
* #! Large underlined bold, ## Medium Italic, #. Small underlined bold
* 3 types of comment delimiters:
* // comments - set to blue. Links starting with https:// will also be set to this color blue.
* ~~ comments - set to yellow. I like using this for divider lines so I can do like ~~~ NEXT SECTION ~~~
* -- - same color as text, but bold and italicized. Used for term definitions.
* Numbers colored and work with parentheses, ~2 for appx numbers, k M for thousand/million, am pm, , and . for using in sentences, - : ^ for ranges, times, and exponents.
* two types of list bullets: just letters and numbers. a. 1. set to work from 0-20 and a-z A-Z. However, there's currently a problem where the number colors overrule this bullet point formatting. You can do 1.a. and it will work fine though. Current workaround for numbered bullets is to use two periods 1..
* A second color for list bullets ! a-z! A-Z! 0-20! have hot pink for emphasis.
* YYYY-MM-DD dates are highlighted orange as long as the year is 202X
* arrows -> <- --> <-- highlighted red
* _____ ----- highlighted as line dividers
* Month names and DOW names / abbrevs are highlighted

https://github.com/nordtheme
I use this nordtheme for my base colors for notepad++ and have built the colors around that.
The more important part of the UDL is having a reasonable basis for all the rules in place so that customizing the colors is easy. 

Continuing to make qol improvements as I see them. 
