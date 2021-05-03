# Intro
Directed network graph of Valheim's crafting recipes created in [Gephi](https://gephi.org/). The thickness of each edge (line connecting nodes) is the amount of source material needed to create target material. Edge color related to the category of the target node (type of weapon, item, etc.). Node colour is dependant on how much of a hub a given node is - darker means a bigger hub, lighter colour means not so much of a hub.

## Data source
All data used to create this graph was taken from [ign.com](https://www.ign.com/wikis/valheim/Items_List#) using Google Spreadsheets.

## To-do
- [x] Create a static PNG version of the graph
- [ ] Sort out the arrows not appearing in the static graph version
- [ ] Create an interactive version of the graph using Python's Plotly/Dash package
- [x] Upgrade the data source to [ign.com](https://www.ign.com/wikis/valheim/Items_List#) as it's more comprehensive

![Alt text](/crafting_hubs.png?raw=true "Optional Title")
