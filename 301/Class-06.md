Api

**_API_** stands for application programming interface—a set of definitions and protocols to build and integrate application software.

**API Keys** - to limit the use

**HTTP API Client** - a server to hold API's, like Postman.

**Axios** - a library to query an API-

---

API run on Query Parameters
Key- pokemon - pk.26abc9dd5ee16aed89fcba4ccb797fb6
q - freeform query string to search for Commas are optional but improves perfromance.

---

async code to call the code
'res' = result (API call)

First you have to declare the function as ASYNC

```
async function getLocation(){ //run function
const API = 'http link' 'get api'
const res =await axios.get(API); //call api with axios'
console.log(res) // uses res, but wont run until 'await has ran'
}
```

After this point we will have called alot of data. Which is an array of objects.
Note;
**(status: 200)- it has worked **

code to search for a specific place, using location and display name.
inputing a button so that when clicks we 'get data'

```
import "./App.css";
import axios from "axios";
import { useState } from "react";

function App() {
  const [location, setlocation] = useState({});

  async function getLocation() {
    const API = https://us1.locationiq.com/v1/search.php?key=pk.57e7e72c81dea4916ec31515a0edd22&q=liverpool&format=json;
    const res = await axios.get(API);
    setlocation(res.data[0]);
  }
  return (
    <div className="App">
      {location.display_name && (
        <p>
          {location.display_name} Is at lat and lon: {location.lat} /
          {location.lon}
        </p>
      )}
      <button onClick={getLocation}>Get Data</button>
    </div>
  );
}

export default App;
```
