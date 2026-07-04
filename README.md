# Media-Query-Basic-Box-and-h1-Practice

-- Here i ahev use the @Media Query for respsonive and moble/app first design. 
-- As demonsttrated here, using very Basic Css and `@Media only screen` to change the layout of the page.


### Extra Wide Monitor View
<img width="717" height="682" alt="image" src="https://github.com/user-attachments/assets/ed59d04f-e051-463b-8917-8f9f909534ca" />

### Default View
<img width="1002" height="676" alt="image" src="https://github.com/user-attachments/assets/6c3e53b8-752a-4947-a1d2-e274107d9197" />


### Tablet View /Ipad Mini 
<img width="912" height="687" alt="image" src="https://github.com/user-attachments/assets/773696f2-adea-452a-bd2b-d8bed841544b" />

### Phone View Galaxy S8+
<img width="807" height="696" alt="image" src="https://github.com/user-attachments/assets/c432f780-ffc7-43a2-87c6-02ed9415cc26" />


#### snippet of the code
`.container::after {
  content: "default view";
  background-color: aliceblue;
  color: red;
  font-size: large;
  display: flex;
  justify-content: center;
}`

`.box {
  border: 3px solid red;
  border-radius: 20px;
  height: 400px;
  width: 500px;
}`

/* mobile view */
`@media only screen and (min-width: 100px) and (max-width: 499px) {
  .container::after {
    content: "mobile view";
    background-color: greenyellow;
    color: blue;
    font-size: large;
    display: flex;
    text-align: center;
  }
  .box {
    border: 3px solid red;
    border-radius: 20px;
    height: 200px;
    width: 100px;
  }
}`

/* tablet view */
`@media only screen and (min-width: 499px) and (max-width: 799px) {
  .container::after {
    content: "tablet view";
    background-color: pink;
    color: whitesmoke;
    font-size: large;
    display: flex;
    text-align: center;
  }
  .box {
    border: 3px solid red;
    border-radius: 20px;
    height: 200px;
    width: 250px;
  }
}`

/* extra wide monitor view */
/* tablet view */
`@media only screen and (min-width: 1800px) and (max-width: 2500px) {
  .container::after {
    content: "extra wide monitor view";
    background-color: red;
    color: whitesmoke;
    font-size: large;
    display: flex;
    text-align: center;
  }
  .box {
    border: 3px solid black;
    border-radius: 20px;
    height: 500px;
    width: 600px;
  }
}`

