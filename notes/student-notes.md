This file contains basic notes for students, links to resources etc. 

# To Do

## Preliminaries

Here are the things each student needs to do to prepare and familiarize with the tools we need before we can make progress.
(If you need help, try posting to slack.)

* Join the slack team (send me an email with your preferred email, and I will send you an invitation)
	* Post a message to the #random channel of slack telling us your favourite film

* Get aquainted with the basic goal of a Dynamic Statistical Comparison
	* Read my [blog posts](http://stephens999.github.io/blog/) - October 1, October 2, and November 17.  


* Organize github and git
	* Sign up for an account on [github](http://www.github.com). You may want to ask for a [student discount](http://education.github.com) where you can get free accounts that also include private repos (usually you have to pay for private repos). 
		* Post your github user id on the "github" channel of slack

	* Install [git](http://git-scm.com) on your laptop/computer.
		* Read Chapter 1 (and perhaps more!) of [The Pro Git book](http://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).	

	* Read Karl Broman's [guide to git/github](http://kbroman.org/github_tutorial/)
	* Fork the [test repo](http://github.com/stephens999/test). Add a directory to this repo with your username, and send me a pull request.
	
 
* Organize R and Rstudio
	* Install [Rstudio](http://www.rstudio.com) on your laptop/computer.
	* Install the ``knitr`` package in R.
	* Read Karl Broman's [knitr in a nutshell](http://kbroman.org/knitr_knutshell/)
 	* Use knitr to produce a report

* Organize 'make'
	* make sure you have a working version of 'make' on your computer. This should come standard with linux. With mac you will need to install xtools. 
See the second answer [here](http://stackoverflow.com/questions/6767481/where-can-i-find-make-program-for-mac-os-x-lion). With Windows I don't know what the easiest approach is.  


* Organize the 'dscr' package
	* Install the [dscr package](https://github.com/stephens999/dscr) in R.
	* Run the vignette and make sure it works.

## Next Step - the first DSC

Now I hope we are ready to try to use the dscr package to run our own DSC. My plan here is to focus on the simulation study in Section 5 of the
Elastic Net paper by
[Zou and Hastie](http://web.stanford.edu/~hastie/Papers/B67.2%20%282005%29%20301-320%20Zou%20&%20Hastie.pdf).

* Key question: should we do one DSC between us and work together? Or do one each and then compare how we did it?
* If we work together, one group could put together the datamaker function and scenarios; another could put together the methods?
* A key thing will be to keep track of problems that we have. Open an issue in the dscr repo with any problems that you come across.
Give enough details that someone could reproduce the problem. Maybe you can even fix the problem (but document it first!). 
I anticipate that the main thing we might want to do at this stage is add checks to the dscr package
so that users can more easily diagnose problems.

## And then...

My tentative plan is that after we have one DSC working, we will look for other published comparisons that we could turn into a DSC. We might also
want to add other comparisons to the EN DSC beyond those in the original publication. 
