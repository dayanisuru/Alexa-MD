FROM quay.io/dayanisuru/alexa:md
RUN git clone https://github.com/dayanisuru/Alexa-MD /root/Alexa/
WORKDIR /root/Alexa/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
