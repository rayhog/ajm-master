---
title: Authentication
position: 2
parameters:
  - name:
    content:
content_markdown: >-
  You must be authenticated for all API requests. Generate an API key on the
  developer dashboard.


  Add the API key to all requests as a GET parameter.


  Nothing will work unless you include this API key

  {: .error}
left_code_blocks:
  - code_block: |-
      GET @allj fdkjf
          fkdjf{}
    title: GET REQUEST
    language:
  - code_block: |-
      dsfdsa?
      ////
      ?????
    title: Jumble
    language:
right_code_blocks:
  - code_block: |2-
       $.get("http://api.myapp.com/books/", { "token": "YOUR_APP_KEY"}, function(data) {
         alert(data);
       });
    title: JQuery
    language: javascript
  - code_block: ' curl http://api.myapp.com/books?token=YOUR_APP_KEY'
    title: Curl
    language: bash
---