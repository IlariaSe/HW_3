# Group34
## Homework 3 - Find the perfect place to stay in Texas!
![alt text](https://github.com/IlariaSe/HW_3/blob/master/airbnb.jpg)
## What you will find in our repository:
1) **Homework_3.ipynb**: a tidy Notebook where we put the code and the comments of our pipeline;
2) **Map.ipynb**: a notebook that contains the code to make the map;
3) **Map**: this is the map ! (We have inserted the *html file* in README) http://nbviewer.jupyter.org/github/IlariaSe/HW_3/blob/master/Map.html
...We noticed that several points are hard to see since they can be very close to each other, for this reason, we created *marker clusters*: the marker clusers group points that overlap and then it labels the resulting cirlce with the number of points in that area. If you click on the circle, the map zooms to the area to show you the individual points.
...We also create a popup tooltip to provide the average_rate_per_night and if you click on the price you can go directly to the site of the house;
4) **A folder named *File* with inside**: 
..* `'listwords.txt'`: list of our words obtained after preprocessing the documents;
..* `'vocabulary.txt'`: this file shows the id associated with each word.
..* `'inverted.json'`: it contains the inverted index --> *invertedIndex = {termID : doc}*
