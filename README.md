![repository-banner.png](https://res.cloudinary.com/alvarosaburido/image/upload/v1564929632/as-readme-banner_tqdgrx.png)

## Software version

- `node -v` : v12.16.1
- `npm -v` : v6.13.4
- `vue --version`:3.0.0-rc.10
- `ionic -v` : v6.11.8-testing.0
- `@ionic/vue -v` : v0.3.1

---

# Ionic Vue 3 Labs

This app was created following the official blog post: [Announcing the (new) Ionic Vue Beta](https://ionicframework.com/blog/announcing-the-new-ionic-vue-beta/)

```bash

ionic start ionic-vue-lab sidemenu --type vue
```

## Serve

```bash
ionic serve
```

## Android

### Livereload on device

To test your app on a emulated or physical device you must install last version of [Android Studio](https://developer.android.com/studio).

In your bash profile, or zsh add an alias for adb

```bash
code ~/.zshrc
```

```bash
alias adb='/Users/<your-user>/Library/Android/sdk/platform-tools/adb'
```

To help it have effect run

```bash
source ~/.zshrc
```

Then:

```bash
 ionic capacitor run android -l --external
```
