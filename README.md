# katalon-finalapi-nabilahalmiraizzati

GITHUB
Create new repository
Integration Github with Katalon
Create new branch

KATALON
Create Global Variable dengan variable mainURL to generate website https://restful-booker.herokuapp.com

Create new object repository Web Service Request for POST CreateToken
Input URL pada repo CreateToken -> ${GlobalVariable.mainURL}/auth
RUN repository dengan response 200
Get Token
Create new test case CreateToken

Create new object repository Web Service Request for GetBookingIds
Input URL pada repo POST -> ${GlobalVariable.mainURL}/booking
RUN repository dengan response 200
Create new test case BookingIds

Create new object repository Web Service Request for GetBooking
Input URL pada repo DELETE -> ${GlobalVariable.mainURL}/booking/4
RUN repository dengan response 200
Create new test case GetBooking

Create new object repository Web Service Request for CreateBooking
Input URL pada repo DELETE -> ${GlobalVariable.mainURL}/booking
RUN repository dengan response 200
Create new test case CreateBooking

Create new object repository Web Service Request for UpdateBooking
Input URL pada repo DELETE -> ${GlobalVariable.mainURL}/booking/4
RUN repository dengan response 200
Create new test case UpdateBooking

Create new object repository Web Service Request for ParsialUpdateBooking
Input URL pada repo DELETE -> ${GlobalVariable.mainURL}/booking/4
RUN repository dengan response 200
Create new test case ParsialUpdateBooking

Create new object repository Web Service Request for DeleteBooking
Input URL pada repo DELETE -> ${GlobalVariable.mainURL}/booking/4
RUN repository dengan response 201
Create new test case DeleteBooking

Create new object repository Web Service Request for PING
Input URL pada repo DELETE -> ${GlobalVariable.mainURL}/ping
RUN repository dengan response 200

Create Test Suite AllEndpoint
Run Test Suite AllEndpoint

Commit n Push
Edit README
Create PullReq
Merge
