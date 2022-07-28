FROM python:3.11.0b5-buster

RUN pip install -U https://github.com/platformio/platformio-core/archive/develop.zip
RUN platformio update
# To get the test platforms
RUN pip install PyYaml
#ENV PATH /code/buildroot/bin/:/code/buildroot/tests/:${PATH}
