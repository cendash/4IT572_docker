FROM node:10

COPY . .                    # vse z rootu

RUN npm install \ 
 && npm run build           # Pousti prikazy na OS image

EXPOSE 3000                 # otevreme port

ENTRYPOINT npm run start    # nebo CMD



