# FROM node
# WORKDIR /app
# COPY package*.json ./
# RUN npm install
# COPY . .
# EXPOSE 5173
# CMD ["npm", "run", "dev"]

FROM nginx:alpine
COPY default.conf /etc/nginx/conf.d/default.conf
COPY ./dist /usr/share/nginx/html
EXPOSE 80
CMD [ "nginx", "-g", "daemon off" ]