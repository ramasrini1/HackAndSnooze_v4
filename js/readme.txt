
https://hack-or-snooze-v3.herokuapp.com/login
Method: POST
{
  "user": {
    "username": "rs1",
    "password": "tester1"
  }
}

Response
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6InJzMSIsImlhdCI6MTYzNzg3MjEwMX0.pxyL_bBFzy_mjN_l7xat59zTA66cxvQramwL5DRCBqs",
    "user": {
        "createdAt": "2021-11-19T05:03:23.869Z",
        "favorites": [],
        "name": "rama",
        "stories": [
            {
                "author": "Jim Carey",
                "createdAt": "2021-11-25T18:51:31.774Z",
                "storyId": "00eb65af-4585-4d71-957d-42c404621f63",
                "title": "Dumb and Dumb",
                "updatedAt": "2021-11-25T18:51:31.774Z",
                "url": "https://www.google.com/",
                "username": "rs1"
            }
        ],
        "updatedAt": "2021-11-25T18:51:31.776Z",
        "username": "rs1"
    }
}
rs2 tester2

{
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6InJzMiIsImlhdCI6MTYzNzg3NDg1OH0.mHkN3fDcslLWPQYSSAizjwCA5qnx50gFOt3w2Am4-rw",
    "user": {
        "createdAt": "2021-11-25T21:13:59.670Z",
        "favorites": [],
        "name": "Rama2",
        "stories": [],
        "updatedAt": "2021-11-25T21:13:59.670Z",
        "username": "rs2"
    }
}

for rs2 tester2
{
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6InJzMiIsImlhdCI6MTYzNzg3MjU4NH0.Y4GPSuI53SVdQzh5w_Ohsl0Nt8HolK1rnS8NqCzvjtI",
    "user": {
        "createdAt": "2021-11-25T20:35:58.965Z",
        "favorites": [],
        "name": "Rama2",
        "stories": [],
        "updatedAt": "2021-11-25T20:35:58.965Z",
        "username": "rs2"
    }
}

Change user name
https://hack-or-snooze-v3.herokuapp.com/users/rs2

Method Patch
{
 "token":
 "user":{
  "username": "rs3"
}
}

Response
{
    "user": {
        "createdAt": "2021-11-25T21:13:59.670Z",
        "favorites": [],
        "name": "Rama2",
        "stories": [],
        "updatedAt": "2021-11-25T21:18:09.878Z",
        "username": "rs3"
    }
}

Get users
https://hack-or-snooze-v3.herokuapp.com/users?skip=0&limit=10
Method: GET


storyId: f9893f14-5764-4fed-b2b8-b50a21812c7a
Get Story
https://hack-or-snooze-v3.herokuapp.com/stories/storyId
https://hack-or-snooze-v3.herokuapp.com/stories/f9893f14-5764-4fed-b2b8-b50a21812c7a
Method:Get
