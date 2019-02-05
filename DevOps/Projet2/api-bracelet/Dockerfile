FROM python:3
ADD __main__.py /
ADD _version.py /
ADD requirement.txt /
RUN pip install pystrich
CMD [ "python", "./__main__.py" ]
