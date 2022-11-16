FROM httpd

WORKDIR /usr/local/apache2/htdocs

COPY coming-soon-evening-html.zip .

RUN apt update && apt install unzip -y

RUN rm /usr/local/apache2/htdocs/*.html && \
    unzip coming-soon-evening-html.zip && rm *zip



