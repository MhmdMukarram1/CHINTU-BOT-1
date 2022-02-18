FROM Ajx-Abu/Sana-Mwol:latest

RUN git clone https://github.com/MhmdMukarram1/CHINTU-BOT-1 /root/sans
WORKDIR /root/sana/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ajx-Abu/sana-media

CMD ["node", "bot.js"]
