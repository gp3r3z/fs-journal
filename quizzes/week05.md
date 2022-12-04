# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?

<!-- enter you answer in the space below -->

```
The acronym stands for Create, Read, Update, and Delete.
```

**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

<!-- enter you answer in the space below -->

```
    The below hilights how CRUD maps to an HTTP request:
        - Create - utilizes the HTTP Post method
        - Read - utilized with GET
        - Update - utilizes the Http PUT
        - Delete - utilizes HTPP DELETE
```

**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

<!-- enter you answer in the space below -->

```
ORM stands for Object relational mapping and is used to address database interactions.
```

**4.** Which two `HTTP` request types include a body?

<!-- enter you answer in the space below -->

```
The two types of request are POST and PUT.
```

**5.** In a/an **\_\_\_** coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an **\_\_\_** coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run. Fill in the blanks.

<!-- enter you answer in the space below -->

```
 - In a synchronous coding model ..
 - in a asynchronous coding model ..
```

**6.** Fill in the missing piece of this snippet of code.

```js
import ______ from "_______";
let Schema = ________.Schema;
```

<!-- enter you answer in the space below -->

```
import { Schema } from "mongoose ";
let Schema = new Schema;
```

**7.** What is middleware?

<!-- enter you answer in the space below -->

```
Middleware is when software is utilized to communicate for various services via another application like an API.
```

**8.** The **\_\_** pipeline delivers information from the client while the **\_\_** pipeline returns it. Fill in the blanks.

<!-- enter you answer in the space below -->

```
--The Controller pipline...
--The Service piline returns it...
```

**9.**
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

<!-- enter you answer in the space below -->

```
const res = await axios.get('api / winter')

```
