# Sentiment Analysis of Citizen on Twitter in Accessibility of Disabilities at The Public Space Using Support Vector Machine (SVM) Method with Radial Basis Function (RBF) Kernel

In the process, the SVM method has kernels trick where kernel functions are used to operate on a dimensional feature space that cannot be separated linearly. In general, problems in the real world are rarely linear. RBF (Radial Basis Function) kernel is a good first choice for model building.\
The RBF kernel non-linearly maps samples to a higher dimensional space so that it can handle non-linear cases. The RBF kernel has several parameters in its process (C,γ), but we don't know how much the C and γ. I use GridSearch to find the best number of C and γ for my dataset.

## How to Use

- If you want use my dataset, you can skip the `source_code/Crawling.ipynb`. But if you want use another dataset from Twitter, you can use `source_code/Crawling.ipynb` with your API key from Twitter Developer.
- all my data is in `data` folder.
- from Pre-Processing to Classification is in `source_code/Analisis_sentimen.ipynb`.
- I use Indonesia Sentiment Lexicon that you can download the files from fajri91 on github at References below, then you can edit the files as you need.

## References

- https://link.springer.com/book/10.1007/978-1-4842-4354-1
- https://ejournal3.undip.ac.id/index.php/gaussian/article/view/28932
- https://github.com/fajri91/InSet

\
**Hope that is usefull**\
Regards,\
Mitha Rachma Putri
