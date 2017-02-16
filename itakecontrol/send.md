# SCHEDULE REQUEST
------------------

## Request

    GET https://sarepta-api-dev.nof1health.com/participant/subjectsSchedules

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

    {
        "001-001" : [
            { status: "COMPLETE", startedAt: "18 FEB 2017", endAt: "20 FEB 2017", activities: [] },
            { status: "INCOMPLETE", startedAt: "18 MAR 2017", endAt: "20 MAR 2017", activities: [] },
            {
                status: "OPEN",
                startedAt: "18 APR 2017",
                endAt: "20 APR 2017",
                activities: [
                    { label: "Run", status: "COMPLETE" },
                    { label: "Walking", status: "SKIP", reason: "ILLNESS" },
                    { label: "Stairs", status: "UPCOMING" }
                ]
            },
            { status: "UPCOMING", startedAt: "18 MAY 2017", endAt: "20 MAY 2017", activities: [] }
        ],
        "001-002" : [
            { status: "COMPLETE", startedAt: "18 FEB 2017", endAt: "20 FEB 2017", activities: [] },
            { status: "INCOMPLETE", startedAt: "18 MAR 2017", endAt: "20 MAR 2017", activities: [] },
            { status: "UPCOMING", startedAt: "18 APR 2017", endAt: "20 APR 2017", activities: [] }
        ]
    }

```