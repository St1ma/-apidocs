# LIST VIDEOS FOR CURRENT VISIT
-------------------------------

## Request

    GET https://sarepta-api-dev.nof1health.com/videosByOpenVisit

```javascript

    {
        headers: {
            "Content-Type": "application/x-www-form-urlencoded; charset=utf-8",
            "Authorization": "Bearer n3N0wlxpk6hzJLgn18C7Q2BaGqi0JYHp"
        }
    }

```

## Response

```javascript

    [
        {
          "mediaMetadata": {
            "fileInfo": {
              "id": "979a496b-3900-4711-8a0a-cd54c3a50b8a",
              "mediaFilename": "b6264dea-96f7-493c-9521-8b27e624f663.mov",
              "mediaUrl": "",
              "videoLength": "0.30"
            },
            "participantInfo": {
              "userId": "c32f0eed-85c1-4791-8aa9-79679cc526d2",
              "subjectId": "a3fb7e4b-e21e-48aa-9fd1-62724348e3d5"
            },
            "assessmentInfo": {
              "visitId": "024703e9-fcf0-4229-9255-e9a8a0a0739e",
              "visitSurveyName": "",
              /* other params */
              "skipped": "false",
              "skippedReason": ""
            },
            "deviceInfo": {
              "captured": "true",
              "deviceId": "cd04c413-21b0-4a4f-99c1-0e82fb16ca68"
            }
          }
        },
        {
          "mediaMetadata": {
            "fileInfo": {
              "id": "979a496b-3900-4711-8a0a-cd54c3a50b8b",
              "mediaFilename": "b6264dea-96f7-493c-9521-8b27e624f664.mov",
              "mediaUrl": "",
              "videoLength": "0.30"
            },
            "participantInfo": {
              "userId": "c32f0eed-85c1-4791-8aa9-79679cc526d2",
              "subjectId": "a3fb7e4b-e21e-48aa-9fd1-62724348e3d5"
            },
            "assessmentInfo": {
              "visitId": "024703e9-fcf0-4229-9255-e9a8a0a0739e",
              "visitSurveyName": "",
              /* other params */
              "skipped": "false",
              "skippedReason": ""
            },
            "deviceInfo": {
              "captured": "true",
              "deviceId": "cd04c413-21b0-4a4f-99c1-0e82fb16ca68"
            }
          }
        },
        {
          "mediaMetadata": {
            "fileInfo": {
              /* params for skipped video */
            },
            "participantInfo": {
              "userId": "c32f0eed-85c1-4791-8aa9-79679cc526d2",
              "subjectId": "a3fb7e4b-e21e-48aa-9fd1-62724348e3d5"
            },
            "assessmentInfo": {
              "visitId": "024703e9-fcf0-4229-9255-e9a8a0a0739e",
              "visitSurveyName": "",
              /* other params */
              "skipped": "true",
              "skippedReason": "illness"
            },
            "deviceInfo": {
              "captured": "true",
              "deviceId": "cd04c413-21b0-4a4f-99c1-0e82fb16ca68"
            }
          }
        }
    ]

```