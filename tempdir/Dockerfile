FROM python
RUN pip3 install flask
COPY ./static /home/myapp/static/
COPY ./templates /home/myapp/templates/
COPY test_app.py /home/myapp/
EXPOSE 8080
CMD [python3,/home/myapp/test_app.py]
CMD [flask,run,--host,0.0.0.0]
