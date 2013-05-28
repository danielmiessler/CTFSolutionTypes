1. Solution in Source Code: Don't forget to review the source code of the page(s) you're looking at. The solution is often right in front of you--frequently in a comment.

2. Check Your POST Values: Make sure you check your POST values (especially your cookies) to ensure there isn't trivial encoding being used to hide security-sensitive information, e.g. username=admin

3. Content Discovery: There is often juicy content hanging off the tree structure you're working within, e.g. /admin, etc. Make sure you using something like Dirbuster or Burp's Content Discovery under Engagement Tools.

4. Injection Flaws: Injection flaws in CTFs are often fairly straightforward. Have a basic list of injections handy for attacking key parameters.

5. Bypassing Authentication via SQLi: Don't forget to try bypassing authenticaiton altogher via a basic SQL Injection.
