'[HOME](../README.md)'<br/>


# Local Storage

* to load our web page quickly we want a lot of storage space on the user's machine so it can be remain after refresh the page and without be transmitted to the the server. before HTML5 all these was possible to acheive because there were cookies which had a dealbreaking downsides.

* HTML5 storage refer to local storage or DOM storage, it is based on named key/value pairs, it is limit is 5 megabytes
    * check for html5 storage:
     ```
     function supports_html5_storage() { 
     try {
     return 'localStorage' in window && window['localStorage'] !== null;<br>
     } catch (e) {<br>
     return false;<br>
     }
     }
     ```
* to keep track programmatically of when the storage area changes, we can use the `storage event` , storage event properties: 
    * key
    * old value
    * new value
    * url