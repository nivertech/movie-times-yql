movie-times-yql
===============

A YQL parser for getting movie times through Fandango. Test it out at http://developer.yahoo.com/yql/console/

Here's an example of the data returned for zipcode="02142" and date="5/30/2012"

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
          "clock": "1:15p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574793amp;mid=152960amp;tid=AAGBK"
         },
         {
          "clock": "3:30p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574805amp;mid=152960amp;tid=AAGBK"
         },
         {
          "clock": "5:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574818amp;mid=152960amp;tid=AAGBK"
         },
         {
          "clock": "8:00p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574829amp;mid=152960amp;tid=AAGBK"
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
          "clock": "11:55a",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574789amp;mid=135737amp;tid=AAGBK"
         },
         {
          "clock": "2:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574801amp;mid=135737amp;tid=AAGBK"
         },
         {
          "clock": "5:30p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574817amp;mid=135737amp;tid=AAGBK"
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
       },
       {
        "id": "Men in Black III 3D",
        "title": "Men in Black III 3D",
        "rating": "PG-13, 1 hr 44 min",
        "runtime": "undefined",
        "times": [
         {
          "clock": "11:00a",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574783amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "1:00p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574792amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "1:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574796amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "4:00p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574808amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "4:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574812amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "6:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574821amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "7:30p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574824amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "9:20p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574834amp;mid=147264amp;tid=AAGBK"
         },
         {
          "clock": "10:05p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574837amp;mid=147264amp;tid=AAGBK"
         }
        ]
       },
       {
        "id": "Battleship",
        "title": "Battleship",
        "rating": "PG-13, 2 hr 11 min",
        "runtime": "undefined",
        "times": [
         {
          "clock": "1:50p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574797amp;mid=130096amp;tid=AAGBK"
         },
         {
          "clock": "2:50p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574804amp;mid=130096amp;tid=AAGBK"
         },
         {
          "clock": "4:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574811amp;mid=130096amp;tid=AAGBK"
         },
         {
          "clock": "7:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574827amp;mid=130096amp;tid=AAGBK"
         },
         {
          "clock": "9:30p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574835amp;mid=130096amp;tid=AAGBK"
         },
         {
          "clock": "10:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574843amp;mid=130096amp;tid=AAGBK"
         }
        ]
       },
       {
        "id": "What to Expect When You're Expecting",
        "title": "What to Expect When You're Expecting",
        "rating": "PG-13, 1 hr 50 min",
        "runtime": "undefined",
        "times": [
         {
          "clock": "11:40a",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574788amp;mid=120322amp;tid=AAGBK"
         },
         {
          "clock": "1:55p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574799amp;mid=120322amp;tid=AAGBK"
         },
         {
          "clock": "2:45p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574803amp;mid=120322amp;tid=AAGBK"
         },
         {
          "clock": "5:25p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574816amp;mid=120322amp;tid=AAGBK"
         },
         {
          "clock": "8:05p",
          "buyURL": "https://www.fandango.com/Transaction/Ticketing/ticketboxoffice.aspx?row_count=2551574830amp;mid=120322amp;tid=AAGBK"
         }
        ]
       }
      }
    }
  }
}


Available for anyone to use under the MIT License.