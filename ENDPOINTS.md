# Endpoints

Comment: 
 - The RequestBody is displayed as raw data. So propably not readable
 - As I have no idea if the Google API key is per user or global It isn't in here. 
 - Mitmproxy is currently not able to do all HTTP2.0 stuff thats why these are only the Requests.

## Send
### Text Messages
Usage: sending Text Messages

URL: PUT https://instantmessaging-pa.googleapis.com/google.internal.communications.instantmessaging.v1.IM/SendMessage HTTP/2.0

RequestHeaders:
```
:authority:            instantmessaging-pa.googleapis.com
user-agent:            FB/1/20018674 grpc-java-cronet/0.0
content-type:          application/grpc
te:                    trailers
x-client-data:         COzijQk=
x-goog-api-key:        GOOGLEAPIKEY_WOULD_BE_HERE
grpc-accept-encoding:  gzip
grpc-census-bin:
grpc-timeout:          599999m
```

RequestBody: 
```
\x00\x00\x00\x00\x9d
\x15\x08\x01\x12
HERE_WOULD_BE_MY_PHONE_NUMBER\x1a\x02FB\x125
$4bd30ffb-3155-46bd-87cc-f2c447431efa\x10\x02(\x02b?\xa2\x06\x06\x08?J\x02\x08\x01\x1aM2.\x00V\xaa\xdbVz#\xa5}Q\xc9\xa4\xd9'.%\xd6.UI\xfcJ\xa9(\xfd\xe5\xe8-?\xfb=\xd6\xfe\xc5\xcb<\x0cN\xba=
p\xe7a\x98\x9c\x1e:?\x18\xf2\xeb\xc5?8\x04H\x01J\x10xW\x1d\xe5\x9b\xe9I\x81\x8cd\x93\x128\xd7-G
```

### GetBotList
Usage: Unknown

URL: PUT https://instantmessaging-pa.googleapis.com/google.internal.communications.instantmessaging.v1.IM/GetBotList HTTP/2.0

RequestHeaders:
```
:authority:            instantmessaging-pa.googleapis.com
user-agent:            FB/1/20018674 grpc-java-cronet/0.0
content-type:          application/grpc
te:                    trailers
x-client-data:         COzijQk=
x-goog-api-key:        GOOGLEAPIKEY_WOULD_BE_HERE
grpc-accept-encoding:  gzip
grpc-census-bin:
grpc-timeout:          599999m
```

RequestBody:
```
\x00\x00\x00\x00\xe6
M2.\x00V\xaa\xdbVz#\xa5}Q\xc9\xa4\xd9'.%\xd6.UI\xfcJ\xa9(\xfd\xe5\xe8-?\xfb=\xd6\xfe\xc5\xcb<\x0cN\xba=p\xe7a\x98\x9c\x1e:?\x18\xf2\xeb\xc5?8\x04H\x01J\x10}\x05\xb9bLDB\x1d\xbc\x92\x8dvl\xcf.J\x1a\x94\x01
\x8b\x01ya29.CmLHA-RPH5vBrETnpbW1X7r3_Phq9ckhuvS4gzHvXtdlkDim8aoifYn7vrumNXZZlcHfLk_pe4ziBbpEpDGnWL2EJSp-or5mvueE-ZDzQ-_ARK95NUF49LY4uqlidhj7N6gR_w\x12\x04prod
```

## Remove
### Remove Text

Usage: Removing Text Messages

URL: PUT https://instantmessaging-pa.googleapis.com/google.internal.communications.instantmessaging.v1.IM/DeleteUserMessages HTTP/2.0

RequestHeaders:
```
:authority:            instantmessaging-pa.googleapis.com
user-agent:            FB/1/20018674 grpc-java-cronet/0.0
content-type:          application/grpc
te:                    trailers
x-client-data:         COzijQk=
x-goog-api-key:        GOOGLEAPIKEY_WOULD_BE_HERE
grpc-accept-encoding:  gzip
grpc-census-bin:
grpc-timeout:          599999m
```

RequestBody:
```
\x00\x00\x00\x00w
M2.\x00V\xaa\xdbVz#\xa5}Q\xc9\xa4\xd9'.%\xd6.UI\xfcJ\xa9(\xfd\xe5\xe8-?\xfb=\xd6\xfe\xc5\xcb<\x0cN\xba=p\xe7a\x98\x9c\x1e:?\x18\xf2\xeb\xc5?8\x04H\x01J\x10 \xbe\x97VN2H\xae\x95:\xf9\xea\xc4\x18\xa3b\x12&
$c4025afe-b725-48e3-a12a-70626e81abc6
```

# Stickers
Usage: Propably get Stickers

URL: GET https://www.gstatic.com/allo/stickers/current_version HTTP/2.0

RequestHeaders:
```
:authority:         www.gstatic.com
user-agent:         com.google.android.apps.fireball/20018674 (Linux; U; Android 6.0.1; de_DE; A0001; Build/MOB31K; Cronet/56.0.2913.4)
accept-encoding:    gzip, deflate
if-modified-since:  Fri, 09 Dec 2016 13:45:00 GMT
```
