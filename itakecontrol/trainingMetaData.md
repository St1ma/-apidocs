# TRAINING META DATA
--------------------

## Request

    POST https://sarepta-api-dev.nof1health.com/participant/trainingData/subject-id

```javascript

    {
        headers: {
            "Content-Type"  : "application/x-www-form-urlencoded; charset=utf-8",
            "Authorization" : "Bearer n3N0wlxpk6hzJLgn18C7Q2BaGqi0JYHp"
        },
        body: {
            "subjectId"       : "001-001",  // Subject ID of selected child
            "choiseActivity"  : "Soccer",   // Name of Choice assessment
            "walkingLocation" : "Home",     // Location for Walking (Front View and Side View) and Standing assesment
            "stairsLocation"  : "Home",     // Location for Stairs assesment
            "choiceLocation"  : "School"    // Location for Choice assesment
        }
    }

```

## Response

```javascript

    {
        "status": "1" // for successfully updated info
    }

```