FROM Ajx-Abu/Sana-Mwol:latest

RUN git clone https://github.com/MhmdMukarram1/CHINTU-BOT-1 /root/sana
WORKDIR /root/sana/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/MhmdMukarram1/1901/tree/master/plugins

CMD ["node", "bot.js"]
