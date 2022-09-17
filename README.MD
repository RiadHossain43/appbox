# APPBOX

The process assumes you already have `git`, `node.js` and `yarn` installed in you local machine.

### Clone Project

Go to your suitable project directory in your machine and run the following command

```shell
git clone git@github.com:RiadHossain43/appbox.git
```

or if you are using `https`

```shell
git clone https://github.com/RiadHossain43/appbox.git
```

Now change your working directory to **appbox**

```shell
cd appbox
```

### Intialise lerna

Run the folling command

```shell
npm install
```

or

```shell
yarn install
```

To initialise `lerna` run the following commands

```shell
npx learna@latest init
```

To bootstrap all the packages run folloing command

```shell
npx learna bootstrap --hoist
```

`--hoist` flag will hoist all your lerna dependency in the root of the project.
