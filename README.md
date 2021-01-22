# Wails + Vue.js 2 + TypeScript + Vue Router + Vuex + Tailwind CSS v1

First, you need to install https://github.com/wailsapp/wails and [Node.js](https://nodejs.org/en/).

## Development

Run Go backend
```
wails serve
```

Run Vue.js 2
```
cd frontend
npm run serve
```

## Build

Run this command to build
```
wails build -f
```

The build output in folder `./build`

Notes:
> The `-f` parameter can be use to force rebuild frontend (`npm run build`).

### Debug

For Debugging, put `-d` parameter
```
wails build -f -d
```

Now you can right click to open developer tools.

#### Windows

Unfortunately, old IE don't have developer tools. You can't right click to open developer tools. Instead You can to run this
```
C:\Windows\System32\F12>IEChooser.exe
```

Then choose to attach developer tools to wails window.

### Run

Windows
```
build/vue2.exe
```

Linux
```
./build/vue2
```

MacOS
```
open build/vue2.app
```
