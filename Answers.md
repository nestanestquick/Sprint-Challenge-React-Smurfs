1.  Explain the differences between `client-side routing` and `server-side routing`.
   
    Server Side  sends a request for an entire document every time a link is clicked and causes the whole page to refresh, and dicards old page. The Pro's are that it only requests the necessary data and search engines are server side optimized. Cons are that each request pulls up a new document and can be a burden on the machine if the internet connection is slow or the file is big 

    Client Side Routing is loaded once and further interacions are loaded with javascript state, only the requested information changes rather than the whole webpage. Pros are it loads faster do to only section of the webpage changing. Cons are everything is preloaded in the beginning ,so initial loading time might be slower, and search engines havent quite caught up to Client Side Routing

2.  What does HTTP stand for?

    Hyper Text Transfer Protocol

3.  What does CRUD stand for?

    Create 
    Read
    Update
    Delete

4.  Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.

    Create - Post
    Read - Get
    Update - Put
    Delete - Delete

5.  Mention three tools we can use to make AJAX requests

    Building an XMLHTTP request manually (advanced)
    Axios methods
    Ajax methods (JQueryy, etc)