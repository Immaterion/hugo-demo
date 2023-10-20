---
title : '{{ replace .File.ContentBaseName "-" " " | title }}'
date : {{ .Date }}
draft : false

editPost:
  URL: "/content"
  Text: "Edit Post" # edit text
  appendFilePath: true # to append file path to Edit link
---