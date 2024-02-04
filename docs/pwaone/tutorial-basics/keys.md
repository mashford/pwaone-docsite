---
sidebar_position: 1
---

# Keys

Keys are the core of PWA One. They are used to generate your digital identity, sign your posts, and encrypt your messages.

## 1. Root Secret Key

**RSK (Root Secret Key)** is the start point of your PWA One journey.

- Like a Bitcoin wallet has a secret key, PWA One has RSK to for generating everything else.

- RSK is a **Secret Key**, that's say, it will never leave your phone. _It will not be in the keychain, it will not in a remote server. And it's **your responsibility** to keep it safe_.

A good practice is to use a generator to create some RSKs, print it out and keep them in a locked drawer.

## 2. Path

**Path** is list of keywords indicating the using scenario.

Ex: `["personal", "blog"]` means this key is used for personal blog.

## 3. Avatar Secret Key

**Avatar Secret key** is the key to generate your digital identity. It's a **Secret Key**.

- It's **generated** from RSK and path.
- It **will** be used to generate your digital identity information.
- It **will** be used to sign your posts.
- It comes with a _**Public Key**_.

## 4. Avatar Public Key

**Avatar Public key** is the key to generate your digital identity. It's a **Public Key**.

- It's **generated** from **Avatar Secret key**.
- It **will** be used to verify your signatures.
- It **can** be shared and stored in **PWA One Publics**.
