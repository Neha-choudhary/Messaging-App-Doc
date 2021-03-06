# Technologies Used

The Backend process of [React Native Messaging App](http://market.nativebase.io/view/react-native-messaging-app-with-backend) Backend are built using the core components of Node, Express, MongoDB, SocketIO. The theme has also been constantly incorporating various other latest technologies.

* Feathers JS

* MongoDB

* SocketIO

* Mocha

* Chai

### [Feathers JS](http://feathersjs.com/):

[Feathers](http://feathersjs.com/) is a minimalist, service-oriented, real-time web framework for modern applications that puts real-time communication at the forefront rather than as an afterthought.Built on top ofExpress, [Feathers](http://feathersjs.com/) has embodied the same spirit. It is comprised of a bunch of small modules that are all completely optional and the core weighs in at just a few hundred lines of code.Most real-time\* web frameworks only allow clients to be pushed data in real time. You interact with your server over REST and then receive events over websockets or, even worse, the client polls for changes \(which isn't really real-time\).

[Feathers](http://feathersjs.com/) is different. [Feathers](http://feathersjs.com/) allows you to send and receive data over websockets, bringing real-time to the forefront and making your apps incredibly snappy.

The whole [Feathers](http://feathersjs.com/) ecosystem has been modeled around supporting real-time communication and making it a first class citizen instead of a hacky add-on. You can even forgo REST altogether and simply use websockets to communicate with your app, making it ideal for real-time IoT devices, among other things.

### [MongoDB](https://www.mongodb.com/):

[MongoDB](https://www.mongodb.com/) is a document-oriented database designed with both scalability and developer agility in mind. [MongoDB](https://www.mongodb.com/)'s ability to store JavaScript objects natively saves time and processing power. Rather than storing your data in tables and rows as you would with a relational database, in [MongoDB](https://www.mongodb.com/) you store JSON-like documents with dynamic schemas. Instead of a domain-specific language like SQL, MongoDB utilizes a simple JavaScript interface for querying. Looking up a document is as simple as passing a JavaScript object that partially describes the search target.

###  [SocketIO](http://socket.io/)

[Socket.IO](http://socket.io/) is an event-based bi-directional communication layer for realtime web applications. It abstracts many transports, including AJAX long-polling and WebSockets, into a single API. It allows developers to send and receive data without worrying about cross-browser compatibility.  
[Socket.IO](http://socket.io/) provides both server-side and client-side components with similar APIs.

* On the server-side, [Socket.IO](http://socket.io/) works by adding event listeners to an instance of
  `http.Server`
  .
* The HTTP server will begin to serve the client library at
  `/socket.io/socket.io.js`

Since both the server and client's Socket object act as  **EventEmitters **, you can emit and listen for events in a bi-directional manner.
