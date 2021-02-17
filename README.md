# Private Blockchain Application

## How to test application functionality?

To test the application I recommend you to use POSTMAN, this tool will help you to make the requests to the API.

1. Run the application using the command `node app.js`
You should see in your terminal a message indicating that the server is listening in port 8000(A warning can appear: 'Buffer() is deprecated due to security and usability issues'):

> Server Listening for port: 8000

2. To make sure the application is working fine and it creates the Genesis Block you can use POSTMAN to request the Genesis block:
    ![Request genesis block](testingImgs/request-genesis.png?raw=true)

3. Make the first request of ownership sending the wallet address:
    ![Request ownership](testingImgs/request-ownership.png?raw=true)

4. Sign the message with the Wallet:
    ![Sign message](testingImgs/signing-message.png?raw=true)

5. Submit the Star
    ![Submit star](testingImgs/submit-star.png?raw=true)

6. Retrieve Stars owned by me
    ![Retrieve stars](testingImgs/retrieve-stars.png?raw=true)