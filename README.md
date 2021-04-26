# capstone

Hello, and welcome to pH to Amino Acid!

The purpose of this project is to act as a web app that can find out amino acids from pKa values (that are calculated to find isoelectric points) and in addition also create titration curves based on user data and also preordained values. This will allow a user to essentially run an experiment based off randomized samples and create a titration curve that ideally will be able to identify possible amino acids in the sample.

In order to run this webpage statically - a user could download the current repo and be able to use the website off their local machines. However, the webpage will also be available through a web server on https://www.ph2aminoacid.com


Work Schedule:

Week 1:
- created AWS static website and tested Hello World command, and made tabs with the experiment copied and pasted in it to test (3 hours)
- got domain and HTTP set up (15 mins)
- I got reacclimated with Python, and read up on HTML/JS (2.5 hour)
- created dynamic server for AWS, going to try to break it next week (1 hour)

Week 2:
- Got information on all 20 amino acid and formed about 10 of their protonation charts (9 hours)
- worked on the backend pseudocode for the program to tell amino acids from just the pKas, will also add in an area to put how many buffer zones there are in the titration to help narrow down amino acid identification (2 hours)

Week 3:
- Completed 18/20 amino acid protonation structures and information (7 hours)
- wrote code for pkas (ie the simple version) (2 hours)

Week 4:
- Finished all protonation charts
- Tested isolated program for pKas, put together readme info


Week 5:
- Looked up search functions for websites and what I would need to incorporate into what I already had (2 hours)
- Worked on creating titration curves from preordained values on the page, found a pretty good API and source (Highcharts.com) that I think will help work (3 hours)
- Again contemplating how I want to incoporate values that the user has an excel file of... Problem is that there are so many different acid-base combinations to find an unknown amino acid in a sample that I may just have to focus on the one that my experiment did and branch out from there if my professor requests it (1 hour)
- Fixed weird banner styling and the tabs in the amino acid area acting up (4 hours)

Week 6:
- I got a basic chart up and running this week that can essentially take inputs and change based on them and not have a person have to refresh the page,yay (7 hours)
- Fixed a few more UI problems (ability to see words and lettering, headers, etc) (4 hours)
- Looked into how importing an excel sheet for the API I'm using would work (3 hours)

Week 7:
- worked out some of the variables for graph (x/y axis, and exporting/CSV) (4 hours)
- fixed some of the UI problems like shiffting pages(3 hours)
- fixed the search bar that wasn't running (4 hours)

Week 8
- I have done the plot and gotten that sorted for the most part (about 6ish hours)
- All the amino acids have been updated with more information

Week 9:
- decided against AWS and went with Hostinger, which worked great, set up website on there and it worked for the most part - has HTTPS and SSL certs, and its own domain
- fixed search function on webserver (2 hours)
- fixed images that were broken (30 mins)
- embedded Excel Sheet to increase completeness and usability since I could not get Highchart working, backend code is still present to show attempt (1 hour)
