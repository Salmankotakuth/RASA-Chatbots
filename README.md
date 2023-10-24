# RASA-Chatbots
AI Chatbots using RASA Frameworks

It is an easy way to create chatbots using RASA Frameworks. Here are the steps to follow for installing rasa in your system.

1. Install python
2. Create a new directory for developing a Virtual environment
  	-	mkdir rasa_directory.
  	-	cd rasa_directory.
3. Create a Virtual Environment
  	>>>	apt install python3.10-venv
  	>>>	python3 -m venv ./venv
  	>>>	source ./venv/bin/activate
3. Install rasa by using pip 
  	>>>	sudo apt install python3-pip
  	>>>	pip install rasa
4. Run rasa
  	>>>	rasa init
5. Run rasa chatbot
    >>>	rasa run -m models –enable-api –cors “*”
