## Create NEXTjs TS app (framework) 🏞

![NEXTJS](https://widgetcore.com/wp-content/uploads/2022/01/nextjs.jpg)

```
npx create-next-app@latest --ts
```

---

## Create NESTjs TS app (framework) 🐱

![NESTJS](https://miro.medium.com/max/810/1*8_uUnP2g8H8Zj3N_KktFtw.png)

```
nest new <project-name>
```

NESTjs cli

(order create is important)

- create module

```
nest g mo <serviceName>
```

- create controller

```
nest g co <serviceName>
```

- create service

```
nest g s <serviceName>
```

---

## Create Hardhat 🪖

![HARDHAT](https://hardhat.org/card.jpg)

```
npx hardhat
```

Hardhat Cli

- create local node

```
npx hardhat node
```

- deploy contract (default localhost)

```
npx hardhat run scripts/<"deployContract">
```

- deploy contract with (select network)

```
npx hardhat run scripts/<"deployContract"> --network <"network">
```

---

## Docker 🐳

![docker](https://wallpaperaccess.com/full/2982327.jpg)

image & container

```
  docker buid ...

  docker run ...
```

### compose

!MUST cd to right directory

- Up compose (run in background)

```
docker-compose up -d
```

- Down compose

```
docker-compose down
```
