# FAKEBOOK

## Specification
Build a micro social network where users can create their posts and comment on others.

Users should be able:
* create posts
* comment on their own posts and other users
* remove comments on their pages
* edit profile (first name, last name and upload avatar)

Admins should be able:
* the same functionality as for users
* delete any comment
* delete users' posts with all its comments

## Structure
Application should have structure like this:
```
/                   # welcome page
/feed/              # list of the most recent posts
/feed/:id           # detailed view of a post with users comments
/user/:id/feed      # user's feed page
/user/:id           # user's profile page with personal information, available for all users
/profile`           # user's page for editing his own profile
```

## Requirements
Must have:
* ruby
* ruby on rails

Should have:
* twitter bootsrap
* postgresql database
* test suite

Could have:
* permalinks (links like `/user/1-john-doe` or `/posts/22-my-first-post`)
* AJAX for creating/deleting items
* fragment caching (think over invalidation)

This repository already has a desired set of gems.
Please fork it and then create a pull request when work is done.
