# influence-city
Testing the AdMix SDK in a sample game


# Notes (public)

## Test Ads
AdMix SDK has a sandbox mode on a placement level. 
While placements aren't set to live, it'll hit a sandbox.

## Supported Ad Formats
Banner, Video. 

## Creating Placements
Creating a placement is done within the editor itself (via plugin).
You drag, drop, and resize the ad asset to fit within your 2D/3D world.
Need to sync placement creation and save the scene.

## Ad Loading and Viewability 
Ads are only actually requested / displayed after they are rendered in the scene.
The ad unit can _exist_ in the scene, but until it is in view of a camera, it will not be rendered.
Ad request will not be issued ahead of time.

## Ad Impressions (related to above)

From their documentation:
Impressions are counted when the ad enters the field of view of the user, meaning when the content is starting to render around them. So an ad in another scene will only render when the user enters the scene and approaches this ad.
https://docs.admix.in/docs/getting-started/how-it-works 

Gaze Tracking: https://docs.admix.in/docs/admix-plugin/understanding-gaze-tracking 




