FROM aarch64/python
MAINTAINER cultclassik@gmail.com

ENV \
	# set python to use utf-8 rather than ascii.
	PYTHONIOENCODING="UTF-8"

RUN pip install --upgrade pip

RUN pip3 install pymysql

RUN pip install homeassistant

CMD ["hass", "--open-ui", "--config", "/config"]

VOLUME /config
EXPOSE 8123
