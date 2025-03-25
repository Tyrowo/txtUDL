# txtUDL
A bit of a personal front-end/ui project for myself. I take a lot of notes in simple text files and use notepad++ a lot.

So this is a Notepad++ User Defined Language for .txt files to make it automatically do some formatting without the need of a markup language extension. Instead, you simply import this .xml in as a User Defined Language, and you can either manually set specific files to be interpreted by this UDL or you can set it to open all of your .txt extension files this way.

Designed to make it easier to read and write my personal notes.

To use it you have to donload the .xml, click the Language dropdown, hover User Defined Lanugage > Define Your Language.
Then click Import, and click Save As to have that language appear in the Languages dropdown.
If you have any .txt files it won't apply until you close and reopen them or select the language manually for each, but it should apply to any .txt files you open afterward.

<img width="169" alt="to do screenshot" src="https://github.com/user-attachments/assets/cd7764a5-a671-4c31-bfb8-f3848a05d91e" />

<img width="189" alt="to do screenshot 2" src="https://github.com/user-attachments/assets/021c0998-4cb9-4ddc-99b3-a699160fef8c" />

<img width="341" alt="to do screenshot 3" src="https://github.com/user-attachments/assets/4ffdcdeb-3c39-4d9b-af07-b895865c1e0d" />

Fixed the wonkiness with the // highlighting links by just making an operator for https:// also does a nice light blue color. 
numbering systems, bullet points, headers.
you can do 1.a. and 1.b. etc, but 1. will highlight like a regular number because I wanted it to highlight numbers when they were at the end of sentences. so to keep the list entries pink you need to do something like 1.. Might need to fix that next.
On the plus side in addition to being at the end of sentences I also improved it to highlight numbers when they're like 1k or 5M or 2pm and ranges of numbers.

https://github.com/nordtheme
I use this nordtheme for my base colors for notepad++ and have built the colors around that.
The more important part of the UDL is having a reasonable basis for all the rules in place so that customizing the colors is easy. 

Will make improvements as I see them. 
