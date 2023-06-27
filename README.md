# Text2Chart-A-Machine-learning-model.

This project presents the development and evaluation of Text2Chart, a machine learning model
designed for converting textual descriptions to graph charts using a multiclass classification approach. 
The project followed a systematic workflow, including data collection, model building, graph type prediction and graph generation.
In this we compared the performance of four different classification models: Random Forest Classifier, Multinomial
Naive Bayes, Linear SVM, and Logistic Regression. The dataset used for training and
evaluation consisted of textual descriptions with corresponding chart types. 
Through extensive experimentation and evaluation, it was determined that the Linear SVM model achieved the
highest accuracy of 78 percent among the tested models. 
Consequently, Linear SVM was chosen as the algorithm for training the Text2Chart model to predict chart types, including bar
chart, line chart, pie chart, and box plot. The project also involved the development of a graph generation component. 
In this phase, common patterns in the input sentences were identified to facilitate the generation of the appropriate chart types. 
The project also incorporated the utilization of spacy, a natural language processing (NLP) model, along with relevant functions
to enhance the accuracy and effectiveness of the graph generation phase. 
The graph generation aspect, along with the proper labelling of the generated graphs, has been identified as a
potential avenue for further research and development. 
This project lays the foundation for future enhancements and expansion of Text2Chart, allowing for more accurate and efficient
chart type prediction and graph generation based on textual inputs. 
