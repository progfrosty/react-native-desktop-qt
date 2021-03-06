:warning::warning::warning:
#### React Native Desktop is under active redesign now. Plese consider documentation as out of date until it is adapted.

---
## Inspecting JS code

### Inspecting code

1) Run js server with `--inspect` switch:
```sh
node --inspect js-executor.js
```

2) Run your `react-native-desktop` application

3) Open `chrome://inspect` page in a Chrome browser
![](media/devtools-inspect-target.png)

4) Click on `inspect` link near `js-executor.js` Target

5) Chrome devtools will open where you can see console output of your application and debug it.

![](media/devtools-window.png)

### Inspecting UI

Read how to investigate UI structure [with `react-devtools`](https://github.com/facebook/react-devtools/blob/master/packages/react-devtools/README.md)
