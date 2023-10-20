---
title : '{{ replace .File.ContentBaseName "-" " " | title }}'
date : {{ .Date }}
draft : false

editPost:
  URL: "https://github.com/Immaterion/hugo-demo/blob/master/content"
  Text: "Edit" # edit text
  appendFilePath: true # to append file path to Edit link
---