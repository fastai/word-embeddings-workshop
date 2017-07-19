This is the repository for the word embeddings session at the [Demystifying Deep Learning conference](https://www.eventbrite.com/e/demystifying-deep-learning-ai-tickets-34351888423) and the 
[Practical AI for Women day-long event](https://www.eventbrite.com/e/practical-ai-for-female-engineers-product-managers-and-designers-tickets-34805104003).  A video of the workshop is [available here](https://www.youtube.com/watch?v=25nC0n9ERq4).

The session will include a presentation, as well as a demo in Python.  Below are instructions on how to set up the demo yourself, 
if you choose. If you are not comfortable doing so or don't code, no problem, you will still get a lot out of the session.

We will be using a dataset of pretrained and pre-processed [GloVe word embeddings](https://nlp.stanford.edu/projects/glove/) 
available at http://files.fast.ai/models/

To download and unzip the files from the command line, you can run:

    wget http://files.fast.ai/models/glove_50_glove_100.tgz 
    tar xvzf glove_50_glove_100.tgz

I recommend downloading [Anaconda](https://www.continuum.io/downloads), which contains the main Python scientific libraries.  Alternately, you can create a virtual environment and install the necessary requirements: 

    virtualenv env
    source env/bin/activate
    pip install -r requirements.txt
    
To start the jupyter notebook from the command line:

    jupyter notebook
    
