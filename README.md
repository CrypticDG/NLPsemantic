#### NLPsemantic
##### Semantic similarity with NLP Spacy
##### Code description 1. 2. 3. 
###### IDE used = Virtual Studio, OP = Windows 11, Language = Python
###### 3.1 Clone repository with command below. Must have Git & Github installed.
###### git clone https://github.com/CrypticDG/NLPsemantic
######  3.2 Move to project root folder
######  cd NLPsemantic
###### 3.3 Create a virtual environment
######  virtualenv 'env1' - (create virtual environment and give it a name)
######  env1\scripts\activate (activate virtual environment that stored all your modules for your project)
######  3.4 Install requirements.txt, (this will install all the modules you will need to run this app)
###### py -m pip install -r requirements.txt
######  3.5 run you app  (not containerized before deploy, see Docker section 3.6)
###### 3.6 Docker(Have Docker Hub and Docker desktop installed)
###### Run in terminal: docker build -t nlp1 .    
###### Run in terminal: docker run nlp1  