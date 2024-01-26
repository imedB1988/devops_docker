FROM python
 
# Create app directory
WORKDIR /app
 
# Install app dependencies
#COPY requirements.txt ./
COPY . .
 
RUN pip install -r requirments.txt
 
# Bundle app source

 
EXPOSE 5000
CMD [ "flask", "run","--host","0.0.0.0","--port","5000"]
