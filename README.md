# azure-blob-list
Have you ever wanted to just see a list of the items in a blob container by looking at the base URL?  Well, you can't.  But you can go to this index.html page and do the same thing!

All you need to do is set the container access policy to container (aka public container and blobs) in either the Azure portal, from your favority Azure CLI or from an Azure Storage Explorer app.

Then upload the three files in the repo to the root of the container, and visit <container uri>/index.html to enumerate the files with easy links.  This script also crawls sub-folders.  Limited to 5000 results, but you can extend with paging if you like.



