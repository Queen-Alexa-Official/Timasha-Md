FROM quay.io/KING-BOT-OFFICIAL/KING-BOT-MD:multidevice

RUN git clone https://github.com/KING-BOT-OFFICIAL/KING-BOT-MD /skl/KING-BOT-MD
WORKDIR /skl/KING-BOT-MD
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
