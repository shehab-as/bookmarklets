# Bookmarklets

A collection of bookmarklets for quick actions like PR links (GitHub, GitLab, etc.), Google docs, Notion, etc. These can be added to your browser bookmarks for easy access.

## How to Add a Bookmarklet to Your Browser

1. Copy the JavaScript code from the bookmarklet you want to use.
2. Right-click on your bookmarks bar and select "Add Page" or "Add Bookmark."
3. Name the bookmarklet (e.g., "GitHub PR").
4. Paste the JavaScript code into the URL field.
5. Save the bookmarklet.
6. Click the bookmarklet while viewing a page (e.g., a GitHub PR) to call the embedded code.


### Here's an example

A bookmarklet to send a simple alert message to your browser.

```javascript
javascript:(function(){
  alert('Hello, this is a test bookmarklet 👋!');
})();
