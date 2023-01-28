FROM node

WORKDIR back_end

COPY . .

RUN npm install

RUN npm run clean

EXPOSE 5000

CMD npm run dev