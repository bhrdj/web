# web
my web presents  
*(my presence 4U!)*

----

This repo houses generating scripts and links-to-content for my personal/professional website.
- Domain will be bhrdwj.net:
    - bhrdwj.com and bhrdwj.org will also point to bhrdwj.net
- Generator framework will be:
    - modeled after [pelican](getpelican.com), but extra simplified
    - basically generator will just insert headers and footers:
        - headers so that pages link to home, toc, and maybe a few others
        - highlighting of the current page title among the header links
        - footers with some snarky comment
    - The entire site will be just
        - a splashy generated intro page linking to:
            - resume
            - featured project
            - portfolio TOC
        - a generated table of contents (TOC)
        - portfolio content pages
            - an html resume
            - github readme markdown files
            - jupyter notebook html files
        - all with the added headers and footers
    - content and generated files (/content and /docs) are .gitignore'd
        - rely on a pagemaking notebook to pull other repos' html etc into content
