# Async

Debugging using chrome console

    + Using Fetch/ XHR will highlight the specific request we make to an api
    + FETCH to send a request to the designated endpoint
    + TRY Catch are great to testing network request.


    ====


- await is good to use when waiting for a promise to complete




============
Week 4 Thursday 

+ Creating a seperate service for axios 

writing in service: 
    export const NasaApi = new axios.create({
        baseURL:'https://api.nasa.gov',
        timeout:800
    })

 TA Recommeds we start with controller 

============

 # Map & ForEach Defined
Let’s first take a look at the definitions on MDN:

forEach() — executes a provided function once for each array element.
map() — creates a new array with the results of calling a provided function on every element in the calling array.
            - use when handling multiple data 

==============
# CallBack Insight
-Nothing special for javasript but implies a function where handling a result takes some time 
-