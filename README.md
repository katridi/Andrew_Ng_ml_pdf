# [Andrew Ng Machine Learning](https://www.coursera.org/learn/machine-learning/home/welcome)

downloaded via coursera-dl 

> $ coursera-dl -u <youremail@whatever.com> -p <yourcourserapassword> -f "pdf" --path=here/is/path/to_folder --clear-cache machine-learning
  
to extract all pdfs from all folders recursively
> $ find . -iname "*.pdf" -exec mv {} ~/Desktop/machine-learning/ \;

delete all empty folders
> $ find . -type d -empty -delete
