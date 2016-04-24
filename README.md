<h1>Natural Language Classifier for Fact or Opinion
Created by: Diana Yau</h1>

My Bluemix link is found here: http://natural-language-classifier-demo-diana.mybluemix.net/

The IBM Watson Classifier is a service provided through an API that is trained to categorize objects. Here we are classifying a statement to be a fact or an opinion. A fact is a piece of information that can be strictly defined and proved true. An opinion is a statement that expresses a belief, value, or feeling. 

<b>Steps to adapting a new classifier:</b>
<ul style="list-style-type:disc">
<li>Compiling a .csv file of fact and opinion statements</li>
<li>Training the classifier through a command line interface</li>
<li>After it is trained, the status of the classifier will be set to "Available", allowing one to be able to make requests to the classifier</li>
<li>Setting the environment variable of the classifier to the ID that is found</li>
<li>Restaging the application to ensure the environment variable is set</li>
</ul> 

After the classifier is set, we are able to input a statement to test whether it is a fact or an opinion.
The natural language classifier uses machine learning algorithms to identify here whether the declaration relates arguments socially, especially the media. 

Furthermore, the natural language classifer will make predictions about how to handle new declarations it has never encountered with before. It can also be used for labelling blocks of text.

Most of the files were provided by IBM's Watson Developer Cloud Github page at https://github.com/watson-developer-cloud/natural-language-classifier-nodejs

Thank you!
