client
dev tun
proto udp
remote 34.175.8.33 1194
resolv-retry infinite
nobind
persist-key
persist-tun
remote-cert-tls server
auth SHA512
ignore-unknown-option block-outside-dns
verb 3

<cert>
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number:
            3d:ba:3c:00:70:00:44:5a:31:b0:5a:15:d8:83:34:0d
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: CN=Easy-RSA CA
        Validity
            Not Before: May  3 18:49:59 2026 GMT
            Not After : Apr 30 18:49:59 2036 GMT
        Subject: CN=debian-casa
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                Public-Key: (2048 bit)
                Modulus:
                    00:b2:49:91:9b:da:51:df:15:3d:b1:56:22:76:9b:
                    71:0e:df:60:50:2c:5d:e7:d8:91:01:44:eb:e4:96:
                    42:4a:0d:53:8b:1f:90:b5:0b:77:51:7d:98:50:01:
                    03:31:4b:98:22:eb:c1:71:86:de:47:ec:6d:84:c6:
                    58:ff:d6:70:cb:fc:18:2a:fe:f0:f3:63:56:f7:43:
                    40:2e:19:f2:fb:3b:22:fa:d9:3a:f9:42:b3:47:56:
                    df:a1:fe:63:10:44:a2:61:cb:c5:34:76:e6:69:02:
                    8b:26:71:03:4a:bf:91:a6:28:99:bf:db:aa:25:87:
                    9d:1a:e4:ca:e4:28:10:2a:7e:29:2a:6e:53:e3:44:
                    41:dd:8c:80:ed:71:45:09:e5:98:17:50:47:b9:ef:
                    f3:a5:c3:d4:df:ed:6a:c7:c5:01:a2:2e:2b:5d:18:
                    a0:60:e4:94:80:88:a3:94:7a:3f:2b:c3:43:88:88:
                    f4:b6:1d:f0:0c:27:f9:2a:18:95:aa:26:91:31:c1:
                    23:1f:c4:33:4b:78:a2:24:6c:a6:33:3f:12:41:01:
                    29:2b:f3:d1:94:2a:02:e7:68:db:0a:8f:ba:9b:eb:
                    79:16:1f:66:34:f4:73:7d:31:b3:b5:c2:1b:6f:56:
                    3b:c3:9e:04:39:76:34:4a:a8:95:cb:a5:63:12:9f:
                    dc:ab
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            X509v3 Basic Constraints: 
                CA:FALSE
            X509v3 Subject Key Identifier: 
                AB:D0:89:05:AB:E6:64:3C:2F:3A:DF:CA:D5:DE:8F:C9:6D:60:D7:48
            X509v3 Authority Key Identifier: 
                keyid:FE:BA:03:3A:84:F8:E6:48:3C:34:F4:12:73:5E:1A:2D:7C:59:F3:88
                DirName:/CN=Easy-RSA CA
                serial:7B:55:EB:07:28:B7:B3:36:C2:23:DC:34:7D:54:45:FF:AC:AD:B0:55
            X509v3 Extended Key Usage: 
                TLS Web Client Authentication
            X509v3 Key Usage: 
                Digital Signature
    Signature Algorithm: sha256WithRSAEncryption
    Signature Value:
        4e:45:7e:d7:11:b2:cc:a6:07:88:29:c5:62:fe:21:f6:ef:db:
        7f:02:7c:2b:70:f0:69:a9:a2:17:4f:5d:87:3c:2b:d5:5e:05:
        6a:62:d5:7c:c6:d6:b1:4e:81:93:c5:13:1b:27:b2:51:0c:1d:
        90:ab:2f:69:ef:0b:f4:88:bd:64:c2:ef:dd:1a:81:12:b7:4f:
        26:13:07:63:7b:b9:28:fa:b6:6c:65:38:8f:96:58:8c:30:6b:
        e2:fc:3c:03:6e:e6:1f:d1:40:04:99:13:5b:17:5d:7a:79:43:
        ca:8e:51:95:a6:76:e4:90:64:45:34:27:76:41:17:89:cd:fa:
        54:1d:40:18:30:ba:08:57:fb:b1:d4:26:88:38:ea:31:01:16:
        7b:e0:5b:d7:39:7d:58:0e:e3:86:8b:bb:f7:e6:c1:f9:8b:5b:
        bc:a6:52:17:8c:02:79:b0:14:c4:26:21:eb:80:83:76:4d:0e:
        40:49:5b:b7:28:10:3a:bd:1d:29:c6:07:bb:20:5f:71:23:38:
        2b:67:10:44:29:d0:db:ab:55:1c:2d:e4:03:1a:1d:2f:ad:91:
        ea:75:ef:49:ae:c2:0a:a8:97:fb:e1:b3:17:4a:1e:2d:a1:e1:
        f8:a1:46:b5:0e:cc:47:b3:c3:a2:46:43:05:fb:2f:88:25:b5:
        fa:8f:06:74
-----BEGIN CERTIFICATE-----
MIIDWTCCAkGgAwIBAgIQPbo8AHAARFoxsFoV2IM0DTANBgkqhkiG9w0BAQsFADAW
MRQwEgYDVQQDDAtFYXN5LVJTQSBDQTAeFw0yNjA1MDMxODQ5NTlaFw0zNjA0MzAx
ODQ5NTlaMBYxFDASBgNVBAMMC2RlYmlhbi1jYXNhMIIBIjANBgkqhkiG9w0BAQEF
AAOCAQ8AMIIBCgKCAQEAskmRm9pR3xU9sVYidptxDt9gUCxd59iRAUTr5JZCSg1T
ix+QtQt3UX2YUAEDMUuYIuvBcYbeR+xthMZY/9Zwy/wYKv7w82NW90NALhny+zsi
+tk6+UKzR1bfof5jEESiYcvFNHbmaQKLJnEDSr+RpiiZv9uqJYedGuTK5CgQKn4p
Km5T40RB3YyA7XFFCeWYF1BHue/zpcPU3+1qx8UBoi4rXRigYOSUgIijlHo/K8ND
iIj0th3wDCf5KhiVqiaRMcEjH8QzS3iiJGymMz8SQQEpK/PRlCoC52jbCo+6m+t5
Fh9mNPRzfTGztcIbb1Y7w54EOXY0SqiVy6VjEp/cqwIDAQABo4GiMIGfMAkGA1Ud
EwQCMAAwHQYDVR0OBBYEFKvQiQWr5mQ8LzrfytXej8ltYNdIMFEGA1UdIwRKMEiA
FP66AzqE+OZIPDT0EnNeGi18WfOIoRqkGDAWMRQwEgYDVQQDDAtFYXN5LVJTQSBD
QYIUe1XrByi3szbCI9w0fVRF/6ytsFUwEwYDVR0lBAwwCgYIKwYBBQUHAwIwCwYD
VR0PBAQDAgeAMA0GCSqGSIb3DQEBCwUAA4IBAQBORX7XEbLMpgeIKcVi/iH279t/
AnwrcPBpqaIXT12HPCvVXgVqYtV8xtaxToGTxRMbJ7JRDB2Qqy9p7wv0iL1kwu/d
GoESt08mEwdje7ko+rZsZTiPlliMMGvi/DwDbuYf0UAEmRNbF116eUPKjlGVpnbk
kGRFNCd2QReJzfpUHUAYMLoIV/ux1CaIOOoxARZ74FvXOX1YDuOGi7v35sH5i1u8
plIXjAJ5sBTEJiHrgIN2TQ5ASVu3KBA6vR0pxge7IF9xIzgrZxBEKdDbq1UcLeQD
Gh0vrZHqde9JrsIKqJf74bMXSh4toeH4oUa1DsxHs8OiRkMF+y+IJbX6jwZ0
-----END CERTIFICATE-----
</cert>

<key>
-----BEGIN PRIVATE KEY-----
MIIEvgIBADANBgkqhkiG9w0BAQEFAASCBKgwggSkAgEAAoIBAQCySZGb2lHfFT2x
ViJ2m3EO32BQLF3n2JEBROvklkJKDVOLH5C1C3dRfZhQAQMxS5gi68Fxht5H7G2E
xlj/1nDL/Bgq/vDzY1b3Q0AuGfL7OyL62Tr5QrNHVt+h/mMQRKJhy8U0duZpAosm
cQNKv5GmKJm/26olh50a5MrkKBAqfikqblPjREHdjIDtcUUJ5ZgXUEe57/Olw9Tf
7WrHxQGiLitdGKBg5JSAiKOUej8rw0OIiPS2HfAMJ/kqGJWqJpExwSMfxDNLeKIk
bKYzPxJBASkr89GUKgLnaNsKj7qb63kWH2Y09HN9MbO1whtvVjvDngQ5djRKqJXL
pWMSn9yrAgMBAAECggEABQNwy6wP3+qPsadrtt/rH3ekYTMsltYhSbxZUWdXFao0
EbYn0kRJ+cNceTXcemvj3mnrwCU1pfPqwBbFyB5ZgKe/oQhKchJ2jrBxvK1WufE+
Eni+VRkNKot+V8zr/NHS3e+/3v62JV8z1rcx2DQn3j8t1G/SyohhBuStJRpQgULy
Ll9tZn9lJuXQlvLP+8/2lxf+1nCuq61AQtnVATM1Lpy/yYVGANePlYJWuS0V9B2F
U4yW9ZIHFHQKVeTc8SEF6ucb/owtAatpZIOpBybFtxvl/dVJ9LStYfzSvHNDVmna
0FQ4ZJVozVDHgmXKva1gf5dLEeGMzlxbuRpeekF+TQKBgQC2PxQm/v6DVRgvV0Hs
AmhV8yfSr4YSkFdAB8uRFgYZF7947GoV3QlS56njGQn5u2Lp9MzxJbzXp+jdhfqR
1U2k+eUOzVk0HMQSImwZQVPTNC6e009+HiEmyXz1o9CLgXm8pKxjk1lFPXnncB7N
fVu5hhr6FWCG4e1ISV7a6kye1QKBgQD6cFS/Ze7ctKICKYOigo7xAk6q2Zx4JEjg
OzRxYZeSNFg4ogPGGx9HD39UPYKzX5Xk/iqLbMq+j2dL75L8ww7CI2h91MphO9gE
m0UOTDmqnKK2jrHw3MhoD6sXMOCGQnc7s8ZXGlHoJpPbqqd3aiJvb6Vs91apdmfO
KQMX0PtNfwKBgDsOY8RjOyxpxcWJfBYzjYXUnqH6OPMJDQz1ubSRM3asKGLSEWp2
TxAre/TYZ1AiteHkbwjx1qj3g1FNmi3pthhw1hYe2vo1HCBYQTlJ3xUAwt660Pao
YsvD3RdodyrN0RodLrOxyurSCg/CWGj0Z2XOHC3QAZCT46VaCT/dTujlAoGBALNB
Rhe9YUxOaou7pUHjy2aMrTwzCIEiD5uYJQBmxzPaDa9zn9njve6CFDR61puHdmXy
2wby9ueRA3Hh6EbNYznoWDmA3t7cE9GwRaxnOPt6pCihWJI7paJ+XIr77CmNV4S/
N99OsoPFYR3hN38M09sJgdHN9BTV8JUq29DnP4kHAoGBAIK1ZtOiwy7r+hb+ZxQT
ga7450qmgsse9JRESJBvMcIxO3NtRnaDdkvbSNiJLsZH6Dv9q9YK39ooejeSM9Tn
qFFEuyn4iebZd8Zyq88/grJrKCkLAYEaSV8ROWG4pTjkBJaKAv3LVSuc/1+rBsCJ
HLSIvLOXS06J2ApCdo4gYhK6
-----END PRIVATE KEY-----
</key>

<ca>
-----BEGIN CERTIFICATE-----
MIIDTjCCAjagAwIBAgIUe1XrByi3szbCI9w0fVRF/6ytsFUwDQYJKoZIhvcNAQEL
BQAwFjEUMBIGA1UEAwwLRWFzeS1SU0EgQ0EwHhcNMjYwNTAzMTg0OTU4WhcNMzYw
NDMwMTg0OTU4WjAWMRQwEgYDVQQDDAtFYXN5LVJTQSBDQTCCASIwDQYJKoZIhvcN
AQEBBQADggEPADCCAQoCggEBANQK58T7co4lL4H6fRNE3aL4ILzm0qMVjrWFUGpD
IhTznFs67MZLkmfMWIWtPfwnRQaRGmSVisV0RdyxqXifYME5UVT+vHr8nQG0Vc42
8w38X7Wr88RLZ57DJHQp4E9qUUbrp79Mq90qn3KyeNhToKRYx9VkeT3DEb3cM7OP
/4nKwLXpaLzlRcyeMV3r+yIzmfmCuR4Y+daGL/hHciQb+9Qon2oVm95uEfVgFaXS
Jr45ID1aJjhGvaFw5muLyw0QijUA/l8Pt+LCkaf/Rb+XdAyqourpfvXHiCTnuK6J
bSs38Rf0tLxvC5Rx6yGh292mzajyaZ2DrfP14uxZuSYl3dkCAwEAAaOBkzCBkDAP
BgNVHRMBAf8EBTADAQH/MB0GA1UdDgQWBBT+ugM6hPjmSDw09BJzXhotfFnziDBR
BgNVHSMESjBIgBT+ugM6hPjmSDw09BJzXhotfFnziKEapBgwFjEUMBIGA1UEAwwL
RWFzeS1SU0EgQ0GCFHtV6wcot7M2wiPcNH1URf+srbBVMAsGA1UdDwQEAwIBBjAN
BgkqhkiG9w0BAQsFAAOCAQEAYtj9Fx9lvleo0rQ2ZMfrSiV90Zh+WDg/oQthwCL2
xD2D/busE9uROgzq4mi4Waf70nBDZb8IJpPwAIYLcbypqIP82qkrOeb1Ku62BHJ3
XtlCqAwQigEJ8YqDgKWrM/3wxKQuF2q+27pyo7dnlzkLf4Wr0y8Ar4Ua1Mn4Bmee
TOdo3n4IJLCea5OUcmsJ6b+dfZbtGQVX4Tn9kkRVUE+W/eLlXYOqb6WE4za5LFqk
29qsp2ldxqj6TXb27oDp5GG+o6CnXQFBQl8SLWA1kPq8ylFdftjPNZpkqQgYBLPq
vElxd0efCkS0XRqCK8yjuZbrKmjaUkYNXZ88sYWO1Na71Q==
-----END CERTIFICATE-----
</ca>

<tls-crypt>
-----BEGIN OpenVPN Static key V1-----
f545a679cfa9163f7c864e2eb9a14dbf
6f95004b8ef4a1728d803a7e748b2386
43c16b3ad419cd0af9a10216bcc7a1fe
678439d1ef5f7b97d46d21a750b2fe59
ca5b0d51dfea15a4302eef0982e78e32
b2b3940e9b96f6b1ba5f8ceb47bcad77
fdba747b6cb524a25ad655a2ebe2b2f6
f08b707e3af09bb564203457508aad05
5f6bd046de2fc03b2cb912a27826e1a3
69704eefee50a5dbe4bcf7bc3c3f9793
b4d0463d10a8403d71a3fe20409f82a9
38d8079481b120df02dff9c6a116809f
210ee2cc3aa4d4873236420dcc745f1c
4ce92c4bfd118099a23297fb2844a0e2
f3dc1d1d50862506baf2a4aba64d8019
d408bc2b11a051d99aca77a501253c69
-----END OpenVPN Static key V1-----
</tls-crypt>
