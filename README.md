# lightning-viz

This a visualizer for the Decred testnet Lightning Network.

Lightning-viz supports advanced node querying (enter `query:` into the search
bar) and remapping of the graph based on the node search results.

The server also periodically pings peers to determine their connectivity.
The server collects geo-location data on nodes that have an address configured.

## Installation

Tested with node 10.17.0 and npm 6.11.3. Requires dcrlnd running on localhost.

```
git clone https://github.com/jholdstock/lightning-viz
cd lightning-viz
npm install && npm run build
npm start
```
