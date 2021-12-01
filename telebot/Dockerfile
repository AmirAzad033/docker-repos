FROM python:latest
COPY bot.py .
RUN pip3 install pyrogram --upgrade
RUN pip3 install tgcrypto --upgrade
ENTRYPOINT [ "python3" ]
CMD ["bot.py"] 