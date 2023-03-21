# AirFlights
AirFlights 

JOURNEYS
http://localhost:64452/api/Journeys/12121

RESPUESTA FAIL:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.4",
  "title": "Not Found",
  "status": 404,
  "traceId": "00-b5d3eab96abf7642b4e7b496129193ce-edd6cbfe04188b49-00"
}

SUCCESS
http://localhost:64452/api/Journeys/9020

{
  "flights": [
    {
      "transport": {
        "flightCarrier": "AV",
        "flightNumber": "9020"
      },
      "origin": "New York",
      "destination": "Los Angeles",
      "price": 800
    },
    {
      "transport": {
        "flightCarrier": "CO",
        "flightNumber": "7050"
      },
      "origin": "Los Angeles",
      "destination": "New York",
      "price": 800
    }
  ],
  "origin": "New York",
  "destination": "Los Angeles",
  "price": 800
}
