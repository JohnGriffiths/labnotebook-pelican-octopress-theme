
Lab Notebook (modified) Pelican Octopress Theme
===============================================

This is a fork of the pelican-octopress-theme, 
modified for my digital lab notebook, which is 
built as a static html website using pelican.

The principal modifications are some changes 
to the template files that enable password-encrypted
content, using the [pelican-encrypt-content plugin](https://github.com/mindcruzer/pelican-encrypt-content.git). I then add this 
repo as a submodule in the 'themes' folder of the 
LabNotebook repository. Note that further 
modifications are required in the actual main folder 
of the pelican site to get everything working; 
the modifications here simply take care of the changes 
required in the site theme folder. See the encrypt-content 
repo documentation for more on this. 


If you want to use the pelican-octopress-theme 
without these modifications, see the [original github repo](https://github.com/duilio/pelican-octopress-theme.git).


Modifications
-------------

The modifications made should be clearly identifiable from the 
commit history of this repo and the comments therein. For 
maximum transparency, I will also list them here: 

1. Replace the line X with X
2. Replace the line X with X
3. Copy the static/scripts folder from the pelican-encrypt-content repo
4. Copy the templates/encrypt-content folder from the pelican-encrypt content repo







