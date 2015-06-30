PRIO 3
# Pagination

> Use rel=”next” and rel=”prev” if you paginate content over multiple pages.

Description:
-
Place the next and prev tags in the <head> section of your pages to indicate relationships between individual URLs.
Code Examples:
-
If the entire website should be accessible to search engines, state the following in the robots.txt-File. :

    <link rel="next" href="https://example.com/article?pg=2">

Place this on the second page https://example.com/article?pg=2

    <link rel="prev" href="https://example.com/article">
    <link rel="next" href="https://example.com/article?pg=3">

Place this on the last page - https://example.com/article?pg=3  

    <link rel="prev" href="https://example.com/article?pg=2">

Sources and Guidelines:
-
 - http://googlewebmastercentral.blogspot.ch/2011/09/pagination-with-relnext-and-relprev.html
 - https://support.google.com/webmasters/answer/1663744?hl=en
