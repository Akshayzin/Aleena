FROM https:/quay.io/repository/akshayzin:latest
RUN git clone https://github.com/Akshayzin/Aleena/root/Aleena
WORKDIR /root/X-Asena
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 


