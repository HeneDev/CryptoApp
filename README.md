# CryptoApp

A wep app i made for practice using ReactJS and Redux + Redux Toolkit. Coin information provided by Coinranking and Cryptonews by Bing News Search

## Screenshots

**Homepage view**
  <p align="right">
    <img width="1028" height="702" src="https://github.com/HeneDev/CryptoApp/blob/master/images/Home.PNG">
  </p>
  ![Homepage view](/images/Home.png)
  
  **Cryptocurrencies view**
  <p align="right">
    <img width="1028" height="702" src="https://github.com/HeneDev/CryptoApp/blob/master/images/Cryptocurrencies.PNG">
  </p>
  
   **Detailed view of a single cryptocurrency**
  <p align="right">
    <img width="1028" height="702" src="https://github.com/HeneDev/CryptoApp/blob/master/images/Cryptodetails.PNG">
  </p>
  
   **Detailed view of a single cryptocurrency**
  <p align="right">
    <img width="1028" height="702" src="https://github.com/HeneDev/CryptoApp/blob/master/images/Cryptodetails(1).PNG">
  </p>
  
   **Exchanges websites view**
  <p align="right">
    <img width="1028" height="702" src="https://github.com/HeneDev/CryptoApp/blob/master/images/Exchanges.PNG">
  </p>

   **Cryptocurrency related news view**
  <p align="right">
    <img width="1028" height="702" src="https://github.com/HeneDev/CryptoApp/blob/master/images/News.PNG">
  </p>

### Installation

#### Requirements:

- npm
- coinranking api key
- bing news search api key

#### Cloning repository and changing directory:

```
$ git clone git@github.com:HeneDev/CryptoApp.git
cd CryptoApp
```

#### Inside the CryptoApp folder open the terminal and install all the dependencies by the following command:

```
npm i
```

#### Inside the root directory create an .env file and inside put in the following environment variables:

```
REACT_APP_CRYPTO_KEY=<Your coinranking key>
REACT_APP_BASE_NEWS_URL=<Your bing news search key>
REACT_APP_BASE_URL=https://coinranking1.p.rapidapi.com
REACT_APP_NEWS_RAPIDAPI_HOST=bing-news-search1.p.rapidapi.com
REACT_APP_CRYPTO_RAPIDAPI_HOST=coinranking1.p.rapidapi.com
```

#### Running the application

- **Inside the CryptoApp directory, run the command**

```
npm start
```
