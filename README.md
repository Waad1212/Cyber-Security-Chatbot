# Cyber-Security-Chatbot
A chatbot was used in the experiment (in the research paper)
# Explanation of chatbot
This code sets up a system for building a question-and-answer chatbot that retrieves information from uploaded documents (PDF, Docx, Txt) and utilizes a large language model (LLM) for generating responses.
This chatbot was tested on a group of students after training it on 70 correct pieces of information and 30 incorrect pieces of information (two PDF files are in this repost) to test the extent of their confidence in the answers provided by large language models.
# how to operate
1- Run this code in Google Colab.
2- After running a cell (mkdir docs!), you will find in the files on the left side a folder called docs.
3- Download the files you want to train the model on in this folder (in my case, I downloaded the correct data file and the Poisoned data file)
4- Turn on the rest of the cells
5- Finally, I linked the code to a user interface using gradio so that users can interact with the chatbot easily so after the last cell, a link will appear that you can share to try the chatbot.
