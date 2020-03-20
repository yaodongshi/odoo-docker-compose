FROM registry.docker-cn.com/library/odoo:12
# CN fonts
User root
ADD chinese.msyh.ttf /usr/local/share/fonts/
ADD simsun.ttc /usr/local/share/fonts/
ADD trebuchet-ms/*.ttf /usr/local/share/fonts/
RUN fc-cache -rf
COPY ir_mail_server.py /usr/lib/python3/dist-packages/odoo/addons/base/models/ir_mail_server.py
