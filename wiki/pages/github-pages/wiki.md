# Creating new page

To create a new page just create a html file in the appropriate category folder. Eks: `/wiki/python/webscraping.html`

Paste the html code from the [_example.html](https://raw.githubusercontent.com/EliasTors/eliastors.github.io/main/wiki/_example.html)

Then create a corresponding markdown file in the `/wiki/pages/YOURFOLDER/YOURFILE.md`

Lastly add a link in the `/wiki/table_oc.md` to the new page


# Creating a new category

To create a new category is pretty straight forward. Create a new folder with the name of the new category. This will be the be adress and it **is** case sensetive. After you have created the folder for the category, create a html file called `index.html`. This will be the landing page for the category. 

After that you can create a folder under the `wiki/pages/` and create a md file to add to the start page. The name of this file can be anything you want, just refert to it in the html file. 

To add more pages to category refer to the top of this page

# Notes

- When updating CSS the browser may cache info. To force refresh of css use `Ctrl + F5`