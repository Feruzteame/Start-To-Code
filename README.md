# Starting-Code

Some helpful points before start to code

* How To Master Google

* Text Editor

# How To Master Google

Here are a couple of tips to master your Google searching skills:

## Search in English

English is **_the_** language of the world.  
The chance that you find something useful in dutch, french, or your mother tongue regarding your search is way smaller than in English.

#### Use quotation marks and remove specific info

Using quotation marks in Google search will search for those EXACT words on websites. This can be very handy when looking for error codes. But always do a first search without quotes, sometimes you get lucky.

For example, if you get the following error message:

```
Warning: Cannot modify header information - headers already sent by (output started at /path/to/geeklog/public_html/config.php:581) in /path/to/geeklog/public_html/system/lib-sessions.php on line 180
```

You could copy paste that into the Google search bar, break it down into the core words, remove the stuff that is specific to your files,
wrap it in quotation marks and look it up. Your Google search would look like this:

```
"Warning: Cannot modify header information – headers already sent by"
```
#### Searching on a specific site

Type "site:" followed by the url of the site you wish to search on.
For example you could search the above line of text and limit results to stackoverflow.com.

Example:

```
site:stackoverflow.com "Warning: Cannot modify header information - headers already sent by"
```

#### Add the language/framework you use

If you are looking to solve issues with your coding always try to write in front of the search the name of the language you are using. That will limit results to that language.

Example:

`HTML table` 
`CSS flex`   

#### Improve your search step by step

Improve your google search step by step and come closer to the perfect answer gradually to learn more about the process. If your first search gives too many and too generic results, add some keywords.

Example:

```
CSS boxes
CSS flex
CSS flex direction
```

#### What important words (keywords) would the website you are looking for use?

Don't use a fully formed question, delete prepositions and punctuation, use a professional tone.  
For example, instead of `I'm looking for a job in Gent` try to serach `Jobs developer Gent`.

## Other fun tips

#### What does Google know about my site?

```
site:pixeline.be
```

#### Who is linking to my site?

```
link:yoursite.be
```

#### Find related sites

```
related:pixeline.be
```

# Text-Editor

A text editor is a type of computer program that edits plain text.Text editors are provided with operating systems and software development packages, and can be used to change files such as configuration files, documentation files and programming language source code.
[More about Text-Editor](https://whatis.techtarget.com/definition/text-editor)

#### Here are the most popular code editors currently on the market.

* Atom
* Brackets
* Notepad++
* Sublime Text
* Vim
* visual-studio code

[Read more](https://kinsta.com/blog/best-text-editors/)

### visual-studio code

Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux.

#### Why visual studio code

[Why visual studio code](https://code.visualstudio.com/docs/editor/whyvscode#:~:text=Edit%2C%20build%2C%20and%20debug%20with%20ease%23&text=For%20serious%20coding%2C%20you'll,and%20navigation%2C%20and%20code%20refactoring.)

[Top visual studio Extension](https://code.visualstudio.com/docs#:~:text=Visual%20Studio%20Code%20is%20a,for%20JavaScript%2C%20TypeScript%20and%20Node.)

#### Basic visual studio Extension

##### Live server

This extension is used for launching a development local server with a live reload feature for static and dynamic pages. This saves times for previewing the changes made to your source code by just making the changes in the VS code and saving the file. This will automatically refresh the browser and reflect the changes you have made in it, instead of us manually refreshing the browser page.
[Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

##### beautify

This extension is used for formatting files like HTML. The unformatted code in these files is converted into formatted, readable code by this extension. You can set this setting in the VS Code preferences, which will then automatically format all the code you have typed in the editor.
[beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)

##### spell-checker

The goal of this spell checker is to help catch common spelling errors while keeping the number of false positives low.
[spell-checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
