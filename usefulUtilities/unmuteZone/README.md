# Unmute Zone
When added to a zone entity, this script will automatically unmute a user when the user is inside the zone.

## Features
- On entering the zone, you will be unmuted (unless you have Push-to-Talk enabled)
- On leaving the zone, you will have your previous mute setting applied
- If a user mutes themselves inside the zone, the zone will not apply your previous mute setting

## Setup
1. Add a zone entity to your domain
2. Select the zone entity with the Create Tool
3. Add `unmuteZoneClient.js` to the "Script" section

## Exclusions
- Push-to-talk is unaffected in the zone

# Releases

## v1.1 :: [2627d1e](https://github.com/highfidelity/hifi-content/commit/2627d1e)
- Added a missing variable to the source code to prevent console errors.

## 2019-04-15_13-00-00 :: [d8a4e4d1](https://github.com/highfidelity/hifi-content/commit/d8a4e4d1)
- Initial release