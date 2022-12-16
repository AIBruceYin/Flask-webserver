# Flask-webserver

#-----------------Method1----------------
#create requirements.txt, it will list the required packages
pip freeze > requirements.txt

pip install requirements.txt

#-----------------Method2----------------
#create requirements.txt, it will list the used packages
#install pipreqes
pip install pipreqs

#complete pip requirements
pipreqs ./ --encoding==utf-8
