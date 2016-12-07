# articleperuser
**articleperuser** is a module that adds a new block at your website. It produces a list of nodes, ordered by their post date descending, and only one node per author is visible. This way the block won't show more than once an author, and their order is based on the post date of their latest article.

Currently **articleperuser** works only on **Drupal 7 CMS**.

Block contents
--------------
 - Author user name and avatar, with links to their profile page
 - Node title and teaser, with links to the full node

Configuration
-------------
Admin can configure the way the block works by the block config page. He can:

 - change the maximum number of shown articles-authors
 - restrict the scanned authors by specific role
 - restrict the scanned nodes by specific content type, or show from all the content types
 - select the avatar imagestyle to be used 

Features
-------------
 - Authors' latest node shown
 - Authors are shown only once
 - Authors avatar used
 - Configuration in the block config page

ToDo
----
 - Create a themable .tpl file of the block
 - Add more configuration parameters, like excluding parts of the content
