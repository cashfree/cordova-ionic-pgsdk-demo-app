# Cashfree PG Ionic Cordova Demo App
This demo app illustrates integration of [cashfree_pg_sdk_cordova](https://www.npmjs.com/package/cashfree_pg_sdk_cordova).

## Environment
For setting up cordova environment refer [here](https://cordova.apache.org/docs/en/10.x/guide/cli/)

---

## Setup
Enter the following command in your shell.
### Step 1 (Clone the Repo)
```shell
git clone https://github.com/cashfree/cordova-pgsdk-demo-app.git
```
### Step 2 (Install dependencies)
```shell
npm install
cordova plugin add
```
### Step 3 (Sync project)
```shell
ionic cordova prepare <platform>
```

---


## Configure the App
* navigate to <code>src/app/home</code> and open <code>home.page.ts</code>
<p align="center">
  <img src="screenshots/screenshot1.png" alt="setting-api-keys" />
</p>

* Replace <code>APP_ID</code> and <code>APP_SECRET</code> with the credentials from your Cashfree's account PG dashboard.

* Set the <code>ENV</code> as per the environment from where the credentials are used ( 'TEST' or 'PROD' ).

---

## Installing The App
### Android
To install the app in android run the following command.

```shell
ionic cordova run android
```

### iOS
To install the app in iOS run the following command.

```shell
ionic cordova run ios
```
