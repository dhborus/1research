## Computer Setup Commentary

### Operating System and Machine

Ordinarily, I would stick with Apple equipment. There are two complicating factors. First, the iPad - iMac scheme is not particularly viable since Karen has, for the most part, laid claim to the iMac. In addition, the iPad had some drawbacks. It's not quite a work machine and has developed some glitches particularly interruptions and skips and difficulty charging (at least with one cord).

Second, it seems clear that Apple will be moving away from the Intel architecture. That will force a choice of paying the Apple tax or using a laptop that is old, slow, and has a draining battery or one with a smaller screen (and possibly a draining battery). Laptops do have the advantage of portability, which will open up the iPad to be an entertainment device only.

As it stands, few of my major apps are OS-dependent. Atom, Zettlr, pandoc-latex, Obsidian, Firefox, and Bitwarden are all plain text or available on different platforms. So a switch to Linux is theoretically possible, although I will eventually be faced with the equipment problem mentioned above.  

So the question is whether Linux will suffice. Can I communicate, research, write, and prepare for publication? Can I find replacements for Alfred, Keyboard Maestro, and MS Word? Can I learn the shortcuts? If yes, the test then becomes whether the 13" is usable. Key will be how well the battery lasts (the 15” works worse with Linux than with MacOS) and how the screen looks at that size.

Linux does have a number of interesting features and advantages. It extends the life of the machine and can do much that the Mac can do. I was able to move the keys so as make basic hotkeys the same (although there is an advantage to separating Linux and Mac shortcuts so as to recognize the differences), set up Autokey for snippets, and found a way to transfer files from Linux to Mac and to use Working Copy to download clips from Firefox on the iPad. Nitroshare (for Manjaro) and SSH are possible tools as well. I do not, as yet, have a full replacement for either Alfred or Keyboard Maestro (K-runner is an approximation)

However, switching platforms is more work than necessary (at least at the moment). I have the muscle memory for Mac, can redeem sunk costs on apps, synchronize through iCloud, possibly use the iPad, and generally avoid kludges. Macbook Pro 15" has a battery problem, but . . . its display and heating are less taxed. Don't recall much fan noise in a month of use with MacOS. Whereas with Manjaro, I heard it right away. The fit between software and hardware is better. As a Mac, actually looks better in terms of scaling and available fonts. Not a deal breaker but helps. So, despite progress, after three weeks I moved back 5 April. **Will try again with Sarah's laptop.** 



#### Distro



As for the distribution, I have solved many of the Manjaro problems -- screen fonts (16X9 rather than X10), email, Dropbox, Autokey usage, update, Zotero picker rather than autocomplete, Mint is solid but it isn't very exciting. Manjaro has great software repositories, although Debian-based distros and easier to learn. I have heard that Manjaro eventually runs into difficulties once updating occurs, so I will keep elementary in reserve since it is terribly solid and is the most Mac-like.

Will need Alfred and Keyboard Maestro replacements (ULauncher comes close).

Working Copy and SSH will allow IOS, MacOS, and Linux exchange.

**Distro Conclusion** Keep Manjaro until it becomes ragged and then replace with elementary os.



### Text Editor

In truth, the difference between Atom and Zettlr is marginal. They handle citations, links, MD conversion to PDF slightly differently. The strength of the search and the overall look and feel are also in play:

**citation** Zettlr can do the footnotes and produce PDFs with footnotes based on the bibtex or JSON file. Atom, on the other hand, is having trouble with autocomplete-bibtex, but Zotero picker works acceptably, although it requires an open Zotero and after return will focus on Zotero.

**links**: Z reads Obsidian backlinks that do not have folder name directly. Atom has a Wikilinks package, which work perfectly but which, like Atom-notes,  must have links that indicate the note and the directory.

**conversion** Zettlr PDF requires YAML on mac (which changes title if different from designated file name). On Linux, straight forward so far

 Atom runs best through the terminal and for PDF is fairly simple: Include YAML, cd to folder, pandoc -s -o (pdf name) --citeproc (md name).

 **searches** Atom slightly more powerful

**storage** Atom more easily store in GitHub, but Zettlr-Obsidian-1writer works perfectly fine with iCloud.


**ease of writing** Atom has dual editor; Zettlr needs kludges with Quick Look. Atom has autocomplete; Zettlr does not. Atom can show PDFs (with package); Zettlr can not but Obsidian can. 

**TextEditor Conclusion** -- Zettlr is easier to read, will do automatic citations, and is a project of an academic. I will stick with it for awhile, especially with Obsidian in split screen. 
