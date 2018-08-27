---
swagger: "2.0"
x-collection-name: eBay
x-complete: 0
info:
  title: Ebay Get Category Tree Category Tree  Get Item Aspects For Category
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
  contact:
    name: eBay Inc.
  version: 1.0.0
host: api.ebay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /category_tree/{category_tree_id}/get_item_aspects_for_category:
    get:
      summary: Get Category Tree Category Tree  Get Item Aspects For Category
      description: 'This call returns a list of aspects that are appropriate or necessary
        for accurately describing items in the specified leaf category. Each aspect
        identifies an item attribute (for example, color) for which the seller will
        be required or encouraged to provide a value (or variation values) when offering
        an item in that category on eBay. For each aspect, getItemAspectsForCategory
        provides complete metadata, including: The aspect''s data type, format, and
        entry mode Whether the aspect is required in listings Whether the aspect can
        be used for item variations Whether the aspect accepts multiple values for
        an item Allowed values for the aspectUse this information to construct an
        interface through which sellers can enter or select the appropriate values
        for their items or item variations. Once you collect those values, include
        them as product aspects when creating inventory items using the Inventory
        API.'
      operationId: getItemAspectsForCategory
      x-api-path-slug: category-treecategory-tree-idget-item-aspects-for-category-get
      parameters:
      - in: query
        name: category_id
        description: The unique identifier of the leaf category for which aspects
          are being requested
      - in: path
        name: category_tree_id
        description: The unique identifier of the eBay category tree from which the
          specified categorys aspects are being requested
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Category
      - Tree
      - Category
      - Tree
      - ""
      - ""
      - Item
      - Aspects
      - Category
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---