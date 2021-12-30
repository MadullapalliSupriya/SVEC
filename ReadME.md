###   Front-end Technologies

- HTML
- CSS
- JavaScript
- Booststrap framework
- ReactJS

###  Backend Technologies
- Node.js
       - express.js
       - nodemoon
       - cors
       - dotenv
- PHP
- C#
- Java
- Python

### Databases

- MongoDb
- Mysql
- SQLite
- Firebase
- Postgreessql
- Oracle


+ VCS (Source code Management)
       - Distributed VCS
          - Git, Mercurial
       - Remote(Central) VCS
          - Github, Bitbucket


###   Git

- git init
- git add filename
- git add filename1 filename5 filename100
- git add . or git add --all
- git status
- Do git configurations (set user .name and user .email)
- commit data with commit message

### welcome tosvec

### HTML5

- Hyper Text Markup Language
- Semantic Elements
    - header
    - section
    - article
    - aside
    - footer
    - table

- Block Level Elements
    - h1 to h6
    - paragraph
    - div
    - all semantic elements
    - Text will start from newline

- Inline Elements
    - span
    - img
    - a
    - nav
    - form
    - input
    - textarea
    - legend
    - sup
    - sub
    - ul
    - ol
## Task :
======
- Audio
- Video
- Canvas
- Progress
- Datalist
- Meter
- Select


### CSS
+ Cascading Style Sheets
+ Types of CSS
     - Inline CSS
     - Internal CSS
     - External CSS
+ Syntax of CSS
```
selector {
    css properties
}
```

#### Selectors
+ Simple selectors
     - Universal Selector (*)
     - By Element Name
     - Grouping selector (,)
     - Class Selector
     - Id selector

+ Combinators
     + Desecendent selector ( )
     + Child selector (>)
     + Adjacent sibling selector (+)
     + General sibling selector (~)
+ Pseudo class selector
+ Pseudo element selector
+ Attribute selector



### Box Model

+ margin
+ border
+ padding

      -  padding : 10px (for all adjacent sides)
      -  padding : 10px 30px (10px for top & bottom; 30px for left & ight)
      -  padding : 10px 300px 50px (10px for top; 300px for for left & right; 50px for bottom)
      -  padding : 10px 30px 4px 50px (top,right,bottom,left)
+ width
- 1rem=16px


+ display
   - none
   - inline
   - block
   - inline-block
+ position
   - static
   - relative
   - absolute
   - fixed
   - sticky
+ algin-content
+ algin-items
+ algin-self

#### Responsive Web Design
#### Flex-box

- display
     - flex
        - flex-wrap
        - justify-content
        - flex-direction
        - flex-flow
## Task2:
 - index pagr
 - registration page
 - login page

###  Media Quries

- Extra Small Devices (Mobiles)
     - max-width:600px
- Small Devices (Large Phones)
     - min-width:600px
     - max-width:768px
- Medium Devices (Small Laptops)
     - min-width:768px
- Large Devices (Large Laptops or Desktops)
     - min-width:992px
- Extra Large Devices ()
     - min-width:1200px

```
 @media only screen (max-width:320px) and (max-width:500px{
     CSS Code
 }
```

### Bootstrap 4.6

- It is a CSS framework


## Task3:
      - Navbar with Responsive

- module (Collections of Functions and classes)
- Package (Collections of modules)
- Library (Collection of packages)
- Framework (Collections of library)
    + module --> Package --> Library --> Framework

    + Type of Modes
        - Offline
        - Online
             -CDN links
    
    + background-color -bg
    + text-white

    + Margin in Booststrap (m-* (0-5))
         - 0  --> 0rem
         - 1  --> 0.25rem
         - 2  --> 0.5rem
         - 3  --> 1rem
         - 4  --> 1.5rem           
         - 5  --> 3rem
         - m (margin in all directions)
         - ml-5 (margin-left)
         - mt (margin-top)
         - mb (margin-bottom)
         - mr (margin-right)
         
         - mt (margin-top)
    + padding (padding-left --> p1-5) 

    + colors
         - primary
         - secondary
         - info
         - success
         - warning
         - danger
         - light
         - dark
         - white
         

    + We can use color classes for
         - Buttons (btn btn-primary)
         - text (text-white)
         - background (bg-secondary)
         - alerts (alert alert-primary)
    + Grid System
        - col-sm-12
        - sm (small devices)
        - md (medium devices)
        - lg (large devices)
        - xl (Extra large devices)
        
     + modal
     + Table


####  JavaScript

+ In 1995 `Brenden Eich` introduced JavaScript(ES-262)
+ JavaScript loosely toupled and dynamic language
+ It is a text based programming language and we can use in client-side and server-side(Node.js) for dynamic web applications
- ECMA-Script(European Computer Manufacture Association)(ES-6)
    - let & const
    - map()
    - arrow function
    - classes
    - spread operater
    - rest parameter
+ Datatypes
    - Number
    - BigInt(2^53-1)
    - String
    - Boolean
    - Undefined
    - Null
    - Object
    - Array

+ variables
    - var,let & const
    - Scope
        - function level --> var
        - block level --> let & const
    - Redefine --> var ,let
    - Redeclare --> var
+ `typeof()`
+ Object

```
{
     name:"Hasii"
}
```

+ Array

### Alerts

+ To generate notifications
   - alert
   - prompt(to take input from the user)
   - confirm
+ console statements
   - `console.lo g()`
   - `console.info()`
   - `console.warn()`
   - `console.error()`

+ Spread Operator
    
   - To change array elements from one array to another(swamp)

  ```
    ...variableName

  ```

+ Rest parameter
   + To handle function parameter
```
   ...parameter

```

+ Destructuring of Array & Objects

+ Functions

  - function with functionname
  ```
   function demo(x,y){
         return x+y
   }
   demo()
   ```
   - Anonymous function
   ```
   let demo=function (x,y)
   {
        return x+y
   }
   ```

   - Arrow function
   ```
   let demo= ()=>{
        return x*y
   }
   demo(3,4)
   ```

   + for-in
     - To get index valoes of an array
   + for-of
     - To get elements in an array

   + forEach() --> (ES_5)
   + map() --> (ES-6)
### DOM
   
  - Document Object Model
  - document  
  - history
  - window
  - navigator(PWA-progressive web application)

+ DOM methods
  - `getElementById()`
  - `getElementByClassName()`
  - `querySelector()`
  - `innerText`
  - `textContent`
  - `append`
  - `appendChild`
  - `innerHTML`
  - `setAttribute()`
  - `classList`
  - `style`
  - `src`

#### JSON
+ JavaScript Object Notation
     - To exchange information between application and server

```
{
     "name":"Supriya Madullapalli",
     "salary":"8LPA",
     "designation":"MERN Developer",
     "mobile":18927823 
}
```
+Ajax call or Promises (fetch API) or axios
##### Reference links

  - [github login](https://github.com/)
  - [freeSVG](https://freesvg.org/)
  - [Flation](https://www.flaticon.com/)
  - [html color codes](https://htmlcolorcodes.com/)
  - [webaim(for checking contrast)](https://webaim.org/resources/contrastchecker/)
  - [jsonlint or JSON validate link](https://jsonlint.com/)
  - [ajax call](https://www.w3schools.com/xml/ajax_intro.asp)