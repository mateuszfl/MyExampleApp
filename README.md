
**Installation**

1. Run:
 
    docker-compose up -d

2. Go to http://localhost/admin in your browser
3. Log in with "admin" and the password "shopware"
4. Go to Extension -> My extensions
5. Install and activate the application called "Label"

**What's the problem**
When will I do:

    curl -i http://localhost/storefront/script/custom/endpoint 

I am expecting a 200 response code and the following content: {'foo': 'bar'}

Instead I get the answer code "204 No Content" and that's wrong.

> Written with [StackEdit](https://stackedit.io/).
