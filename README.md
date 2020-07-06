# Classifying Medical vs Alternative Medical Research Papers Using Machine Learning.ipynb

In the age of social media, discriminating between facts, fiction and 'fake-news' has become increasingly difficult. Concerningly, misinformation regarding what
constitutes sound medical advice has been proliferating through social media. In this project, I attempted to utilize machine learning to determine whether on a 
fudnamental level, scienctific writing could be distinguished from pseudoscientific writing. To this end, I utilized web-scraping to download over 1600 titles and 
abstracts from scientific and pseudoscientific journals. I then used various classification algorithms to predict which class (science or pseudoscience) belonged to
using either the title or the abstract as input data. Using abstracts as data resulted in an average accuracy (averaged over all classification algorithms) of 93.8%,
with the highest accuracy obtained of 96% using artifical neural networks. Interestingly, using titles resulted in a significantly lower average and highest 
accuracy of 84.9% and 90% respectively. This project shows not only that science and pseudoscience can be differentiated by machine learning on a fundamental level,
but that utilizing a smaller feature set such as titles might not perform as well as a larger feature set such as abstracts.

This project was completed as my final project required by the Brainstation Data Science course. 
