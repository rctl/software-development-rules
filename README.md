# Software Development Rules

[1] When in doubt, **index**

> Indexing data makes for faster requests when fetching data from databases. Specifying desired order of elements in your indexes keeps the database from sorting your data upon request.

[2] Minify assets whenever possible

> Make sure all your assets are minified by your server before sent to the client. When scaling, significant amounts of bandwidth will be saved.

[3] Always do a postmortem after a system failure

> Doing a postmortem after a system failure means that not only do we get a backlog of every bug but we also get to think back and learn from our mistakes. 

[4] Always serve over HTTPS

> There are really no excuses for not using TLS. Make sure all of your requests are served securely.

[5] Release them resources

> Properly releasing resources and closing network connections in a controlled manner should always be taken care of.

[6] Sleep while true

> When blocking a thread with a while(true){} add a sleep to avoid excess CPU usage
