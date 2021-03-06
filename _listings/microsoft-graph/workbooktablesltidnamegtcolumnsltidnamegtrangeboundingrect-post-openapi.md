---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Range Bounding Rect
  description: 'Range: BoundingRect Gets the smallest range object that encompasses
    the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15" is
    "B2:E16".'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbooknamesltnamegtrangeboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/BoundingRect:
    post:
      summary: Range Bounding Rect
      description: 'Range: BoundingRect Gets the smallest range object that encompasses
        the given ranges. For example, the GetBoundingRect of "B2:C5" and "D10:E15"
        is "B2:E16".'
      operationId: Range:BoundingRect
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeboundingrect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Bounding
      - Rect
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