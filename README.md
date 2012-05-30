movie-times-yql
===============

A YQL parser for getting movie times through Fandango. Test it out at http://developer.yahoo.com/yql/console/

Here's an example of the data returned for zipcode="94109" and date="5/30/2012"

```json
{
 "query": {
  "count": 1,
  "created": "2012-05-30T05:11:57Z",
  "lang": "en-US",
  "results": {
   "fandango": {
    "src": "http://www.fandango.com/94109_movietimes?date=5/30/2012",
    "theaters": [
     {
      "id": "AMC Van Ness 14",
      "name": "AMC Van Ness 14",
      "address": "1000 Van Ness Avenue, San Francisco, CA 94109",
      "onlinetickets": "true",
      "movies": [
       {
        "id": "Chernobyl Diaries",
        "title": "Chernobyl Diaries",
        "rating": "R, 1 hr 26 min",
        "runtime": "undefined",
        "times": [
         {
          "clock": "11:05a",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574784amp;mid=152960amp;tid=AAGBK"
         },
         {
          "clock": "10:15p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574838amp;mid=152960amp;tid=AAGBK"
         }
        ]
       },
       {
        "id": "Men in Black III",
        "title": "Men in Black III",
        "rating": "PG-13, 1 hr 44 min",
        "runtime": "undefined",
        "times": [
         {
          "clock": "11:00a",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574781amp;mid=135737amp;tid=AAGBK"
         },
         {
          "clock": "8:15p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574832amp;mid=135737amp;tid=AAGBK"
         },
         {
          "clock": "10:50p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574845amp;mid=135737amp;tid=AAGBK"
         }
        ]
       }
      ]
     }
    ]
   }
  }
 }
}
```

Available for anyone to use under the MIT License.