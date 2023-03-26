![Crypto](https://tse4.mm.bing.net/th?id=OIP.cqoaUyIKryQpISKXkC2fLwHaFj&pid=Api&P=0)

### This is a single-page app track the price of coins from [coingecko](www.coingecko.com).


#### Getting start the project.
```react
To create the project npx create-react-app crypto
To start the project npm start
```
- Use [http:localhost:3000](http://localhost:3000) to open it in browser.

## Dependencies
- axios
```Javascript
 const [coins,setCoins] = useState([]);
   useEffect (() => {
  axios.get(url) .then((response) => {
    setCoins(response.data)
    console.log(response.data[0])
  }).catch((error) => {
    console.log(error);
  })
}, [])
```
## Technology
React.js

## Deploy on github
The easiest way to deploy your react.js app is to use the [github](github.com).

Check out our [github documentation](https://docs.github.com/en) for more details.






