# contractsubmission
## Deploy
	concordium-client module deploy contractsubmission.wasm.v1 --name contractsubmission --sender kastavotevas --grpc-ip node.testnet.concordium.com --grpc-port 10000

https://github.com/kastavotevas/contractsubmission/blob/master/screenshots/Screenshot%202023-02-26%20at%2000.38.11.png

Trans hash: c7412cbe9bae971c792ee1b5bbfd968f96e369b18310c2705298967154a09b13

Ref hash: 51bc4614d4cd207b2828087a10fc4e26d9c2870f67f4eeb2fa0e5dc1c4266537

## Init
https://github.com/kastavotevas/contractsubmission/blob/master/screenshots/Screenshot%202023-02-26%20at%2000.41.53.png

	concordium-client contract init contractsubmission --contract contractsubmission  --sender kastavotevas --energy 10000 --grpc-ip node.testnet.concordium.com --grpc-port 10000

Trans hash: 0cae43632b5d914c1d5d28c1306def177c6a0d3d5aec690519a4b5d623088b4a


## Update
	concordium-client contract update 3444 --entrypoint receive --energy 10000 --sender kastavotevas --parameter-json update_param.json --grpc-ip node.testnet.concordium.com --grpc-port 10000

Trans hash: 66c061ff97982c572018721ef1e8fc9d73cd8c0c2360a1c769ba16af4a3a3761

https://github.com/kastavotevas/contractsubmission/blob/master/screenshots/Screenshot%202023-02-26%20at%2000.42.42.png

#Invoke
https://github.com/kastavotevas/contractsubmission/blob/master/screenshots/Screenshot%202023-02-26%20at%2000.45.13.png

#Mainnet Address CCD
3JRCMzAFT5EnZ8GGWupMgTNnsW51sVfDNTz939A8n7BVUbK1S7
