---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc communications calls record-response post --call-id {call-id} --body '{\
  "bargeInAllowed": true,\
  "clientContext": "d45324c1-fcb5-430a-902c-f20af696537c",\
  "prompts": [\
    {\
      "@odata.type": "#microsoft.graph.mediaPrompt",\
      "mediaInfo": {\
        "uri": "https://cdn.contoso.com/beep.wav",\
        "resourceId": "1D6DE2D4-CD51-4309-8DAA-70768651088E"\
      }\
    }\
  ],\
  "maxRecordDurationInSeconds": 10,\
  "initialSilenceTimeoutInSeconds": 5,\
  "maxSilenceTimeoutInSeconds": 2,\
  "playBeep": true,\
  "stopTones": [ "#", "1", "*" ]\
}\
'

```