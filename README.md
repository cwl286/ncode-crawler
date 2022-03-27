# ncode-crawler


Python

This is a script to create epud and mobi by fetching novels from [ncode](ncode.syosetu.com/).

[epub example] (https://drive.google.com/drive/folders/1fKXPQ9-_Ag04EQQo0SFiHUbkqyHS0-Iw)
[mobi example] (https://drive.google.com/drive/folders/1bU3aygB0_vMWCzvsyJLs_p5cPy8gkJJa?usp=sharing)

INPUT = {basename} of url (https://ncode.syosetu.com/n4698cv/)[https://ncode.syosetu.com/n4698cv/)]
e.g. INPUT = n4698cv

#### Note
* It mounts Google drive
    * create two folder for each novel 
    * e.g. a orignal html folder "n4698cv" and a parsed html folder "n4698cv_org"
    * Copy parsed htmls to Colab drive
* It will download all episodes in Colab drive.
* It will parse all into html and generate epub and mobi.
* Copy htmls and parsed htmls to your Google drive


#### Folder structure
Google Drive <br/>
├──syosetu <br/> 
&emsp;└──epub <br/>
&emsp;└──mobi <br/>
&emsp;└──n4698cv <br/>
&emsp;└──n4698cv_org <br/>
&emsp;└──... <br/>
