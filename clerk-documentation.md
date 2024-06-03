---
layout: default
title: Clerk Documentation
---

In progess

# Official Documentation

General: https://clerk.com/docs
Expo: https://clerk.com/docs/quickstarts/expo

# User Authentication

1. To get started in the app no account is required. Simply use the app to view bathrooms and reviews.
   1. To get access to full features of the app, such as posting new bathrooms and reviews, an account is required.
      1. Register using email and password.
         1. Register using you legal first and last name, this will be the name other users will see.
         2. Use a valid email adress that we can send you verification code to during the signup process
         3. Enter a strong memorable password, with a minimum strenght of "good". This password should not be shared with others.
         4. Enter the 6 digit code you have received in your email inbox.
      2. Register and sign in using Google or Microsoft sign in.
         1. To expedite the process of signing in, login using your exisitng third party account.
         2. The data that will be collected is the same as registering using email and password.
      3. Sign in using Email code
         1. When you have an account you can simply login using your email
         2. Enter the code sent to your email
         3. No password is required.
2. Each login session will last for 30 days unless you sign out under the user profile tab.

# Testing

1. Register using `<your_email_username>+clerk_test@<your_email_domain>`
   1. For example, if your email is `dltompki@calpoly.edu`, you would log in with `dltompki+clerk_test@calpoly.edu`.
   2. Enter any required information(First Name, Last Name, Email, Password and confrim your password).
1. For verification, use the code `424242`

# Dev

Clerk has been set up so all you need to do is import the component you want to use from clerk.

- To limit what users can do or see in the app all you need to do is import useSignIn and/or useSignOut
  Example usage:
  - `<SignedIn> You are Signed In </SignedIn>`
  - `<SignedOut> You are Signed Out </SignedOut>`
  - These components can be wrapped around any other component.
- To get access to user data such as First and Last name import useUser
  Example usage:
  - `<Text> Hello, {user.firstName} {user.lastName} welcome to Bathroom Finder</Text>`
