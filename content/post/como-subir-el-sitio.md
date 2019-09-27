---
title: "Como Subir El Sitio"
date: 2019-09-27T12:32:20-03:00
tags: ["documentacion"]
---

## Como subir el sitio a git

Para cada subida tenemos que hacer lo siguiente (después de hacer los cambios y probar en local):

1. 
{{< cmd >}}
hugo
{{< /cmd >}}
2. 
{{< cmd >}}
git add .
{{< /cmd >}}
3. 
{{< cmd >}}
git commit -m "Mensaje"
{{< /cmd >}}
4. 
{{< cmd >}}
git push origin master
{{< /cmd >}}