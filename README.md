# Key Invest Project Stub
This is the repository for the KI Project Stub.

## How to use?
1. Clone the repository:
```bash
 git clone https://github.com/iamDrachir/kiStub.git
```

2. Go to kiStub folder; then run the below java command:
```bash
 java -jar wiremock-standalone-3.10.0.jar --admin-api-basic-auth Loftus:Loftus123
```

3. Test the available mocks:
```
curl --user Loftus:Loftus123 http://localhost:8080/__admin/mappings   
```
