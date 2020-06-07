# Pretty Fly for a WiFi
Category: SOCIAL

Type: Automatic

Flag: `CYBAR{Ballarat}`

Points: 250

Difficulty: Easy-Medium

Status: Playable after CTF ends

Real Person or Ficticious: Fictitious

## Summary
BSSID's can be tracked down to their physical geo-location.

## Description
We need to find Marc's second office location (not the primary workplace) for the contract tracing. Business records tell us it's relatively new. Scour his Twitter account and see if there's anything that can help us geo-locate it. We don't need it down to the road, just the town (not suburb) and we can work from there.

Flag format: `CYBAR{x}`

## Solution
By searching for ways to track down Wireless Access Points, and correlating that data with the WiFi info posted by Marc on his twitter, they can track down the BSSID address to the street. Search for open Wi-Fi databases.

`74:44:01:81:b8:e2` BSSID found via Wigle.net for example

## Files Included
[WiFi picture on Marc's twitter feed](../Files/pretty_fly_for_a_wifi.png)
