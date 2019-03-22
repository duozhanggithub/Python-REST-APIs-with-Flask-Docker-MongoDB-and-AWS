#download python 3 from docker hub
FROM python:3 #download not only python 3, but also ubuntu operating system

#Tell the image(ubuntu OS with python 3 installed), the working directory is /usr/src/app
WORKDIR /usr/src/app

#copy requirements.txt from local machine (the directory include the docker file) 
#to current working directory /usr/src/app
COPY requirements.txt .

#install libraries listed in the requirements.txt on the Ubuntu machine
RUN pip install --no-cache-dir -r requirements.txt

#copy all the files from local machine to the ubuntu 
COPY . .

#run python app.py
CMD ["python", "app.py"]