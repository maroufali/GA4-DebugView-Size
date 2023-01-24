### GA4 DebugView (column size problem)

JavaScript bookmark to hide the column to create more space and room for the DebugView.

1. Create a new bookmark
If you use Google Chrome use CTRL+D or click the ⭐️ icon on the right of URL

2. Click more and change the URL
Change the name to ("GA4 DebugView Size") and copy and paste the script in the URL field

3. Go GA4 Debug View and click the bookmark
Now you can hide the property column if you click the bookmark

```js
javascript:function DebugViewFull(){document.querySelector('body > ga-hybrid-app-root > ui-view-wrapper > div > app-root > div > div > ui-view-wrapper > div > admin-home').style.maxWidth = 'none';document.querySelector('.admin-nav-columns.with-selection').style.minWidth='0';document.querySelector('.admin-nav-columns.with-selection').style.width='0';}DebugViewFull();
```
