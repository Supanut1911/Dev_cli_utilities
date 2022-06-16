## Create NEXTjs TS app (framework)

```
npx create-next-app@latest --ts
```

---

## Create NESTjs TS app (framework)

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

## Create Hardhat

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
