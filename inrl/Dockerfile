FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/fasweeh-faz/Inrl /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/fasweeh-faz/media
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
