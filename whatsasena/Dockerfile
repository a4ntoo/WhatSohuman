FROM fusuf/whatsasena:latest

RUN git clone https://github.com/phaticusthiccy/a4ntoo/root/a4nto
WORKDIR /root/a4ntoo/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
