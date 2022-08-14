FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/Queen-Alexa-Official/Timasha-Md /skl/Timasha-Md
WORKDIR /skl/SL-KING-X-MD
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
