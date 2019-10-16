#### Get a handle an API Basics
 communication between client and server
 API ( Application Programming Interface) --> can communicate between -> Server to Server
                                                                      -> Server to developer(using request and responses)
                                                                      -> Client to Server

#### Identity the advatage of a REST API
    REpresentational
    State
    Transfer
    -REST API provide a standardized way of communicating between client and server
    -Client server communication happen using REST architecture guidelines, using HTTP.
    -REST is only one type of API
# Public - open to any developer who wants to sign up(apps are more targeted towards end consumers)
# Protected - open to select business partners(app target end consumers or business users)
# Private - exposed only to existing developer within the enterprise(app target employees of the enterprise)

# Six key architectureal guidelines to using REST APIs.
# 1: Client-Server Architecture
    -one standered of REST rull called "Seperation between client and server"
    -Client --> developer, browser
    -Server --> Remote computer
    * In here client -> only deal with getting and displaying the information
              Server -> focus on storing and manipulating the data
# 2: Stateless
    -this mean server does not save any of the previous request or responses
# 3: Cacheable
    A cache is simply a way to save data so future requests can be returned faster. When you visit a bunch of websites on your browser, it can save those requests so it can autocomplete the site you want to go to or load the page faster the next time you visit it
# 4: Uniform Interface
     # This interface is like a contract between the client and the service that all REST APIs share.
     # A REST API from one application can communicate in the same way to an entirely different application. This makes communication much easier and more efficient.

# 5: Layered System
    # Create independent components and connect them then easy to replace or update

# 6: Code on Demand (Optional)

# ALtranative API called as SOAP APIs.
    -SOAP - Simple Object Access Protocol
    -Its considered a protocol not an architectural style
    -SOAP is the most popular API before come REST API
    - REST uses HTTP to communicate but SOAP can use multiple means of communication
    - SOAP require more bandwidth and its lead to slower page load times, But REST solve that and its lighter and more flexible.
    -SOAP used in enterprise application (because can add additional layers of security, data privacy, and integrity)
# Some key advantages to REST APIs are:
        Separation between client and server, which helps apps be more scalable. 
        Statelessness, which makes API requests very specific and detail-driven. 
        Cacheable, which lets clients save data so they don't have to constantly query servers.

#### Use REST Resource and Collections

URI - Uniform Ressource Identifiers
Response data languages - JSON, XML
# REST data is represented in resources (like type of object) , group of resources called as collection

# Domain name(www.myapp.com) + URI(/user/34) = Endpoint(www.myapp.com/user/34)

# Quiz 01 Summary

# A REST API is a set of standards developers use when communicating between different components of an application, and between an application and other developers. REST APIs are not a language or a protocol with extra data privacy features (that describes SOAP!).
# Private APIs are used when sending information that you wouldn't want third-party developers outside your company or organization to be able to access. All secure APIs, whether they are public or private, should have encryption and authentication.
# Resources need to represent a thing or an object, so  eating/pizza is out, as isinventory/ilovepizza. Nested resources need to have a logical flow of ordering. For example, pizzas can have topping so  pizza/toppings is OK, but  pizza/icecream is not, because pizzas don't have ice cream in them! 
# Data in JSON is represented in a key-value format. It starts with an opening bracket  {, the  key, a colon  :, the  value, and a closing bracket  }.Lists, or arrays, need to be contained with square brackets  [  ].
# A stateless API means that the server does not keep track of previous requests and responses, which makes each request more purposeful. It's also able to scale and deploy the same APIs to multiple servers. With cacheable data, servers don't have to repeat a request multiple times for the same data. 
