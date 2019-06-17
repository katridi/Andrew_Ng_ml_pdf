# [Andrew Ng Machine Learning](https://www.coursera.org/learn/machine-learning/home/welcome)

downloaded via __[coursera-dl](https://github.com/coursera-dl/coursera-dl)__

> $ pip install coursera-dl

> $ __course_name__ coursera-dl -u __youremail__ -p __yourcourserapassword__ -f "pdf" --path=__here/is/path/to_folder__ __course_name__
  
to extract all pdfs from all folders recursively
> $ find __here/is/path/to_folder__ -iname "*.pdf" -exec mv {} __here/is/path/to_folder__ \;

delete all empty folders
> $ find __here/is/path/to_folder__ -type d -empty -delete
