# 100MB Map

This repository might host an experiment where I see how much of the OSM data I can compress and fit into 100 megabytes.
I would like to put together a vector map which uses no API, just a static file server (like GitHub Pages) and GitHub
repositories have a file size limit of 100 MB: https://help.github.com/en/articles/what-is-my-disk-quota and I am thinking
about trying to squeeze all this data into a single file and use `fetch` with range requests to get bits as they are needed.