This is the repository for the word embeddings session at the 
[Practical AI for Women day-long event](https://www.eventbrite.com/e/practical-ai-for-female-engineers-product-managers-and-designers-tickets-34805104003).

The session will include a presentation, as well as a demo in Python.  Below are instructions on how to set up the demo yourself, 
if you choose. If you are not comfortable doing so or don't code, no problem, you will still get a lot out of the session.

We will be using a dataset of pretrained and pre-processed [GloVe word embeddings](https://nlp.stanford.edu/projects/glove/) 
available at http://files.fast.ai/models/

To download and unzip the files from the command line, you can run:

    wget http://files.fast.ai/models/glove_50_glove_100.tgz 
    tar xvzf glove_50_glove_100.tgz

To create a virtual environment, install the necessary requirements, and start the jupyter notebook server:

    virtualenv env
    source env/bin/activate
    pip install -r requirements.txt
    jupyter notebook
    
