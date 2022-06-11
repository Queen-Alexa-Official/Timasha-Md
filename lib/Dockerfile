FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/KING-BOT-OFFICIAL/SL-KING-X-MD /skl/SL-KING-X-MD
WORKDIR /skl/SL-KING-X-MD
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
