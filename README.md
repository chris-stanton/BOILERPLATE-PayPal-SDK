
# PayPal SDK Boilerplate


## Description:
###### PayPal SDK Boilerplate using EJS framework


## Technologies Used
  1. Node.js
  2. EJS
  3. Express.js
  4. PayPal SDK
  7. GIT / GitHub


## Install App
  1. Download zip file or ``git clone`` repo
  2. Open terminal or equivalent and navigate into folder
  3. Create Developer Account with Paypal
  4. Create projected in the Developer Dashboard
  5. Update app.js

    ``paypal.configure({
        'mode': 'sandbox',
        'client_id': 'YOUR_INFO',
        'client_secret': 'YOUR_INFO'
      });
    ``

    with YOUR credentials
  6. Run commands:
    - `` npm install `` Installs Node dependencies from package.json
    - ``` npm start ``` Starts server
    - ``` npm test ``` Starts server using Nodemon
  7. Server is listening on port: 5000


## License
##### Copyright 2017 Chris Stanton

###### Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

###### The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

###### THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
