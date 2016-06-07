FORMAT: 1A

# InboxApi

Some API Calls, for using the Inbox Data

# Group Inbox

## URL [/api/inbox/received]

### Get all Inbox Data [GET]

+ Response 200 (application/json)

    [
      {
          "title": "May 2nd",
          "items":[
              {
                  "name":"Your have new entry in the address book"
              },
              {
                  "name":"Personal Details have changed"
              },
              {
                "name":"Your have new entry in the address book"
              },
              {
                  "name":"Your have new entry in the address book"
              },
              {
                  "name":"Personal Details have changed"
              },
              {
                "name":"You've logged in in a new Computer on Firefox"
              },
              {
                  "name":"You've logged in in a new Computer on Firefox"
              },
              {
                  "name":"You've logged in in a new iOS Device"
              },
              {
                "name":"You've logged in in a new Computer on Browser Firefox"
              }
          ]
      },
      {
          "title": "May 1st",
          "items":[
              {
                  "name":"Personal Details have changed"
              },
              {
                  "name":"You've logged in in a Android Device"
              }]
      }
    ]
