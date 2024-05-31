---
layout: default
title: QA Instructions
---

_We thank you for testing our app!_

# Prerequisites

You will need

- an iOS or Android mobile device with the [Expo Go app](https://expo.dev/go) installed
- a computer with [`yarn`](https://yarnpkg.com/) installed
- a direct network connection between the two ([tutorial](https://github.com/Green-Kittens/bathroom-finder-frontend/wiki/Connecting-your-mobile-device-directly-to-your-computer))

# Running the App

1. Clone the main branch of this repository
2. Run `yarn install`
3. Run `yarn start`
4. Connect your mobile device to the dev server that you just started on your computer
   1. This is dependent on how you have established a direct netowork connection between your two devices. See the tutorial above for more detail

# Authentication

1. Before logging in, consider testing the functionality of the app while logged out. You will be able to read all of the data we provide, but not be able to create anything.
2. When you then want to log in to be able to create data:
   1. Log in using `<your_email_username>+clerk_test@<your_email_domain>`
      1. For example, if your email is `dltompki@calpoly.edu`, you would log in with `dltompki+clerk_test@calpoly.edu`.
   1. For verification, use the code `424242`
   1. Continue testing the rest of the functionality of our app!

# Contact Us

To contact our on-call engineer, join the channel `#green-kittens-contact-us` on Slack and send a message.
