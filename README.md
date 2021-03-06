PSU-GEOSC-thesis-template
=========================

This is the repository for a TeX template specific to theses out of the Geosciences Department at Penn State. It is based on the work of other grad students in other departments across nearly two decades of academia. I have just polished the hubcaps. 



----------------------



Welcome to the newly-updated TeX template for Geosciences theses. In this folder, you'll find a minimum working example (thesis_template.tex) and its output (thesis_template.pdf). This template is  currently in the one-sided configuration appropriate for theses. For a format more suitable for books, you'll need to change the \documentclass[11pt]{psuthesis} to \documentclass[11pt]{psuthesis2side} and recompile. The psuthesis2side class should be essentially identical to the psuthesis class, but be warned -- the two-sided configuration will not pass format review!

The included *.sty files (doublespace, etoolbox) are necessary for formatting (in the first case) and the toggle between Masters and Doctorate degrees (the latter). I have put both the Masters thesis (2013) and PhD dissertation (2017) template through format review, so it should be good to go. 

To toggle between degrees (not so easy in real life): comment and uncomment the relevant \toggletrue and \togglefalse, just beneath \major and \dept declarations in thesis_template.tex. It will handle the relevant wording (on two pages) and whether to display the Vita (optional with the Masters -- you'll have to go in and change it if you want it to show up in a Masters). There are two examples of this toggle in action, reflecting a Masters thesis (thesis_template_Masters.pdf) and a PhD dissertation (thesis_template_PhD.pdf).

The signature page is omitted (not necessary for format review), but is up on the Dept. of Graduate Studies web page. 

In addition to the LaTeX template, I've included (from http://www.sas.psu.edu/penn-state-thesis-template/) a Word 2011 template, for those who would rather not learn TeX at the end of all things. Other formats are available at the link above.

Best of luck, and please let me know if there are future updates needed!
