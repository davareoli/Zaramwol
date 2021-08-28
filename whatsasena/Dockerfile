FROM fusuf/whatsasena:latest

RUN https://github.com/Jokerser-x-Raashii/Zaramwol
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
