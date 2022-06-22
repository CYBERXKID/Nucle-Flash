FROM fusuf/whatsasena:latest

RUN git clone https://github.com/CYBERXKID/Nucle-Flash /root/Flash
WORKDIR /root/Flash/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines

CMD ["node", "bot.js"]
 
