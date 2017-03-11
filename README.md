kiwifolk.org.nz
===============

This is the place to put notes about the site

This will be displayed on github when you look at the site via the web interface

Loading changes to live website
-------------------------------

Once you've pushed updates to the **Branch: master** these changes need to be incorporated to the
**Branch: gh-pages**.

Using the website <https://github.com/kiwifolk/kiwifolk.org.nz> you can issue a
**Pull** request to get the changes from the **master** branch into the **gh-pages** branch.

  * Select the button **New pull request**
  * You should now see a screen headed **Compare changes**
  * Set *base:* to **gh-pages** and *compare:* to **master**
    * **Make sure you get these in the right order otherwise you'll downgrade the master branch to be the same as the gh-pages branch**
  * If you're happy that the changes should be committed to the live website, press **Create pull request**
    * You should see a message like: *asjl  wants to merge 1 commit into gh-pages from master*
  * Choose **Merge pull request** and then **Confirm Merge**
    * You should see a message like: *asjl  merged 1 commit into gh-pages from master 12 seconds ago*
  * Check the website <http://kiwifolk.lpnz.org> to make sure the changes are correct.
