# new2-demo
This is demo for Git &amp; GitHub Class for new2-demo repository.
git clone:
https://github.com/username/repository.git
nikhil.

app.use(express.json());

in string we use lots of method to use easily strings and their types

React.createElemnets("",{},"");

const root = ReactDom.createRoot(document.getElementById());
const Title = () =>{
<h3>{cusins}</h3>
<Restaurent res-name="Mcdonallads"/>
     return ();
}
     we using multiple type of option to taking a data from a back end and cretaed to function and components.
React.createElement("",{},"")

{Title()}
const jsxHead = <p>lorem lipsum to control panel and we use this method and control system</p>

let users = [
  { id: 1, name: 'John Doe' },
  { id: 2, name: 'Jane Doe' }
space has key code: 32
  git config --list
  git add ( . ) to select all the things in a one time

  non primitiva
array
object

cons resData = () => {
return {
<h3>{resData.data.cuisins}</h3>
}
}

npm run build
npm start

react element is nothing but this is java script object.

 example of :object 
 } function with parameter:
  function sayHello(name){
    return `Hello ${name}!`;
  }

  console.log(sayHello(Nikhil));

app.get('/users', (req, res) => {
  res.json(users);
});
switch (color):

let form = document.querySelector("form");
form.addEventListener("submit", function(event){
event.preventDefault();
})
git -force
`JSON.stringify(): Converts a JavaScript value to a JSON string.`


app.get('/users/:id', (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) return res.status(404).send('User not found');
  res.json(user);
});

app.post('/users', (req, res) => {
  const user = { id: users.length + 1, name: req.body.name };
  users.push(user);
  res.status(201).json(user);
});


app.put('/users/:id', (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) return res.status(404).send('User not found');
  user.name = req.body.name;
  res.json(user);
});

  /**
   * Keeps track of the current dispatcher.
   */
  var ReactCurrentDispatcher = {
    /**
     * @internal
     * @type {ReactComponent}
     */
    current: null
  };

  /**
   * Keeps track of the current batch's configuration such as how long an update
   * should suspend for if it needs to.
   */
  var ReactCurrentBatchConfig = {
    transition: null
  };

  res.json(user);
});

app.listen(port, () => {
  console.log(`API listening at http://localhost:${port}`);
});
