FROM nginx

#RUN apt-get update -y && \
#    apt-get install -y python-pip python3 python-dev build-essential

# We copy just the requirements.txt first to leverage Docker cache
#COPY ./requirements.txt /app/requirements.txt

#COPY ./requirements.txt /app/requirements.txt

#COPY nginx.conf /etc/nginx/conf.d/default.conf

COPY . /usr/share/nginx/html

#WORKDIR /app

#RUN pip install -r     requirements.txt

#COPY . /app

#ENTRYPOINT [ "python"]

#EXPOSE 5000

#CMD ["app.py" ]