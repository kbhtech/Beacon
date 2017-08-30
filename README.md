# Beacon
Beacon to be a public service of multiple private and public servers which consists of beacons to play with, aid operations, or aid catastrophies. 

# The Idea
The idea behind this product is to allow people to privately, publically, or authoritively report their position or their location on a server of beacons that are tracked. A beacon will have three different states; carried, dropped, or thrown. 

# The Layout
The application will open with a directory of the authoritive servers and they can tap one of the servers to automatically connect. From their, a titlebar will display to allow the user to select between two different views. The first view is the beacon itself. The second view will be google maps with beacon lights accross it. 

# The Beacon
Whenever a user taps the beacon on the phone, it toggles between "On and Off". Whenever the beacon is turned on, and the phone is on, then the state of the beacon will be green and it is actively tracking. Whenever the phone is turned off after a becon was turned on then the status of the beacon is yellow, it is not actively tracking. A beacon that switches between active to inactive tracking is also dropped. It is no longer tagged to the phone. Instead, it is tagged to the location. 

# Dropping The Beacon
Dropping the beacon is an easy flick when holding your fingure down on the beacon. Now, the beacon turns yellow and it is tagged to the location for x time before it turns gray.

# Picking Up A Beacon
Whenever someone is at the scene, they are able to pick up any dropped beacons in the area. Only the carrier can turn a carried beacon off. 

# Throwing A Beacon
Thrown beacons happen whenever someone sends someone else a beacon and their phone is off. The beacon acts like a dropped beacon except it has reference data associated with it. A beacon can be either thrown through the web services or thrown from the mobile application.

# Servers
Public Servers: Public servers should probably only be used whenever their is a catastrophie or huge event, perhaps on memorial day we may host a public server and color all becons on that server white for the entire night.
Authoritive Servers: These are servers provided from your local emergancy services
Private Servers: These are recommended for fun and play as well as convoys.

# Data behind the Beacon
I have posted a json example of a search response from a server that does not exist yet. Their is some personal information in a beacon. That is because beacons should mainly be used for emergancies/catastrophic situations.
