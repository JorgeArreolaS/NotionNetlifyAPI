﻿# NotionNetlifyAPI

This is a simple API to get Notion data hosted on Netlify

> This api is created to get notion data from the server (notion prevents to use its API from client side) and consume it from any client

- The collections data is modified to restructure some fields to make them more accessible from code-based systems
- The page contents are rendered by puppeter from the original notion site.
  - It have the option to include an original css sheet
  - It contains [IframeResizer](https://github.com/davidjbradshaw/iframe-resizer) for bettet styling pourposes
