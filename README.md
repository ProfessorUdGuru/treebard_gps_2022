# Treebard Genealogy Software

A showcase for genealogy software functionalities written in Python 3.11, Tkinter and SQLite. Being tested in Windows only at this point. Treebard was a full-time project for a hobby-level coder working alone from July 2018 to August 2024. Its main purposes are 1) to prove that a genealogist can write his own app, and 2) to provide a working model of a code base that can be imitated, stolen, borrowed, or otherwise used without permission, participation, or acknowledgement from me, the creator of Treebard, for any legal purpose, from here to eternity. (Donations are accepted at [my website](https://treebard.com/donate.html).) I am particularly fond of the idea that someone will see the light about continuing to limp along with GEDCOM, and instead *just start using* Treebard's database structure (UNIGEDS) or be inspired by it, to give birth to a UNIversal GEnealogy Data Structure which would replace GEDCOM if app developers could be inspired enough to all use the same data storage structure for their app's primary features.

## How to Use this Repo

This project is alive and well and can be downloaded from [the download page](https://treebard.com/download.html). Go to the forum to read the same code without downloading it. This repo used to be here at Github as an example for github-centric seekers to find, but as a team of one I have my own version control, so the former repo "Treebard GPS" and its 314 commits were deleted. Work on the project is actively ongoing through July 2024, when I plan to let others take it from there. "GPS" has been removed from the name. See [the forum/blog](https://treebard.proboards.com) for more details. Work on the free version of Treebard ended in August 2024. The latest version can be downloaded, along with a matching .exe, from [the donation page](https://treebard.com/donate.html).

The only requirement to try out Treebard's currently existing features is a version of Python between 3.8 and 3.11, and pip install Pillow for graphics. The Pillow install has worked effortlessly for me with no other dependencies in spite of what the Pillow docs may or may not still say to discourage novices, as long as I used Python 3.8 or better. To grow your own version of Treebard-like abilities based on my code, you'll also need to install the SQLite command line interface tool. All of this is very easy.

To get your copy of the repo to function, download the .zip from [the website](https://treebard.com/download). There is a functioning fictional family tree database and hodgepodge of test data (sample_tree.tbd) that you can play with, and you can start your own trees from scratch using the GUI.

## News

Chapter Three of Treebard development is now finished in August 2024 after six years of full time work on Treebard. Finishable functioning GEDCOM import and export programs are included. I am proud of my work and I feel that I have already done a good job of raising the bar for genealogy software, even though the app is not intended to be finished, but rather to serve as a basis for projects that could be finished by larger and younger teams. 

## Limitations

I have not adapted any of this code for Linux or MacOS. Tkinter is supposed to be cross-platform and it shouldn't be that hard to make Treebard work on Linux etc.

This is not version 0 or 1. The as-is version currently being developed will never have backward compatibility, everything is subject to change drastically without notice. It's a showcase and testbed for genealogy software functionalities, written in Python. It's meant to be a working model codebase for genieware developers and wanna-be genieware developers to use as they wish, for anything legal and honest that they want to do. Dishonesty or pretending you wrote the code I wrote will be handled by the guardians of the universe. If you try to use Treebard-as-is as a genealogist to seriously create a family tree, it will be a lot of work to keep the code up to date if more changes are made. And it's written in Python, so a large tree might bog down since neither Python nor Tkinter are built for speed.

A better use of your time would be to create the equivalent of Treebard v. 0.0.0--but don't call it Treebard unless you're me--and keep that version backwardsly compatible for your intended customers. Acknowledging my work is not required but is suggested so you can sleep at night.

Python and Tkinter are slower than the compiled languages. I believe a better language for a commercial project would be Delphi FMX/FireMonkey, or Delphi VCL if the app is meant for Windows only. I don't have enough experience with Delphi to recommend it without reservations, but it's free to play with until you start making money from your app. It seems to me that Delphi is the compiled language for developers and neophytes who love Python's "batteries included" philosophy. Delphi also automatically creates an .exe for your app as you work, which is a big benefit, especially for programming hobbyists.

## Treebard is for Everybody

Every version of Treebard that ever exists is supposed to be portable, public domain and open-source, but I have no control over that, it's just my personal preference. The code has always been unlicensed. So you can do what you want with it, use it to create a product for sale, and you can do all this without permission or paying royalties. Donations are accepted and would be appreciated. If you obtain my code by making a donation, the code is still 100% public domain, yours to use as you wish. I've had no problem creating an .exe version with CXFreeze so the curious can try Treebard without installing Python first.

Treebard has gotten too good to give away. Currently in the throes of burnout after about 16,000 hours of work on Treebard, today I have no plans to keep working on it, but I'm also not promising to not go into competition commercially with anyone who uses Treebard-as-is as the basis for their own commercial application. But I am more likely to fiddle around with the website or the YouTube channel than I am to write more code.

## No Installation

Tkinter and SQLite come packaged with Python so if your Windows is in good shape, then there should be no installation or dependency problems to run Treebard, except to install Python and pip install one dependency called Pillow. Without a recent version of Python (3.8 or better), good luck getting Pillow installed unless you're a professional programmer. Without Pillow, nothing will work unless you want to downgrade to using .gif images only and rewrite all the code involving images. Tkinter will handle .gif images without Pillow but this was not a good experience for me.

Installing the SQLite command-line-interface tool is necessary only if you plan to write your own version, which will involve manipulating the databases manually.

To run Treebard, just run the .py file that has `root` in its name and everything else should work to whatever degree it is currently functioning. If you don't know how to run a Python file, try double clicking the .py file with `root` in the name, where it's listed in your file manager. If that doesn't work, you might have forgotten to check the "...Path..." option when installing Python.

## Roadmap to Infinity and Beyond

Treebard's purpose is to demonstrate how things could/should/might work in a genealogy database GUI, so the main point is user experience and attention to detail when it comes to storing data in a useful way for real genealogists who care about details, sources, and the like, *as well as* a pleasant, congenial, intuitive user experience. 

Treebard works for even the most casual users because it's easy to use, intuitive, and doesn't force you to do things in a contrived way requiring lists of instructions. Many first-time users will be able to use it without glancing at any docs or watching [my YouTube channel](https://www.youtube.com/@treebardgenealogysoftware2577/playlists). The code is working for a detailed right-click context-sensitive help menu as well as unobtrusive tooltips that display in the statusbar. Many of the messages for these two features remain to be written but the code for displaying them is finished. The code for the right-click-menu is ready for an upgrade.

Treebard Version 0 could be written in Delphi, or Electron's replacement when it shows up, or JavaScript/SQLite/HTML/CSS. If you want to use more advanced programming languages, just fork the project and let me know how it goes if you want. I'm a cranky old man, and going from Python to a compiled language would be a big jump for an old geezer who's going blind. Running a team effort would be for someone else to do. The disadvantage to using Electron (besides bloat) is the spread of monoculture since Electron is based on google's Chromium like so many other projects. Other applications which use Electron include the open-source editors VS Code and Atom. Both of which are now owned by the owner of Github. (Rant on "monoculture" omitted.)

Treebard is meant to be accessible to novice programmers and hobbyists, so that any genealogist can try his hand at writing his own genieware. I have rejected attempts for more experienced programmers to join the team, because the first thing they want to do is make the code more "professional", i.e. inaccessible to hobby-level coders. Treebard works as-is, and that is what a working model should do, without unnecessary complications, fancy algorithms, or unnecessary dependencies. I've tried to make it work for everybody, make it portable, and I've made it public domain in spite of being a senior citizen on a fixed income. 

My silliest fantasy is a genealogy program that becomes more ubiquitous than GEDCOM. I know, it won't happen just because it should. But the slogan would be, "Don't share a GEDCOM file... share the whole program!" So Treebard has to be portable because I'm a dreamer and because I believe that steep learning curves are an excuse for writing apps without considering the needs of the average user. Apps with a forbidding appearance and a steep learning curve are geekware written for geeks. Nothing wrong with that, but genealogy is just a hobby for most genealogists, and most of those are over 60, and for these reasons I've tried to keep the GUI beautiful and simple-looking while making it able to manipulate complex data behind the scenes.

There's a lot left to do. An expandable to-do list in markdown is included in the .zip.

For more details see the [forum](https://www.treebard-forum.com/forum/the-treebard-philosophy/history-and-future-of-the-treebard-project) or the [video channel](https://www.youtube.com/@treebardgenealogysoftware2577).

There's now a [video page](https://treebard.com/video.html) at the website with playlists.

I'm currently more interested in making videos about Treebard and UNIGEDS than in writing more features for this as-is version of Treebard. For example, charts are covered by dedicated apps. Why should a working model of primary features bother with them? Reports might be better written by AI, or "artificial stupidity" as I prefer to call it.

## We Support Each Other

If you're trying to test what there is so far and want me to help you, post your question at the [informal forum](https://www.treebard.proboards.com) and I might help you merge with my work if I think we're close to being on the same page. If you want to donate, that can be done [here](https://treebard.com/donate.html). My email address is also available at [the website](https://treebard.com/about.html).

## Contributing is Allowable

I'm not actively looking for a team of coders right now but if such a team were looking for Treebard, I'd consider a team effort as long as I don't have to do anything but offer opinions and advice. After 6 years of doing this full-time+, I might be better advised to get out of this chair and into the garden, if I want to live long enough to get even older. Forking the project might be better for all concerned. (Starting in December 2022 the new commits have appeared only at treebard.com, and if you want old versions I'll have to dig them up out of my back yard.) There are no enforcable restrictions on what you do with the code, but I request that if you are not me, please don't use the name "Treebard" in your project's name without explicit written permission. I'm asking nicely. Remember, nice people go to heaven. 

### To ask questions, make suggestions, or request to join the team in any capacity:

* Go to [the Treebard forum](https://www.treebard.proboards.com)
* Join the forum-blog and read some of my many posts.
* Introduce yourself by answering these questions: 
  * How you heard about Treebard.
  * Why you're interested in the project.
  * What you like and don't like about the Treebard philosophy.
  * Your level of experience with...
    * genealogy
    * programming, Python, SQL, GUI, html/css/JavaScript, other.
* Post your question/suggestion/request in a new thread.
* Ignoring these instructions will get you ignored.

## Treebard's Kind of Genealogy

Genealogists of today are in two opposing camps: conclusion-based genealogy programs let the user decide what happened way back when, and allow sourcing but don't require it. (And usually make it prohibitively tedious to go to the trouble, so many users don't bother.) On the other side of the fence is evidence-based genieware. The creators of this genre of genieware try to solve the problem of users who don't get around to entering sources by encouraging you or forcing you to enter sources first. I once wanted to do it this way so bad that I was forced to take a look at my motivations. What finally convinced me to stop enforcing sourcing was when a Mr. Tamura Jones said something on his website to the effect that genealogists might actually _want or need_ to put their details into their database one factoid at a time. I got to thinking about this and had to admit that I wanted to do it my way too, which might be a different way on a different day. Instead of being forced to input data according to someone else's mindset being built into enforcementware.

I love to input sources but one of my goals has been to make it super easy to do, without all the copying and pasting of citations currently required by Brand X.

My other goal is to create a compromise between the two opposing camps with this slogan: "Evidence--Assertion--Conclusion." In Treebard, **assertions** have to be backed up with sources, **conclusions** can be linked to assertions *optionally*, and the assertions are never merged with the conclusions they support. So for example on the person tab you'll see a table of conclusions about the current person's events and attributes. Each event table row includes a SOURCES button that says how many assertions back up that finding. Zero sources is OK, because it takes all kinds to make McGenealogy.com filthy rich, or the sources can be filled in later. But in Treebard, the zero is explicitly noted right on the SOURCES button. Clicking the button shows the sources linked to the event, attribute or name by opening the dialog where assertions and sources can be created, modified, and linked to conclusions. Since the assertions feature is unique to Treebard, I recorded myself creating the first version of this feature, resulting in a documented effort displayed in a series of 204 videos that used to be available on Rumble.com. For anyone who's not a programmer but is thinking about learning just enough programming to write their own genieware, the videos on my [YouTube channel](https://www.youtube.com/@treebardgenealogysoftware2577) will give you a look at how that's been working out for me.

The idea is to provide an alternative to typical conclusion-based genieware which is a spaghetti interface of bad _feng shui_ with no focus on sources unless you can find it somehow... vs. typical evidence-based genieware which has to allow sourceless input anyway if it's ever gonna be popular. My idea is to start out with a formal and permanent separation of assertions and conclusions and keep them separate. (For example, this will keep the user from recording more than one birth event for a person in a well-meant attempt to track all the evidence. In Treebard, sources do not form conclusions. The user does that.) 

The two backbones of the Treebard philosophy are 1) a _friendly and intuitive user interface_; good software should make it look easy to do complicated things. And 2) a _data storage structure_ that's simple and straightforward, yet detailed enough that any and all genealogy software developers could end up adopting something like it someday. This could enable the retiring of GEDCOM from a job it's clearly not able to do well.
