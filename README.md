# webring url of SDY60-2024
## https://sdy60-2024.github.io/webring/



Webring is based in Webring Starter which is a modern, simple webring that anyone can setup and use!
Please note that there is an automated build occuring every 1 hour to push the changes live (after your pull request has been approved). 
Before you make any changes you need to create a new branch, no need for multiple.

This is a 2-step process: 

-When you want to update your CV info just follow this path **_include > members-cv.html** and add accordingly to the html code your info! 
**( copy this and add it to the respective file )**

```html
<li>
    <h3>
      <a class="post-link" href="https://github.com/XXX/linkhere">
        Somebody X  <!-- Display the member name -->
      </a>
    </h3>
  </li>
```

-Update the members list in **list.json** by updating the below code in the file **( copy this and add it to the respective file )**

```html
{
      "name": "Somebody",
      "url": "https://www.example.com/",
      "author": "Somebody <somebody@example.com>"

    }

```


