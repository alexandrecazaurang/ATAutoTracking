# ATAutoTracking
Short script to automatically get your basic tagging info (page, chapters, s2, clicks names, types and position)
PageTag allows page, chapters and level 2 site detection based on URL structure and content and generates page hits.
LinkTagging adds click names, types, position and level 2 sites to dedicated attributes in links.
GTMClickInit generates clicks hits based on the PageTag and LinkTagging scripts.

In Google Tag Manager PageTag and LinkTagging tags can be fired from a trigger based on DOM ready or a pageview.
On the other hand GTMClickInit has to be fired from a trigger based on the clickedLinks criteria.

