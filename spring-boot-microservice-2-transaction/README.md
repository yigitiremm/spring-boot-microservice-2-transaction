## Spring Boot Microservice 2 - Transaction Service

### Endpoints

#### 1- Save Transaction 

'''
POST /api/transaction HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
Content-Type: application/json
Cookie: JSESSIONID=8F3B499909A2E8B9CEC02DF50EEC99AD
Content-Length: 40

{
"userId":1,
"productId":1
}
'''


#### 2- GET Transactions of User

'''
GET /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
'''

#### 3- DELETE Transactions By Id

'''
DELETE /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
'''

