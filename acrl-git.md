Git and You: An Introduction To Modern Version Control That Will Quite Possibly Leave You Feeling More Confused Than When You Started
==========


What if I told you there was something very much like Dropbox but had a difficult learning curve? Something that, rather than being easy to install and use, actually required a not-insignificant time investment to learn? And that rather than operating automatically, required you to execute a number of steps *beyond* hitting save in Word? Would you ask me why I'm telling you about this?

Writing software is hard business -- don't believe anyone who puts forward the front that they can birth fully-functioning code apropos of nothing. Programming is *iterative*; you write something, you test it, it breaks, you fix it, you write some more, it breaks something else. And it's a common scenario to have a bug arise in your code that you wrote ages ago -- sometimes years -- and you need to go back to how your code looked at a specific point in time to fix it. Common also is adding features to already mature code -- features that may break existing functionality, features that need some working out to actually function, and you want to keep them separate from what's already working.

Enter version control. In programming, a *version control system* is a program that, at a very basic level, records the state of a project and has some functionality to view past states, commonly called a *repository* Modern version control systems have the ability to incorporate changes to that state from multiple contributors, keep all revisions of a project indefinitely, have as many backups as the project as there are people with copies of the repository, and make it easy to collaborate with others. For simple projects it might be overkill, but when you're dealing with million-line codebases with hundreds to thousands of contributors, a system that keeps track of who did what when makes administration of a project not easier, but *possible*. 

<brief git (or scm?) history here>

 If you're a serious Dropbox wonk, you've probably noticed that Dropbox keeps the last ten or so saves of each file -- handy if you nuke something and need to go back to an earlier revision. But if you're a compulsive saver, you'll quickly run out of those last ten revisions. 

