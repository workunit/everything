[RID01      I     PRIO 1
Robots.txt
=
> A robots.txt file must be accessible in the root folder.

A change here.

Description:
-
The robots.txt file must be available at www.yoursite.com/robots.txt. 
Code Examples:
-
If the entire website should be accessible to search engines, state the following in the robots.txt-File. : 

    User-agent: *

or

    User-agent: *
    Disallow: 

or

    User-agent: *
    Allow: /

Block specific pages or subdirectories for search engines by stating: 

    Disallow: /blocked-page-or-directory 

Make sure that you do not explicitly block resources such as JavaScript and CSS for search engines.

Sources and Guidelines:
-
* Find further robots.txt guidelines and instructions here: https://support.google.com/webmasters/answer/6062608?hl=en 
* We recommend to install Google Webmaster Tools and use the robots testing tool: https://www.google.com/webmasters/tools/robots-testing-tool

