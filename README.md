# image-content-search-engine 
CS242- Information Retrieval and Web Search Project 
done by: Karthik Harpanahalli, Varun Sapre, Hoora Sobhani, Sarthak Jain, Ameya Padole

We designed and developed an image search engine using Hadoop Inverted Indexes and Lucene indexing which returns the images pertaining to the input query by the user. We employ FiftyOne API - an object detection software - to detect objects in an image and use the indexed objects called annotations to match with the query. These images are ranked for relevancy using the area of bounding boxes of each annotation and then returned to the frontend to be displayed on the browser.