# Appendix B: Statistical Trends in the Fetchmail Project’s Growth

The scattergram below was made with Gnuplot 3.7 from data pulled directly out of the fetchmail project NEWS file using two custom shellscripts available on the project website.

The graph shows the population growth of the fetchmail project.

The horizontal scale is days since baseline, which is when I started collecting statistics in October 1996 at version 1.9.0. Left vertical scale is number of participants. There is one data point for each release; therefore, the changes in density of marks indicate release frequency.

The peak in the earliest part of the graph (before the note “Bad addresses dropped”) seems to be an artifact; I was not regularly dropping addresses that became invalid at the time. Turnover on the list seems to be about 5% per month (but that’s just my estimate, I don’t have numbers on this).

The scatter of squares is total participants. The scatter of crosses is the count of people on fetchmail-friends after I split the list. The scatter of triangles is the population of fetchmail-announce after the split.

The scatter of diamonds tracks project size in lines of code (right vertical axis). The scale relationship between this scatter and the other three is arbitrary.

This graph is quite revealing. Several trends stand out:

- Over time, the project population displays rather consistent

linear growth.

- The key event in the project’s lifetime was release 4.3.0 in

October 1997, when I declared the code to be out of development and in maintainance mode, and split the fetchmail list.

- The run-up to 4.3.0 saw the most intensive spate of releases in

the project’s history (the gap in that run happened when I took a two-week vacation). It was followed by a significant slowdown.

- After 4.3.0, the developer population remained fairly stable

around an average of about 250 participants.

- Essentially all population growth after 4.3.0 happened on the

announce list, among people using fetchmail but not active co-developers.

- The growth trend in code size looks sublinear, perhaps logarithmic.

The linear growth trend in population is particularly interesting; a priori we might expect geometric or logistic growth, given that the project spreads by word of mouth.

It has been suggested that the linear growth rate is the result of a situation in which both number of projects and the population of eligible programmers are rising on trend curves of the same (probably exponential) rate.

There are some web pages doing similar things:

- http://kitenet.net/programs/debhelper/stats/ contains growth

statistics on the debhelper packaging utility.

- http://durak.org:81/sean/pubs/kfc/ is a page on the vocabulary

of the Linux kernel.
