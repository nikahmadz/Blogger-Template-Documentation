# Data
## View
**data:view**
```
view.archive.rangeMessage
view.isArchive
view.isError
view.isHomepage
view.isSearch
view.isSingleItem
view.isMultipleItems
view.isLayoutMode
view.isPage
view.isPost
view.isPreview
view.isLabelSearch
view.search.resultsMessageHtml
view.title
view.title.escaped
view.type
view.description
view.url
view.url.canonical
```
## Blog
**data:blog**
```
blog.adsenseHasAds
blog.encoding
blog.enabledCommentProfileImages
blog.isMobile
blog.isMobileRequest
blog.mobileClass
blog.isPrivate
blog.isPrivateBlog
blog.title
blog.url
blog.url.canonical
blog.homepageUrl
blog.languageDirection
blog.locale
blog.locale.languageAlignment
blog.localeUnderscoreDelimited
blog.searchLabel
blog.searchQuery
blog.pageName
blog.pageType
blog.pageTitle
blog.feedLinks: The autodiscovery feed links for the page header.
```
## Page Header
```
data:title
data.description
```
## Blog Posts
```
feedLinks: A list of feeds for this page. On the main page, this will contain the main blog feeds; on item pages, this will also contain comments feeds. Each item in this list contains the following:
  feedLinks.url: The feed URL.
  feedLinks.name: The feed name (i.e. 'Posts' or 'Comments').
  feedLinks.feedType: The type of feed (Atom or RSS).
  feedLinks.mimeType: The mime type of the feed.

olderPageUrl: If there are older posts than the ones on the current page, this is a URL to those posts. Context-sensitive for page type. (Not all pages will have this link.)
olderPageTitle: Title of the link to the older page of posts.
newerPageUrl: The newer equivalent of olderPageUrl.
newerPageTitle: The newer equivalent of olderPageTitle.
commentLabel: The phrase to use to show the number of comments, e.g. "comments."
authorLabel: The phrase to use to indicate who wrote the post, e.g. "posted by."
timestampLabel: The phrase to use to indicate when the post was written, e.g. "posted at."
postLabelsLabel: Phrase to introduce the list of post labels, e.g. "labels for this post."
backlinksLabel: Phrase to describe backlinks to this post, e.g. "links to this post."

posts: A list of all posts for this page. Each post contains the following:

  posts.dateHeader: The date of this post, only present if this is the first post in the list that was posted on this day.
  posts.id: The numeric post ID.
  posts.title: The post's title.
  posts.body: The content of the post.
  posts.author: The display name of the post author.
  posts.url: The permalink of this post.
  posts.timestamp: The post's timestamp. Unlike dateHeader, this exists for every post.
  
  posts.labels: The list of the post's labels. Each label contains the following:
    posts.labels.name: The label text.
    posts.labels.url: The URL of the page that lists all posts in this blog with this label.
    posts.labels.isLast: True or false. Whether this label is the last one in the list (useful for placing commas).
  
  posts.allowComments: 'True' if this post allows comments.
  posts.numComments: The number of comments on this post.
  posts.showBacklinks: Whether to show backlinks for this post.
  posts.numBacklinks: Number of backlinks for this post.
  posts.addCommentUrl: The URL of the 'add a comment' form for this post.
  posts.emailPostUrl: The URL of the 'email this post' form for this post.
  posts.editUrl: The URL of the edit form for this post.
  
  posts.feedLinks: A list of feeds specific to this post. (This is different from the overall blog feedLinks, as it may contain a feed for the post's comments, for instance.) Each contains the following:
    posts.feedLinks.url: The feed URL.
    posts.feedLinks.name: The feed name (e.g. 'Posts' or 'Comments').
    posts.feedLinks.feedType: The type of feed (Atom or RSS).
    posts.feedLinks.mimeType: The mime type of the feed.
  
  posts.comments: A list of all comments for this post (on item pages only). Each contains the following:
    posts.comments.id: The numeric ID of the comment.
    posts.comments.body: The body of the comment.
    posts.comments.timestamp: The time the comment was created.
    posts.comments.author: The display name of the comment's author, or 'Anonymous'.
    posts.comments.authorUrl: URL of the comment author's profile, if the comment is not anonymous.
    posts.comments.deleteUrl: The URL for deleting this comment.
    posts.comments.isDeleted: Whether this comment has been deleted. (The text of deleted comments is replaced with a placeholder.)
```
## Link
**data:link**
```
link.title
```
## Messages
**data:messages**
```
messages.archive
messages.moreEllipsis
messages.morePosts
messages.postAComment
messages.posts
messages.showAll
messages.subscribeTo
messages.visitProfile
```
## Post
**data:post**
```
post.adNumber
```
## Skin
**data:skin**
```
skin.vars
skin.vars.body_background.image.isResizable
```
## Misceleneous
```
data:aboutme
data:adCode
data:this
data:content
data:posts
```