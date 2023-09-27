---
description: On this page, we will explain how error handling works on the Hitfel 5.
---

# Failsafe

On a stock (stock as in not touched or modified at all) system, there is the off chance that you could get an exception.

Failsafe attempts to fix and handle all exceptions and prevent the user from seeing buggy or broken parts of the system.

## Normal Error

A normal error occurs when a small bug happens. For example, pressing the green flag too many may result in a small error. This can usually be solved by pressing the green flag or refreshing the page.

<figure><img src=".gitbook/assets/Screenshot 2023-09-26 193032.png" alt=""><figcaption><p>The normal error screen</p></figcaption></figure>

## Fatal Error

A fatal error usually occurs when the code has been messed with while the system is running. A fatal error is recoverable usually by factory resetting the device.

<figure><img src=".gitbook/assets/Screenshot 2023-09-26 193342.png" alt=""><figcaption><p>The fatal error screen</p></figcaption></figure>

## Hardware Error

A hardware error usually occurs when the Wi-Fi module has been touched or the battery is somehow showing an incorrect percentage. This error is non-recoverable from and may require a full refresh or reset.

<figure><img src=".gitbook/assets/Screenshot 2023-09-26 193639.png" alt=""><figcaption><p>The hardware error screen</p></figcaption></figure>
