FROM lyseontech/vue:v3.0.0-rc.5

RUN apt-get update \
 && apt-get install -y libgtkextra-dev libgconf2-dev libnss3 libasound2 libxtst-dev libxss1 --no-install-recommends \
 && rm -rf /var/lib/apt/lists/*

RUN npm install --global\
 quasar-cli@0.17.0-beta.22\
 http-server@0.11.1
