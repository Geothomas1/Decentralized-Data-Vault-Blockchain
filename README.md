# Getting Started with Decentralized-Data-Vault-Blockchain
This  Hyperledger Fabric Blockchain network manage data for different service Requests

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


### 'OUTPUT Start'
<img src="out1.png">
<br>
<br>
### 'login and Register to Network'
<img src="out2.png">
<br>
<br>
<img src="out3.png">
### 'Chaincode DEV'
<img src="out4.png">
<br>
<br>
<img src="out5.png">
<br>
<br>
<img src="out6.png">
###POSTMAN Request and CouchDB
<img src="out7.png">
<br>
<br>
<img src="out8.png">
###For Restart containers
docker start $(docker ps -aq)
###TXID DATA 


{
    "validationCode": 0,
    "transactionEnvelope": {
        "signature": {
            "type": "Buffer",
            "data": [
                48,
                69,
                2,
                33,
                0,
                239,
                80,
                212,
                139,
                98,
                165,
                155,
                119,
                136,
                242,
                113,
                134,
                167,
                127,
                230,
                102,
                89,
                33,
                163,
                171,
                185,
                3,
                249,
                203,
                75,
                133,
                15,
                115,
                178,
                128,
                125,
                235,
                2,
                32,
                121,
                73,
                69,
                167,
                137,
                63,
                192,
                38,
                73,
                58,
                7,
                226,
                84,
                117,
                141,
                99,
                251,
                254,
                137,
                99,
                111,
                238,
                145,
                247,
                70,
                50,
                210,
                232,
                207,
                26,
                211,
                99
            ]
        },
        "payload": {
            "header": {
                "channel_header": {
                    "type": 3,
                    "version": 1,
                    "timestamp": "2020-11-28T08:48:41.044Z",
                    "channel_id": "mychannel",
                    "tx_id": "0c1f7a3e681029f5cf6c2253d454b12ba2e02091e6658107a912cc8471b899c8",
                    "epoch": "0",
                    "extension": {
                        "type": "Buffer",
                        "data": [
                            18,
                            8,
                            18,
                            6,
                            102,
                            97,
                            98,
                            99,
                            97,
                            114
                        ]
                    },
                    "typeString": "ENDORSER_TRANSACTION"
                },
                "signature_header": {
                    "creator": {
                        "Mspid": "Org1MSP",
                        "IdBytes": "-----BEGIN CERTIFICATE-----\nMIICnTCCAkOgAwIBAgIUcwfOSakwIjYqEwBxP4dDIDcMw9owCgYIKoZIzj0EAwIw\nczELMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNh\nbiBGcmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHDAaBgNVBAMT\nE2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMjAxMTI4MDgyMzAwWhcNMjExMTI4MDgy\nODAwWjBAMTAwDQYDVQQLEwZjbGllbnQwCwYDVQQLEwRvcmcxMBIGA1UECxMLZGVw\nYXJ0bWVudDExDDAKBgNVBAMTA1NhbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IA\nBFUT/jJO4/3KO0WI4ezLcbOq5jmckZXMoE8+YgFMOJALoPUZV07g/xghDipKZmYm\nIq5k5J19AgPQePtMYJlwkLKjgecwgeQwDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB\n/wQCMAAwHQYDVR0OBBYEFM42NwhK7musRQjqd2NHVbQOCDi9MCsGA1UdIwQkMCKA\nINShtTbf08tNixkYEJLxVp3et5xyiW4GYypdz2qXxgpUMHgGCCoDBAUGBwgBBGx7\nImF0dHJzIjp7ImhmLkFmZmlsaWF0aW9uIjoib3JnMS5kZXBhcnRtZW50MSIsImhm\nLkVucm9sbG1lbnRJRCI6IlNhbSIsImhmLlR5cGUiOiJjbGllbnQiLCJyb2xlIjoi\nYXBwcm92ZXIifX0wCgYIKoZIzj0EAwIDSAAwRQIhALNlmwjvnnQ+3iT725mE23Gj\nSM9LzHRoho0yjzcd4+AXAiBslP90Nl9D3OCrGzNguSbX/ZlV3V1bVIQAVzuqFwLG\nYg==\n-----END CERTIFICATE-----\n"
                    },
                    "nonce": {
                        "type": "Buffer",
                        "data": [
                            137,
                            166,
                            199,
                            239,
                            190,
                            12,
                            167,
                            9,
                            180,
                            133,
                            47,
                            247,
                            113,
                            191,
                            251,
                            225,
                            212,
                            211,
                            233,
                            156,
                            132,
                            157,
                            2,
                            85
                        ]
                    }
                }
            },
            "data": {
                "actions": [
                    {
                        "header": {
                            "creator": {
                                "Mspid": "Org1MSP",
                                "IdBytes": "-----BEGIN CERTIFICATE-----\nMIICnTCCAkOgAwIBAgIUcwfOSakwIjYqEwBxP4dDIDcMw9owCgYIKoZIzj0EAwIw\nczELMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNh\nbiBGcmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHDAaBgNVBAMT\nE2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMjAxMTI4MDgyMzAwWhcNMjExMTI4MDgy\nODAwWjBAMTAwDQYDVQQLEwZjbGllbnQwCwYDVQQLEwRvcmcxMBIGA1UECxMLZGVw\nYXJ0bWVudDExDDAKBgNVBAMTA1NhbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IA\nBFUT/jJO4/3KO0WI4ezLcbOq5jmckZXMoE8+YgFMOJALoPUZV07g/xghDipKZmYm\nIq5k5J19AgPQePtMYJlwkLKjgecwgeQwDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB\n/wQCMAAwHQYDVR0OBBYEFM42NwhK7musRQjqd2NHVbQOCDi9MCsGA1UdIwQkMCKA\nINShtTbf08tNixkYEJLxVp3et5xyiW4GYypdz2qXxgpUMHgGCCoDBAUGBwgBBGx7\nImF0dHJzIjp7ImhmLkFmZmlsaWF0aW9uIjoib3JnMS5kZXBhcnRtZW50MSIsImhm\nLkVucm9sbG1lbnRJRCI6IlNhbSIsImhmLlR5cGUiOiJjbGllbnQiLCJyb2xlIjoi\nYXBwcm92ZXIifX0wCgYIKoZIzj0EAwIDSAAwRQIhALNlmwjvnnQ+3iT725mE23Gj\nSM9LzHRoho0yjzcd4+AXAiBslP90Nl9D3OCrGzNguSbX/ZlV3V1bVIQAVzuqFwLG\nYg==\n-----END CERTIFICATE-----\n"
                            },
                            "nonce": {
                                "type": "Buffer",
                                "data": [
                                    137,
                                    166,
                                    199,
                                    239,
                                    190,
                                    12,
                                    167,
                                    9,
                                    180,
                                    133,
                                    47,
                                    247,
                                    113,
                                    191,
                                    251,
                                    225,
                                    212,
                                    211,
                                    233,
                                    156,
                                    132,
                                    157,
                                    2,
                                    85
                                ]
                            }
                        },
                        "payload": {
                            "chaincode_proposal_payload": {
                                "input": {
                                    "chaincode_spec": {
                                        "type": 1,
                                        "typeString": "GOLANG",
                                        "input": {
                                            "args": [
                                                {
                                                    "type": "Buffer",
                                                    "data": [
                                                        99,
                                                        104,
                                                        97,
                                                        110,
                                                        103,
                                                        101,
                                                        67,
                                                        97,
                                                        114,
                                                        79,
                                                        119,
                                                        110,
                                                        101,
                                                        114
                                                    ]
                                                },
                                                {
                                                    "type": "Buffer",
                                                    "data": [
                                                        83,
                                                        117,
                                                        112,
                                                        101,
                                                        114,
                                                        99,
                                                        97,
                                                        114,
                                                        49
                                                    ]
                                                },
                                                {
                                                    "type": "Buffer",
                                                    "data": [
                                                        83,
                                                        117,
                                                        110,
                                                        110,
                                                        121
                                                    ]
                                                }
                                            ],
                                            "decorations": {}
                                        },
                                        "chaincode_id": {
                                            "path": "",
                                            "name": "fabcar",
                                            "version": ""
                                        },
                                        "timeout": 0
                                    }
                                }
                            },
                            "action": {
                                "proposal_response_payload": {
                                    "proposal_hash": "8acd55d922bfd2c5df41f310938cda31600b10ec6b026501ae8d88286cc8932f",
                                    "extension": {
                                        "results": {
                                            "data_model": 0,
                                            "ns_rwset": [
                                                {
                                                    "namespace": "_lifecycle",
                                                    "rwset": {
                                                        "reads": [
                                                            {
                                                                "key": "namespaces/fields/fabcar/Sequence",
                                                                "version": {
                                                                    "block_num": "5",
                                                                    "tx_num": "0"
                                                                }
                                                            }
                                                        ],
                                                        "range_queries_info": [],
                                                        "writes": [],
                                                        "metadata_writes": []
                                                    },
                                                    "collection_hashed_rwset": []
                                                },
                                                {
                                                    "namespace": "fabcar",
                                                    "rwset": {
                                                        "reads": [
                                                            {
                                                                "key":"


