FORMAT: 1A

# InboxApi

Some API Calls, for using the Inbox Data

# Group Inbox

## URL [/api/inbox/promos]

### Get all Inbox Data [GET]

+ Response 200 (application/json)

    [
      {
          "title": "May 2nd",
          "items":[
              {
                  "name":"You are eligible for a $50,000 personal loan"
              }
          ]
      },
      {
          "title": "May 1st",
          "items":[
              {
                  "name":"Refer a friend and earn some bonus on your interests"
              }]
      },
      {
          "title": "April 20th",
          "items":[
              {
                  "name":"Use Orange debit card and earn 5% cash back"
              }]
      }
    ]
