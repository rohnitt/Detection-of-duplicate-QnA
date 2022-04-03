Question and Answering sites like Yahoo and Google Answers existed over a decade
however they failed to keep up the content value of their topics and answers due to a lot
of junk information posted; thus their user base declined. On the other hand, Quora is
an emerging site for the quality content, launched in 2009 and as of 2019, it is estimated
to have 300 million active users1. Quora has 400,000 unique topics and domain experts
as its user so that the users get the first-hand information from the experts in the field.
With the advancing repository of the knowledge base, there is a need for Quora to
preserve the belief of the users, maintain the content quality, by discarding the junk,
duplicate and insincere information. Quora has successfully prevail over this challenge
by organizing the data effectively by using modern data science approach to eliminate
question duplication.
As reported by Quora there has been many duplicate questions asked by users which
actually means the same thing and creates a confusion as people have answered to the
same question in different locations . For the instance , suppose take these two questions-
“How old are you ? ”&“What is your birthday?”. Although these questions have no
word in common but have the same intent.Hence, Quora would like to group these
similar questions together so that all the answers could be presented at the same place
and a better user experience overall. We have used the dataset provided by Quora to
create a model which can identify duplicate questions posted by the users.
We need to create a machine learning software to understand that specific language,
there are plenty of NLP machine learning tutorials out there.Once we have an NLP
understanding software you can then run through all the questions and push the output
data to another machine learning software, One that can identify contextual similarity
patterns from your data.

...........Conclusion...........

After testing out 5 models we see that on average Random Forest model shows better
result overall most of the cases .
We can conclude that the models based on homogeneous ensembling feature works better on the dataset that we have taken for out project. A universal rule of thumb:
• Homogeneous ensembles use the same feature selection with a variety of data and
distribute the dataset over several nodes.
• Heterogeneous ensembles use different feature selection methods with the same data
We are getting around 80 percent accuracy with random forest which is quite good
for a ML model, from here on adding new features would result in exponentially slow
improvement on the accuracy of the model.
The model could do better if we include few more advanced features like distance features in the future.
Another way, Quora could achieve a better by pre-processing the original question pair
dataset. Since knowing the context in which question is asked, a proper replacement of
some of the pronouns can be done, and higher accuracy can be achieved.
For example, pronoun like us, we, they can be replaced if the topic under which question
exists thus replacing it with their relative context like “American,” “ Programmers ”
and “ Prisoners ’ etc. during the pre- processing data stage can help achieve a better
result.
As we are unaware in which context questions were asked we could not do such preprocessing on the original dataset.
Increasing the batch sizes usually yields better results, as the task gets harder. It is
more difficult to identify the correct duplicate question out of a set of 100 questions
than out of a set of only 10 questions.
So it is advisable to set the training batch size as large as possible. I trained it with a
batch size of 20000 on 8 GB GPU memory
