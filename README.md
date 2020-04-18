# How to connect a Geth node to RSK

1. Run RSK Node
java -cp ./rskj-core-1.3.0-WASABI-all.jar co.rsk.Start --regtest

2. Run Get attaching it to RSK node
geth attach http://127.0.0.1:4444 

3. Deploy contract and interact via web3

loadScript(register.js)
register.getInfo()
register.setInfo('RSK',{from: eth.accounts[1]})


## Tutorial based on following webinar

https://www.youtube.com/watch?v=apcD6bcSWpw