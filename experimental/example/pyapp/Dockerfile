FROM python:2.7
MAINTAINER Weaveworks Inc <help@weave.works>
WORKDIR /home/weave
ADD requirements.txt /home/weave/
RUN pip install -r /home/weave/requirements.txt
ADD app.py /home/weave/
ENTRYPOINT ["python", "/home/weave/app.py"]
