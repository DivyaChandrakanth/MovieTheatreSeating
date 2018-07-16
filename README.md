MovieTheatreSeating

The Main aim is to sell the tickets in an order.
You have a few rules that i followed are :



1. Fill as many orders as possible
2. Put parties as close to the front as possible.
3. If there are not enough seats available in the theater to handle a party, tell them "Sorry, we can't handle your
party."
4. Each party must sit in a single row in a single section. If they won't fit, tell them "Call to split party".
Your program must parse a theater layout and a list of ticket requests and produce a list of tickets or explanations in the
same order as the requests.

Tha Sample input is


6 6
3 5 5 3
4 6 6 4
2 8 8 2
6 6
Smith 2
Jones 5
Davis 6
Wilson 100
Johnson 3
Williams 4
Brown 8
Miller 12

Sample output is

Smith Row 1 Section 1
Jones Row 2 Section 2
Davis Row 1 Section 2
Wilson Sorry, we can't handle your party.
Johnson Row 2 Section 1
Williams Row 1 Section 1
Brown Row 4 Section 2
Miller Call to split party.
