meredith-bookmarklets
=====================
This repo has a collection of bookmarklets useful to our development teams at Meredith.

Create a bookmarklet with the following pattern:
```javascript
javascript:(function(){var s=document.createElement('script'), u = '<raw github url>';u='https://rawgit.com/'+u.split('/').slice(3).join('/');s.src=u;document.body.appendChild(s);})();
```
