# MedSplorer
This is the code for an app which connects the Pubmed API to the OpenAI model GPT-3.5-turbo
If you like a response, copy it to your clipboard before your next query!

Instructions:

1) Enter a valid email address in the 'EMail' field. This is a requirement of the PubMed API. 

2) Enter your OpenAI API key in the 'OpenAI' field. to generate an API Key (write this down somewhere!), navigate to https://platform.openai.com/account/api-keys, log in, and select 'Create API Key.' I don't want to charge for the use of this app, so you pay as you go! Each query costs a little less than one cent.

3)Input your query! The app will extract keywords and search pubmed for the most relevant papers, where the titles and abstracts will be fed through the GPT-3.5 turbo API.

4)The 'Search Type' feature lets you specify if you want to search just review papers or all papers available.

5)The 'Operation Type' is where the magic happens! Selecting 'Literature Review' will prompt the app to create a summary of the information it finds. 'Relevant Questions' will pose some potential questions you can explore in the literature to further hone what you want to investigate. 'Custom Prompt' lets you format the response to your pubmed search in any manner! An example would be to prompt it to create practice questions, provide an example outline for a review paper, etc.

6)'Submit' initiates the search. Because the app is bouncing between multiple APIs to maximize the number of search results and provide the best answer, it should take between 20 and 40 seconds to process each request. Your query, an answer to your query with in-text citations, and a list of all references will generate in the main box.

7) After each query, if you like the response then 'Copy to Clipboard' allows you to temporarily copy the entire generated response to paste into whatever word processor of your choice.

8) At the end of your entire session, if you would like to save all of the references you have generated, click on "save to Zotero" to save a .bib file which can be imported to the Citation management system. For more information on Zotero, see here: https://www.zotero.org/
