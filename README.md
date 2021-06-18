# To-Do List App

Blockchain To-Do List App powered by Ethereum


## Installing Dependencies

* Git
* Node.JS
* Truffle Framework
* Ganache Personal Blockchain
* Metamask Ethereum Wallet (Google Chrome)


## Installing and Running

---

Run the next commands on Git Bash

``` console
git clone https://github.com/AndresAlcalaGtz/blockchain-todo.git
cd <directory>
npm install
truffle migrate --reset
truffle test
```

---

Start Ganache and make sure that host:port matches with the ones on both truffle-config.js and Metamask

![Ganache host:port](/screenshots/1_ganache_hostport.jpg)
![Configuration host:port](/screenshots/2_configuration_hostport.jpg)
![Metamask host:port](/screenshots/3_metamask_hostport.jpg)

---

Run the next command on Git Bash to start a server with the application

``` console
npm run dev
```

![To-Do List App Starting](/screenshots/4_todo_starting.jpg)

---

Notice the account (upper right section) matches with the one on Ganache

![Ganache Account](/screenshots/5_ganache_account.jpg)

---

Enjoy the To-Do List decentralized application based on blockchain!

![To-Do List App Running](/screenshots/6_todo_running.jpg)

---