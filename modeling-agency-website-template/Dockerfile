FROM nginx

WORKDIR modeling-agency-website-template

COPY . /modeling-agency-website-template/index.html 
COPY . /modeling-agency-website-template/css
COPY . /modeling-agency-website-template/js

RUN nginx install

EXPOSE nginx 8000:8000

CMD ['nginx','index.html']
