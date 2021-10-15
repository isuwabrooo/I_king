FROM fusuf/whatsasena:latest

RUN git clone https://github.com/isuwabrooo/I_king /root/I_king
WORKDIR /root/I_king/
ENV TZ=Europe/Istanbul
RUN npm install supervisor 
RUN yarn install --no-audit

CMD ["node", "bot.js"]
