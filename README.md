# Treebard GPS

A showcase for genealogy software functionalities written in Python 3.11, Tkinter and SQLite. Being tested in Windows only at this point, but Tkinter is supposed to be cross-platform. Treebard has been a full-time project for a hobby-level coder working alone since July 2018. Its main purposes are 1) to prove that a genealogist can write his own app, and 2) to provide a model code base that can be imitated, stolen, borrowed, or otherwise used without permission, participation, or acknowledgement from me, the creator of Treebard, for any legal purpose, from here to eternity. (Donations will somehow manage to be accepted.) I am particularly fond of the idea that someone will see the light about continuing to limp along with GEDCOM, and instead *just start using* Treebard's database structure (UNIGEDS) or be inspired by it, to give birth to a Universal Genealogy Data Structure which would replace GEDCOM if app developers could be inspired enough to all use the same data storage structure for their app's primary features.

## How to Use this Repo

This project is alive and well and living at treebard.com. Go there to get the most recent version. This repo used to be here as an example for github-centric seekers to find, but as a team of one I have my own version control, so the former repo "Treebard GPS" and its 314 commits were deleted. Work on the project is actively ongoing in 2024. See the blog for more details.

The only requirement to try out Treebard's currently existing features is a recent version of Python and pip install Pillow for graphics. The Pillow install has worked effortlessly for me with no other dependencies in spite of what the Pillow docs say, as long as I used Python 3.8 or better. To grow your own version of Treebard-like abilities based on my code, you'll also need to install the SQLite terminal tool. All of this is very easy.

To get your copy of the repo to function, copy and paste [all the code at the repo](https://treebard.proboards.com/) into the directories that the repo instructs. Currently (January 2024) there is one functioning family tree database that you can play with, or you can start your own from scratch.

## News

Chapter Two of Treebard development has been nearly finished for maybe about a year. Rudimentary but very excellent GEDCOM import and export programs are in the trouble-shooting/finishable stage. I plan to finish those trouble-shooting projects as well as the places tab in the GUI before I slow down and diversify my energies (i.e. get out of this chair.) This goal has been approached many times but always interrupted by fresh enthusiasm for rewriting this or that to make them better. The current interruption is a do-over of the events table to use autofill tkinter.Text widgets instead of multi-line tk.Labels with autofill tk.Entry overlays. I am proud of my work and I feel that I have already done a good job of raising the bar for genealogy software, even though the app is not intended to be finished, but rather to serve as a basis for projects that could be finished by larger and younger teams. Starting in 2024 I plan to post the code regularly since waiting for Chapter 2 of Treebard Development to get done is too long for anyone to wait, and many deep changes have been made since the code was last posted in 2022.

## Limitations

I have not tested any of this code on Linux or MacOS. This is not version 0 or 1. The GPS version will never have backward compatibility, everything is subject to change drastically without notice. The GPS version is a showcase and testbed for genealogy software functionalities, written in Python. If you use it to create a family tree, it will be a lot of work to keep the code up to date as changes are made. A better use of your time would be to create Treebard v. 0.0.0 or its equivalent, and keep that version backwardsly compatible. Python is slower than the compiled languages but the Gramps project doesn't seem to be having a problem with a huge genieware written in Python.

## Treebard is for Everybody

Every version of Treebard that ever exists is supposed to be portable, free and open-source, but I have no control over that, it's just my personal preference. The code is officially unlicensed (public domain). So you can do what you want with it, use it to create a product for sale, and you can do all this without permission or paying royalties. Donations are accepted and would be appreciated. Until there is an .exe, Python still has to be installed but that's so easy a monkey could do it blindfolded.

## No Installation

Tkinter and SQLite come packaged with Python so if your Windows is in good shape, then there should be no installation or dependency problems to run Treebard, except to install Python and pip install one dependency called Pillow. Without a recent version of Python (3.8 or better), good luck getting Pillow installed unless you're a professional programmer. Without Pillow, nothing will work unless you want to downgrade to using .gif images only and rewrite all the code involving images. Tkinter will handle .gif images without Pillow but this was not a good experience for me.

Installing the SQLite console is necessary only if you plan to write your own version. The databases can be downloaded from the repo.

To run Treebard, just run the .py file that has `root` in its name and everything else should work to whatever degree it is currently functioning. If you don't know how to run a Python file, try double clicking the .py file with `root` in the name, where it's listed in your file manager. If that doesn't work, you might have forgotten to check the "...Path..." box when installing Python.

## Roadmap to Infinity and Beyond

This project is 5-1/2 years old in January 2024. The GPS version is a Python program so it might run too slow for big databases. (But Gramps runs on Python and I think they'd disagree that Python is too slow.) Treebard GPS' purpose is to demonstrate how things could/should/might work in a genealogy database GUI, so the main point is user experience and attention to detail when it comes to storing data in a useful way for real genealogists who care about details, sources, and the like, *as well as* a pleasant, congenial, intuitive user experience.

Treebard works for even the most casual users because it's easy to use, intuitive, and doesn't force you to do things in a contrived way requiring lists of instructions. Many first-time users will be able to use it without glancing at any docs. There is/will be a detailed right-click context-sensitive help menu as well as unobtrusive tooltips that display in the statusbar.

Treebard Version 0 could be written in Electron's replacement when it shows up, JavaScript, SQLite, HTML and CSS. If you want to use more advanced programming languages, just fork it and let me know how it goes. I'm getting older every day and going from Python to a compiled language would be a big jump for an old geezer who's going blind. The disadvantage to using Electron is the spread of monoculture since Electron is based on google's Chromium like so many other projects. Other applications which use Electron include the open-source editors VS Code and Atom. Both of which are now owned by Microsoft. Like Github. (Rant on "monoculture" omitted.)

GPS stands for _Genieware Pattern Simulation_. It originally stood for _genealogy programming source-first_ but I eventually realized that users won't be told how or when to enter their sources, so flexibility is my new dogma. Make it work for everybody, make it portable, make it public domain. My silliest fantasy is a genealogy program that becomes more ubiquitous than GEDCOM. I know, it will never happen. But the slogan would be, "Don't share a GEDCOM file... share the whole program!" So Treebard has to be portable because I'm a dreamer and because I believe that steep learning curves are an excuse for writing apps without considering the needs of the average user. Apps with a forbidding appearance and a steep learning curve are geekware written for geeks. Nothing wrong with that, but genealogy is a hobby for most and for this reason I've tried to keep the GUI beautiful and simple-looking while making it able to manipulate complex data behind the scenes.

There's a lot left to do. For example, someday I'll use my domain **treebard.com** to publish a manual and tutorial.

For more details see the [forum](https://www.treebard-forum.com/forum/the-treebard-philosophy/history-and-future-of-the-treebard-project) or the [video channel](https://www.youtube.com/@treebardgenealogysoftware2577) which I plan to bring up to date in January 2024 or the [old video channel](https://rumble.com/c/c-1673045).

There's now a [video page](https://treebard.com/video.html) at the website with playlists, which should also be brought up to date in January 2024.

## We Support Each Other

If you're trying to test what there is so far and want me to support you, post your question at the [informal forum](https://www.treebard.proboards.com) and I'll see what I can do. Same goes if you just want to give me some advice. (But don't tell me to give up...) If you want to donate, join the forum and send me a personal message. My email address is also available at [the website](https://treebard.com/about.html).

## Contributing is Allowable

I'm not actively looking for a team of coders right now but if such a team were looking for Treebard, I'd consider a team effort as long as I don't have to do anything but offer opinions and advice. After more than 5-1/2 years of doing this full-time+, I might be better advised to get out of this chair and into the garden, if I want to live long enough to even older. Forking the project might be better for all concerned. (Starting in December 2022 the new commits will appear only at treebard.com, and if you want old versions you'll have to beg for them.) There are no enforcable restrictions on what you do with the code, but I request that if your philosophy diverges significantly from mine, please don't use the name "Treebard" in your fork's name.

### To ask questions, make suggestions, or request to join the team in any capacity:

* Go to [the Treebard forum](https://www.treebard.proboards.com)
* Join the forum and read some of my rants.
* Introduce yourself by answering these questions: 
  * How you heard about Treebard.
  * Why you're interested in the project.
  * What you like and don't like about the Treebard philosophy.
  * Your level of experience with...
    * genealogy
    * programming, Python, SQL, GUI, html/css/JavaScript, other.
* Post your question/suggestion/request in a new thread.

## Treebard's Kind of Genealogy

Genealogists of today are in two opposing camps: conclusion-based genealogy programs let the user decide what happened way back when, and allow sourcing but don't require it. (And usually make it prohibitively tedious to go to the trouble, so many users don't bother.) On the other side of the fence is evidence-based genieware. The creators of this genre of genieware try to solve the problem of users who don't get around to entering sources by encouraging you or forcing you to enter sources first. I once wanted to do it this way so bad that I was forced to take a look at my motivations. What finally convinced me to stop enforcing sourcing was when a Mr. Tamura Jones said something in a blog post to the effect that genealogists might actually _want or need_ to put their details into their database one factoid at a time. I got to thinking about this and had to admit that I wanted to do it my way too, which might be a different way on a different day. Instead of being forced to input data according to someone else's mindset being built into enforcementware.

I love to input sources but one of my goals will be to make it super easy to do, without all the copying and pasting of citations currently required by Brand X.

My other goal is to create a compromise between the two opposing camps with this slogan: "Evidence--Assertion--Conclusion." In Treebard, **assertions** have to be backed up with sources, **conclusions** can be linked to assertions *optionally*, and the assertions are never merged with the conclusions they support. So for example on the person tab you'll see a table of conclusions about the current person's events and attributes. Each "finding" or row of conclusions includes a SOURCES button that says how many assertions back up that finding. Zero sources is OK, because it takes all kinds, or the sources can be filled in later. But in Treebard, the zero is explicit. Clicking the button shows the sources linked to the event, attribute or name by opening the dialog where assertions and sources can be created, modified, and linked to conclusions. Since the assertions feature is unique to Treebard, I recorded myself creating the first version of this feature, resulting in a documented effort displayed in a series of 204 videos that's only on Rumble.com. For anyone who's not a programmer but is thinking about learning just enough programming to write their own genieware, this series will give you a good look at how that's working out for me.

The idea is to provide an alternative to typical conclusion-based genieware which is a spaghetti interface of bad _feng shui_ with no focus on sources unless you can find it somehow... vs. typical evidence-based genieware which has to allow sourceless input anyway if it's ever gonna be popular. My idea is to start out with a formal and permanent separation of assertions and conclusions and keep them separate. (For example, this will keep the user from recording more than one birth event for a person in a well-meant attempt to track all the evidence. In Treebard, sources do not form conclusions. The user does that.) 

The two backbones of the Treebard philosophy are 1) a _friendly and intuitive user interface_; good software should make it look easy to do complicated things. And 2) a _data storage structure_ that's simple and straightforward, yet detailed enough that any and all genealogy software developers could end up adopting something like it someday. This could enable the retiring of GEDCOM from a job it's clearly not able to do well. 
