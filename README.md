# HungryGator
An aggregator of restaurant data.


This is a course-work project.
This aims to aggregate restaurant data from different online platforms to educate the customer 
which platform they should trust w.r.t different restaurants.

Below are the instructions for installing the dependencies for the application:

pip install -r stable-req.txt 



Please follow below instructions if you run into the below issues:

1. We are using WordCloud for producing WordCloud on the restaurants.

--> You might face issues when trying to import wordcloud in Anaconda.
    Follow the below steps to get it resolved:


    i. This most likely happens because in spite of having wordcloud in the local python environment, it is not available to the Anaconda package.


   ii. Try installing the wordcloud package using the Anaconda terminal.
       If you are using MAC, you might have to change the default shell to bash in order for the Anaconda Shell to run as the shell is available to bash only.
       Use: chsh -s /bin/bash to change the shell from zsh to bash.
       Use: chsh -s /bin/zsh to revert back to zsh later.


   iii.Once the shell has been changed run the below command on the Anaconda shell to install wordcloud.
       conda install -c conda-forge wordcloud


   iv. After this ideally the wordcloud import statements should work.
