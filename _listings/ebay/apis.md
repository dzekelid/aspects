---
name: eBay
x-slug: ebay
description: Buy and sell electronics, cars, fashion apparel, collectibles, sporting
  goods, digital cameras, baby items, coupons, and everything else on eBay, the worlds
  online marketplace
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
x-kinRank: "8"
x-alexaRank: "42"
tags: Aspects
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/aspects/master/_listings/ebay/apis.md
specificationVersion: "0.14"
apis:
- name: Ebay - Get Category Tree Category Tree  Get Item Aspects For Category
  x-api-slug: category-treecategory-tree-idget-item-aspects-for-category-get
  description: 'This call returns a list of aspects that are appropriate or necessary
    for accurately describing items in the specified leaf category. Each aspect identifies
    an item attribute (for example, color) for which the seller will be required or
    encouraged to provide a value (or variation values) when offering an item in that
    category on eBay. For each aspect, getItemAspectsForCategory provides complete
    metadata, including: The aspect''s data type, format, and entry mode Whether the
    aspect is required in listings Whether the aspect can be used for item variations
    Whether the aspect accepts multiple values for an item Allowed values for the
    aspectUse this information to construct an interface through which sellers can
    enter or select the appropriate values for their items or item variations. Once
    you collect those values, include them as product aspects when creating inventory
    items using the Inventory API.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aspects/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/aspects/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://easycron.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ebay.stack.network
- type: x-blog
  url: https://go.developer.ebay.com/dev-program-blog
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ebay
- type: x-crunchbase
  url: https://crunchbase.com/organization/leah
- type: x-developer
  url: https://go.developer.ebay.com/
- type: x-email
  url: spam@ebay.com
- type: x-email
  url: spoof@ebay.com
- type: x-github
  url: https://github.com/eBayDeveloper
- type: x-twitter
  url: https://twitter.com/eBay
- type: x-twitter
  url: https://twitter.com/ebaydev
- type: x-website
  url: https://ebay.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---