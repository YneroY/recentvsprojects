# Recent VS projects
I would like to explore how Dataflow could be used to speed up flow of information and processing through a pipeline.

There will be multiple components in this project,

1. Initiatialization will happen by processing all the files in a folder & subfolders, to construct a Trie for all VS solutions.
2. Periodically scan the processes running to store which project (if any) is kept open for the longest time. Keep the top 3 at the moment.
3. A seperate Dataflow pipeline is created to broadcast the projects picked up.
