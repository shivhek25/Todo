It's a todo hybrid app based on ionic framework.

# Requirement

First, you need to install `ionic` and `cordova`:

```bash
npm install -g ionic cordova
```

After that, install all requied modules using `npm`

```bash
npm install
```

# Run the server

```bash
ionic serve
```

# Run on emulator

For Android:

```bash
cordova platform add android
cordova emulate android
```

For iOS:

```
cordova platform add ios
cordova emulate ios
```

# Build the project

For Android:

```bash
cordova build android
```

For iOS:

```
cordova build ios
```
