# Header Parser Microservice
Node.js API that returns client information such as IPAddress, Preferred Language and Software information.

*FCC - Back End Development and APIs Projects #2*
## Getting started
1. Clone the repository:
```bash
git clone https://github.com/jlopezestrada/HeaderParser-Microservice.git
```
2. Install the dependencies:
```bash
npm install
```
3. Start the server:
```
npm start
```
## Usage
Go to /api/whoami endpoint:
```bash
/api/whoami
```
The server will respond with a JSON object containing client information (IPAddress, Preferred Language and Software information):
```json
{
  "ipaddress": "::ffff:127.0.0.1",
  "language": "en",
  "software": "Mozilla/x.0 (Windows NT xx.0; Win64; x64; rv:xx.0) Gecko/20100101 Firefox/xx.0"
}
```
