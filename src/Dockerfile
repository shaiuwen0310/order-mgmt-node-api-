FROM node:12.22.8

WORKDIR /src/order-mgmt-node-api
COPY . /src/order-mgmt-node-api
RUN npm install --production \
	&& npm install pm2 -g --no-optional --production
