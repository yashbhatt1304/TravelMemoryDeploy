FROM node:20
WORKDIR /app
COPY . .
RUN npm install
COPY start.sh /app/start.sh
RUN chmod +x /app/start.sh
EXPOSE 3000
CMD [ "/app/start.sh" ]