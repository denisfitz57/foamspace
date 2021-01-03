# Elasticsearch

 Project elasticsearch and tika on Docker to index some PDFs on the f:drive
> this: curl -X PUT --data-binary @WestVJan10_20.pdf http://localhost:9998/tika --header "Content-type: application/pdf"
> returned text out when run under another linux and git bash prompt with file's dir set as the worling directory
> note powershell curl is not curl
> Make Windows folder visible to tika server running as a container  
> set volume e.g., docker run -v /mnt/f/files/
> Hook up both containers using Docker compose
> Tika server gets info via  command line ~~(maybe)~~
