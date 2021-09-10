# Shopping Cart 2

## Description
This exercise demonstrates pulling data from a back end database to restock items. Clicking on an item will add it to the cart. Clicking on the item in the cart will trigger an accordion dropdown. Clicking on the dropdown will remove it from the cart. The stock numbers of the items are kept track of on the left and the total purchase price is kept track of on the right. Bellow is a field for a URL used to connect to a Strapi database. If a successful connection is made, new products will be added to the list on the left.

## How To Run
This exercise can be run by forking the repository and cloning it to your machine. If you don't have npm installed, you can get it by installing [node.js](https://nodejs.org/en/download/). Run 'npx http-server' from the command line to run a temporary http-server or install http-server as a global command by running 'npm install --global http-server' (https://www.npmjs.com/package/http-server). Run 'http-server' to start a server. Run 'http-server -c-1' to prevent the browser from caching if you want to make changes. You can then access the page by going to localhost:8080 in your web browser.

In order to use the restocking functionality, you’ll need to install [Strapi](https://strapi.io/documentation/developer-docs/latest/getting-started/quick-start.html#_1-install-strapi-and-create-a-new-project). Create a database named “products” with four fields – name (text), country (text), cost (number), and instock (number). The default URL “http://localhost:1337/products” can be used to restock the products list.

## Future Improvements
Restocking by adding to the quantities of items that are already in the products list instead of adding new rows for like products.

## MIT License
Copyright (c) 2021 Russell Propert

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

