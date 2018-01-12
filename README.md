### Description
A non-linear cyclical flow visualization showing the relationship of where certain personas spend most of their time on myGA.

![Mockup](/assets/mockup.png?raw=true)

### Why?
-   We often create flow charts and diagrams like these on the Design team that become outdated and stale in relation to production, and are a real hassle to update.
-   The goal here is to improve visibility between related touchpoints to help understand the inputs and outputs of information flow.
-   Ideally this diagram would be powered by actual event tracking data from myGA/Snowplow, abstracted into a simple birds eye view.
-   Each route is sized based on amount of "traffic" to and from that touchpoint group (similar to a funnel).

### Usage
-   `npm install`
-   `npm start`
