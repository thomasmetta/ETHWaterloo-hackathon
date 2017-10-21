Install TestRPC locally:

`npm install -g ethereumjs-testrpc`

[Download this TestRPC snapshot](https://s3.amazonaws.com/testrpc-shapshots/35053f9.zip)

Go to the download folder of TestRPC snapchat and upzip

`unzip ./35053f9.zip -d ./0x_testrpc_snapshot`


Run TestRPC
```
testrpc \
--networkId 50 \
-p 8545 \
--db ./0x_testrpc_snapshot \
-m "concert load couple harbor equip island argue ramp clarify fence smart topic"
```

Install dependencies

`npm install`

Start the App

`npm start`