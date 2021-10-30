# hello-world
My Repository

curl -X POST https://api.easypost.com/v2/addresses \
  -u <YOUR_TEST/PRODUCTION_API_KEY>: \
  -d 'address[company]=JMR' \
  -d 'address[street1]=1600 Fairmont Ave APT 7' \
  -d 'address[street2]=' \
  -d 'address[city]=Fairmont' \
  -d 'address[state]=WV' \
  -d 'address[zip]=26554' \
  -d 'address[phone]=681-758-4223'
