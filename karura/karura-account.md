# Karura Account

This document covers the basics of Acala, Karura, Polkadot and Kusama account addresses.

## Address Format

Acala and Karura use the Substrate-based chain address format SS58. Read more [here](https://wiki.polkadot.network/docs/en/learn-accounts).

* Acala addresses always start with the number 2.
* Karura addresses could start with a small letter like l, r, p, q, o...
* Polkadot addresses always start with the number 1.
* Kusama addresses always start with a capital letter like C, D, F, G, H, J...
* Generic Substrate addresses start with 5.

## Account Generation 

Before the network is live, and during the initial launch period, below is the only recommended method for generating an Acala and Karura account:

* Polkadot{.js} Browser Plugin 

## Polkadot{.js} Browser Plugin 

### Install the Browser Plugin

The browser plugin is available for both [Google Chrome](https://chrome.google.com/webstore/detail/polkadot%7Bjs%7D-extension/mopnmbcafieddcagagdcbnhejhlodfdd?hl=en) \(and Chromium based browsers like Brave\) and [FireFox](https://addons.mozilla.org/en-US/firefox/addon/polkadot-js-extension). Download the plugins [here](https://polkadot.js.org/extension/).

![](../.gitbook/assets/screen-shot-2021-05-14-at-4.49.27-pm.png)

### Create Account

Open the Polkadot{.js} browser extension by clicking the logo on the top bar of your browser. You will see a browser popup not unlike the one below

![](../.gitbook/assets/screen-shot-2021-05-14-at-4.52.43-pm.png)

Click the big plus button or select "Create new account" from the small plus icon in the top right. The Polkadot{.js} plugin will then use system randomness to make a new seed for you and display it to you in the form of twelve words.

![](../.gitbook/assets/screen-shot-2021-05-14-at-4.53.46-pm.png)

You should back up these words as [explained here](https://wiki.polkadot.network/docs/en/learn-account-generation#storing-your-key-safely). It is imperative to store the seed somewhere safe, secret, and secure. If you cannot access your account via Polkadot{.js} for some reason, you can re-enter your seed through the "Add account menu" by selecting "Import account from pre-existing seed".

### Name Account & Password

The account name is arbitrary and for your use only. The password will be used to encrypt this account's information. You will need to re-enter it when using the account for any kind of outgoing transaction or when using it to cryptographically sign a message.

Note that this password does NOT protect your seed phrase. If someone knows the twelve words in your mnemonic seed, they still have control over your account even if they do not know the password.

![](../.gitbook/assets/screen-shot-2021-05-14-at-4.54.44-pm.png)

### Set Address for Acala Mainnet

Now we will ensure that the addresses are displayed as Acala mainnet addresses.

Click on "Options" at the top-right corner of the plugin window, and under "Display address format for" select "Acala".

**Your address's format is only visual** - the data used to derive this representation of your address are the same, so **you can use the same address on multiple chains**. 

You can copy your address by clicking on the account's icon.

![](../.gitbook/assets/screen-shot-2021-05-14-at-4.58.59-pm.png)

### Set Address for Karura Mainnet

Click on "Options" at the top-right corner of the plugin window, and under "Display address format for" select "Karura".

**Your address's format is only visual** - the data used to derive this representation of your address are the same, so **you can use the same address on multiple chains**. 

You can copy your address by clicking on the account's icon.

![](../.gitbook/assets/screen-shot-2021-06-08-at-2.27.20-pm.png)

### Set Address for Polkadot Mainnet

Click on "Options" at the top-right corner of the plugin window, and under "Display address format for" select "Polkadot".

**Your address's format is only visual** - the data used to derive this representation of your address are the same, so **you can use the same address on multiple chains**. 

You can copy your address by clicking on the account's icon.

![](../.gitbook/assets/screen-shot-2021-05-16-at-9.45.59-am.png)

### Set Address for Kusama Mainnet

Click on "Options" at the top of the plugin window, and under "Display address format for" select "Kusama".

**Your address's format is only visual** - the data used to derive this representation of your address are the same, so **you can use the same address on multiple chains**. 

You can copy your address by clicking on the account's icon.

![](../.gitbook/assets/screen-shot-2021-05-16-at-9.46.09-am.png)

### Convert Address for different chain formats

You can use the [Subscan Address Transform tool](https://polkadot.subscan.io/tools/ss58_transform) to convert your address between the different chain formats.

Enter any address in the input box on the left-hand side, then click **`Transform`** button, you can see address formats for all chains on the right-hand side.

## **Polkawallet**

### **Install Polkawallet App**

Download the Polkawallet app via [its official website](https://polkawallet.io/). The app is available through the Apple App Store for iOS devices, Google Play for Android devices, and as Android APK.

### Create Account

1. Click on the "Create Account" button.

![](https://lh5.googleusercontent.com/VaB4EcpFPO9Qmvl2K_MVKk8rVevhEzDsD45WZzkWKe3B6DXyoSU8-IenMk3slTe4uGLVl4IzAEmOz-A0SyJ508VUy49UfiGpsBT5R7q2QRmeybP1cE-2fU52iOdoudgcdmsLv_Kl)

2. A new screen will appear explaining the importance of recording your mnemonic phrase in a safe place. Click the "Next" button.

![](https://lh6.googleusercontent.com/509_xAUccOu0djt4YJZsvrLW4H_fdBxmOmMMwpRrseGSt9xcyZdx4Tgge7ZofXk6um7rSR6LcPL7c23rJHF2ZHv7FlLl2SbYciqd3-ck_v_hlco0RRP7oPpin90nv2YETvvN_cEb)

‌3. Your mnemonic phrase will appear. Write the mnemonic on a piece of paper and store it somewhere safe. Click on the "Next" button.

![](https://lh5.googleusercontent.com/XD1NG32OkmzZYToN8Fb-noLzUJmacWIACYhi-gSyV3-s58n4Ovu6sS0qQMRe1NkMMyLA4LBz_wEHRnEDwVnQgEaXQwCrgvUr0fNvA8SDilS7mrrnP--9bx3-SnHaioy_prFD4KoE)

4. Confirm your mnemonic by entering the words in the correct order. Click on the "Next" button when completed.

![](https://lh4.googleusercontent.com/ROVs8A4woJy9RYKmsGd6Jm1W8GMzG_cpB6ba3XLViS18GMTmRK0giSV7qkDh2XZrKxxLv4LFLEFuiRT6Lw3wri8yu6cT9tBMyw00vMhxq5Vmwb2qBOUg9-Eey7RHMbh4araqvk7P)

### **Name Account & Password**

Name your account and create a strong password \(at least 6 characters\). Click on the "Next" button when completed.

![](https://lh4.googleusercontent.com/PWXIJxAuCBlb-QGBrpce0gvFgG_C_jWUL125eOU_ke_thRY4WDhUq1AvDa6bAWHWy_sD5BXp40gM5zzJRdkDGF5XrtLEuLD5TwJ1sV8FDdjr1QRjDm9I-hzfXGsqBLsq0QVFgb02)

Your wallet is now set up! The screen will default to the Polkadot network. You can determine which network you're connected to by looking at the grey text under the account name. In the case of this screenshot, it says "Polkadot."

![](https://lh5.googleusercontent.com/xlFLRGhSFMpRc1QeJrObC8vazj7YCLIe2AvW-euSwN4bvjlZWhTbcyBxF4SPTXQGuOCJtdxMW_1IMNyoL88RzC51RGN7CkLepjjOXTnJkEkp0ZSRzS58F7rAVMamcuXJ_01S6AhE)

### Set Address for Polkadot Mainnet

1. Click the menu button on the top-right corner.

 ![](https://i.imgur.com/JwPrsVe.jpg%20=250x)

2. In the opened menu select the Polkadot logo, then press on the appeared address on the main screen.

 ![](https://i.imgur.com/YGx8nne.jpg%20=250x)

### Set Address for Kusama Mainnet

1. Click the menu button on the top-right corner.
2. In the opened menu select the Kusama logo, then press on the appeared address on the main screen.

### Set Address for Acala Mainnet \(Coming Soon\)

### Set Address for Karura Mainnet \(Coming Soon\) 

 



###  
