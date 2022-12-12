# Vue

Mick's Lecture

- FE now has dependicies
  -- Mostly done in src file
  -- AppState works similar without framework
  -- Services layout mostly the same
- Vue
  -- Component made of up 3 parts - Template - Script - Style

- We will still utilize debug and play to utilize the vite compiler

  - compilers help browsers translate frameworks

- Router View
  - what page are you on and here is the pages you have access too

Mick's tips
first rule of vuew, for the tepmlate to access data in the script must have a return
Second rule, for reactivity to take place, you must use vue's reactive stuff
--> add import ref to the script will add reactivty
--> data established here should only be for data that exists exlusively here

Other methods:
Look at v for

## LifeCycle hooks

    onMounted -> when this component gets loaded to the dom

## Changing the theme

    Utilize data-theme on the body

-- Whats a component in Vue ?

--- Day 2

setup method insight
The code inside is compiled as the content of the component's setup() function. This means that unlike normal <script>, which only executes once when the component is first imported, code inside <script setup> will execute every time an instance of the component is created.

Mick's Start Path

- Client start with model
- Setting up axios service for api request
- then additional service to make call to api
- log the data to verify
- after verifying you can bring data to the component using computed
- using appstate to bring in teh new data using map

getting data from the templat to the scipt then back to html
\*\* mick suggest addding row col then the component to allow the child component to continue the same flow

getting info out of the url using route.params.id ex in movie detailspage from movie api example

Pages are responsibile for getting api data or getting data they rely on displaying
kinda act like a controller
they pass data to components

props don't need to be in the return

Router link is connected to the router page

----- Day 3
o token - auth token from auth0
userinfo also comes from auth0

account is connectd to the db

If a data doesn't need to be manipulated you don't need to create a model (this might save time)

- Mick recommends reactive for forms

reactive better for objects and ref better for single

use unshift to add to begining of list array
use push , to add to end of list

if ever using ref you need to reference the refs.value

props work outside of setup but you will need to pass the props to the setup

MPA vs SPA

- Multi page application
  - classical approach
  - page reloads on all content
  - good for companies with extensive products such as e-commerce

How it works
page is loaded on first visit
changes to content must be done through page refresh

- Single Page application
  - Modern approach
  - does not require page reload
    Add Image

============= Video Section 2
Component structure

- small abstracted pieces of UI
- can be nested
  Elements -> components -> pages

Pages - more complex components

## Compoonent structure

- Template
  - used to hold all HTML
  - code can be injected directly using {{}}
- Script
  - contains all javascript
  - must have default export which contains
    - setup() must return object
      - contains the state and any event hooks such as onMounted()
      - returned object will contain all the available methods and data for the template
      - components{}
        - Nested Components must be imported and added to the object to be usedin HTML
- Style
  - contains all css for component
- How is data passed ?
  - Props
    - data is passed down from parent component to child component
    - Parent passes data as bound attribute
      - <child:data="propData">
    - Captured in child in props property
      - props:['data']
    - can be used directly in template or in setup if passed as first argument
      - setup(props){props.data}

Return object is where methods should be made to make available to html

## Reactive & Computed for drawing !

- Reactive

  - method from vue which utilizes the es2015 proxy objects to watch for changes
  - Reactive is for watching full objects
    - Opposed to ref which is used for watching primitive values

- Computed
  - takes in a function an returns a immutable reactive ref object
  - able to watch reactive objects when changed to a function is re-ran / updated

## State and AppState

- both state and appstate are reactive objects used to manage data
- state is for local component data
  - things that are only needed for that component or any of its nested components
- Appstate is for data shared across multiple components
  - appstate will be manipulated through services not directly by the component

## white board suggestions

string split and int parse
other sources for code practice
Edabit

## Thursday lecture

Jeremy vue approach

Generally when you are v-for you are going to pass a prop to the child component

\*\* Jeremy tip
we can add values from script to scss utilizing back tick tildas

router link can be used to direct to another page

Using the id to load the details
also ensure this is a param for the url to reload the profile

account is whoever is logged in meanwhile profile is to the user signed into the client

this will grab any params out of the router specied in the route of the router file
ex : path:'/profile/:profileId'
route.params.profileId
route -> useRoute()



when to use map
this is a array method so won't work on single objects


Axios is able to attached params via objects 
