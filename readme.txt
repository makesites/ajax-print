##############################################################

AJAX Print v1.0

Created by: Makis Tracend (makis@makesites.cc)
URL: http://www.makesites.cc/author/makis/

##############################################################


Description
===========

A simple script to print a remote page with one click. 


Instructions
============
All the AJAX "magic" is dependent on loading the contents of the remote page in an invisible div and defining a different style sheet for printing than the one used for the screen representation.
  
- Create a div with a unique id and place just before the </body> tag (outside any other nested code you have in your web page). This will be the print container, where the remote page will be loaded before printing. Let's call it 'printcontainer' for now.

- Define a "screen" and "print" stylesheet in your page, with the "screen" stylesheet defining the printing container as "display: none;" and the print stylesheet defining the outmost container of your webpage as "display: none;" 

- Include the javaScript in your web pages
 
- Create links to print remote pages like this: <a href="{URL}" onClick="printPage(this, '{PRINT CONTAINER ID}'); return false;">, where: 
  * {URL} is the URL of the remote page you want to print
  * {PRINT CONTAINER ID} is the id of the div you have created as a printing container. 
  

For additional help, open up example.html and read throught the simple code. 

Noting that this script will only work for pages under the same domain...


Changelog
=========

14-02-2008 	(v1.0) 	Initial release: Printing of a remote page with no special formating. 


Copyright
=========

This work is released under the terms of the GNU General Public License:
http://www.gnu.org/licenses/gpl-2.0.txt
