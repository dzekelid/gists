---
name: GitHub
x-slug: github
description: GitHub brings together the worlds largest community of developers to
  discover, share, and build better software. From open source projects to private
  team repositories, were your all-in-one platform for collaborative development.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "64"
tags: Gists
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Gists
  x-api-slug: github
  description: |-
    List the authenticated user's gists or if called anonymously, this will
    return all public gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists
  tags: Gists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gists-get-openapi.md
- name: Github Add Gists
  x-api-slug: github
  description: Create a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gists-post-openapi.md
- name: Github Get Gists Public
  x-api-slug: github
  description: List all public gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/public
  tags: Gists, Public
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistspublic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistspublic-get-openapi.md
- name: Github Get Gists Starred
  x-api-slug: github
  description: List the authenticated user's starred gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/starred
  tags: Gists, Starred
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsstarred-get-openapi.md
- name: Github Delete Gists
  x-api-slug: github
  description: Delete a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsid-delete-openapi.md
- name: Github Get Gists
  x-api-slug: github
  description: Get a single gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsid-get-openapi.md
- name: Github Patch Gists
  x-api-slug: github
  description: Edit a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsid-patch-openapi.md
- name: Github Get Gists  Comments
  x-api-slug: github
  description: List comments on a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments
  tags: Gists, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcomments-get-openapi.md
- name: Github Add Gists  Comments
  x-api-slug: github
  description: Create a commen
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments
  tags: Gists, , Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcomments-post-openapi.md
- name: Github Delete Gists  Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcommentscommentid-delete-openapi.md
- name: Github Get Gists  Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcommentscommentid-get-openapi.md
- name: Github Patch Gists  Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidcommentscommentid-patch-openapi.md
- name: Github Add Gists  Forks
  x-api-slug: github
  description: Fork a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/forks
  tags: Gists, , Forks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidforks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidforks-post-openapi.md
- name: Github Delete Gists  Star
  x-api-slug: github
  description: Unstar a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/star
  tags: Gists, , Star
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidstar-delete-openapi.md
- name: Github Get Gists  Star
  x-api-slug: github
  description: Check if a gist is starred.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/star
  tags: Gists, , Star
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidstar-get-openapi.md
- name: Github Put Gists  Star
  x-api-slug: github
  description: Star a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/star
  tags: Gists, , Star
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/gistsidstar-put-openapi.md
- name: Github Get Users Username Gists
  x-api-slug: github
  description: List a users gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/gists
  tags: Users, Username, Gists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/usersusernamegists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/usersusernamegists-get-openapi.md
- name: Github
  x-api-slug: github
  description: GitHub brings together the worlds largest community of developers to
    discover, share, and build better software. From open source projects to private
    team repositories, were your all-in-one platform for collaborative development.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Gists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/gists/master/_listings/github/openapi.md
x-common:
- type: x--net-library
  url: https://github.com/octokit/octokit.net
- type: x-base
  url: https://api.github.com
- type: x-blog
  url: http://github.com/blog
- type: x-blog-rss
  url: https://github.com/blog/subscribe
- type: x-change-log
  url: https://developer.github.com/changes/
- type: x-contact-form
  url: https://github.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/github
- type: x-crunchbase
  url: https://crunchbase.com/organization/github
- type: x-developer
  url: https://developer.github.com/
- type: x-github
  url: https://github.com/github
- type: x-guides
  url: https://developer.github.com/guides/
- type: x-ios-sdk
  url: https://github.com/octokit/octokit.objc
- type: x-pricing
  url: https://github.com/pricing
- type: x-privacy
  url: http://help.github.com/privacy-policy/
- type: x-ruby-library
  url: https://github.com/octokit/octokit.rb
- type: x-security
  url: http://help.github.com/security/
- type: x-status
  url: https://status.github.com/
- type: x-terms-of-service
  url: http://help.github.com/terms-of-service/
- type: x-transparency-report
  url: https://github.com/blog/1987-github-s-2014-transparency-report
- type: x-twitter
  url: https://twitter.com/github
- type: x-webhooks
  url: https://developer.github.com/webhooks/
- type: x-website
  url: https://github.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---