---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc communications calls participants start-hold-music post --call-id {call-id} --participant-id {participant-id} --body '{\
  "customPrompt": {\
    "@odata.type": "#microsoft.graph.mediaPrompt",\
    "mediaInfo": {\
      "@odata.type": "#microsoft.graph.mediaInfo",\
      "uri": "https://bot.contoso.com/onHold.wav",\
    },\
  },\
  "clientContext": "d45324c1-fcb5-430a-902c-f20af696537c",\
}\
'

```