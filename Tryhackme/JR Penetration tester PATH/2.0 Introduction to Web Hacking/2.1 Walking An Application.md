viewing a web page's source code
the page source is the human-readable code returned by the server to the browser when a request is made. it consists of html, css and javascript, defining the content, styling, and interactivity of the page.

how to view the page source:
* right-click on the page and select "view page source"
* in some browsers, you can add view-source: before the URL.
* you can also access it through the developer tools

what to find in the source code:
- comments: these start with <!-- and end with -->. developers use comments to leave notes or explanations in the code.
- links: links are written using the <a> tag, and the destination is stored in the href attribute.
- hidden links: sometimes, there are hidden links (e.g., starting with "secr") that lead to private areas or secrets of the site.
 - external files: the code may include links to css, javascript, or image files. if the directory of these files is accessible publicy, it may expose confidential or backup files (e.g., flag.txt).

- frameworks and versions:
- many websites use frameworks, whice are collections of pre-written code to simplify development.
-  by viewing the source code, you can identify whice framework and version are in use. is the framework is outdated, there may be vulnerabilities that can be exploited to find flags or sensitive information.
