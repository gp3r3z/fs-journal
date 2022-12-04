# Node

Mongoos works as ORM

- Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

- Middleware provides an additonal layer ex: authorization, Helmet, and body-parser.
  Helmet - sensors sensitive data
  Bodyparser - parses body to a JSON string.

- esLint provides a format for code. This allows multiple users to keep the same format.

- Node syntax
  --> super specifies the door / endpoint for entry
  --> .use to use middle-ware ex authorization
  --> next provides a way for the data to been done to the next request or response
  ---> generally seen with errors or middleware
  ---> every request will need a request, response, and next

OTHER
  --> extends - allows class inheritance which allows additional functionality for a x module

--> Super is a another form of a constructor typically on an extends


Additonal Tools 
logger from utils logger.log() will show errors in the debug console. 