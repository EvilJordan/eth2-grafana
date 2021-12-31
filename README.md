# eth2-grafana
ETH2 Grafana Dashboards

My humble attempt at figuring out/creating Grafana dashboards to expose Ethereum Beacon Chain metrics.

🚨 I HAVE NO IDEA WHAT I'M DOING 🚨

---

I'm playing with the Prater Testnet and realized the amount of time it takes to sync the Beacon Chain is... a lot. The available Grafana dashboards all assume a complete and up-and-running node, so I've created a dashboard to display useful metrics while I wait for the initial sync to complete.

<img width="1438" alt="Screen Shot 2021-12-31 at 2 35 47 PM" src="https://user-images.githubusercontent.com/1364262/147837339-a9d3f0bc-5019-4fd9-b6ce-eb0c5f393ac4.png">

To install:
1. Copy the raw data from [syncData.json](https://github.com/EvilJordan/eth2-grafana/blob/main/syncData.json) to your clipboard.
2. In Grafana, click the + button in the left-hand menu.
3. Select "Import".
4. Paste the copied json into the text area, then hit the "Load" button.
