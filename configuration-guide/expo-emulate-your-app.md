---
description: EAS Update is the next generation of Expo's updates service.
cover: https://webomnizz.com/wp-content/uploads/2020/01/expo-publish.jpg
coverY: 0
---

# 📲 Expo: emulate your app

### Step 1: Create account on Expo

Access the Expo website and create an account on the platform. It is recommended that you create an account by entering your email and password and not by SSO login, this will make it easier when you login through the terminal with the command _**eas login**_.

**Website**: [https://expo.dev/signup](https://expo.dev/signup)

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

### Step 2: Install and Login EAS CLI

1. Open a terminal.
2.  Install EAS CLI globally using npm:

    ```bash
    npm install --global eas-cli
    ```
3.  Log in to your Expo account with EAS CLI:

    ```bash
    eas login
    ```

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

### Step 2: Request access to organization

In order for you to be able to build and make the app available to be viewed on your cell phone, you need to request access to the organization. Ask one of the admins to add you.

Path: [https://expo.dev/accounts/mercado-topografico/settings/members](https://expo.dev/accounts/mercado-topografico/settings/members)

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### Step 3: Starting your project

In your **project directory**, run the command:

```bash
npx expo start
```

After that press "**a**" to open Android Emulator:

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

Or you can run the following command which also works:

```bash
npm run android  
```

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>
