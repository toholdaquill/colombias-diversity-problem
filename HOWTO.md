HOWTO
=====

Grab yourself a copy of colombias-diversity-problem.html. This is the master
file. Then download Calibre:

    http://calibre-ebook.com/download
  
Run:

    ebook-convert colombias-diversity-problem.html colombias-diversity-problem.epub \
    --cover colombias-diversity-problem-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Colombia's Diversity Problem: a Speech on Tourism" \
    --title-sort "Colombia's Diversity Problem: a Speech on Tourism" \
    --preserve-cover-aspect-ratio
  
or if you're a Kindle user:

    ebook-convert colombias-diversity-problem.html colombias-diversity-problem.mobi \
    --cover colombias-diversity-problem-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Colombia's Diversity Problem: a Speech on Tourism" \
    --title-sort "Colombia's Diversity Problem: a Speech on Tourism" \
    --prefer-author-sort

or if you just want a PDF:

    ebook-convert colombias-diversity-problem.html colombias-diversity-problem.pdf \
    --cover colombias-diversity-problem-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Colombia's Diversity Problem: a Speech on Tourism" \
    --title-sort "Colombia's Diversity Problem: a Speech on Tourism" \
    --paper-size a4 \
    --pdf-add-toc \
    --pdf-page-numbers \
    --preserve-cover-aspect-ratio \
    --margin-bottom 72 \
    --margin-top 72 \
    --margin-left 72 \
    --margin-right 72
    
Calibre's full command-line interface is documented here:

    http://manual.calibre-ebook.com/cli/ebook-convert.html
