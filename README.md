# Link Paylaşım Sitesi
LinkTree benzeri açık kaynak kodlu link paylaşma sitesi

# Installation
Öncellikle repo'yu clone'layın

```
https://github.com/ygtdgn/link-sitesi
```

# Usage
Repo'yu istediğiniz kod editöründe açın ve index.html dosyası içinde yer alan linklerin yerine kendi sosyal medya linklerinizi yazın. İstediğiniz kadar link ekleyebilirsiz liste otomatik olarak aşağı doğru devam edecektir.

Örneğin

```
<body>
    <a href="https://www.instagram.com/kullanici-adiniz/" target="_blank">Instagram</a>
</body>

```

Sitenin rengini değiştirmek isterseniz style.css dosyasında "body" tagleri arasındaki renk kodlarını değiştirmeniz yeterli.

Örneğin

```
background: rgb(42,0,89);
background: -moz-linear-gradient(270deg, rgba(42,0,89,1) 0%, rgba(255,98,0,1) 40%, rgba(145,0,255,1) 100%);
background: -webkit-linear-gradient(270deg, rgba(42,0,89,1) 0%, rgba(255,98,0,1) 40%, rgba(145,0,255,1) 100%);
background: linear-gradient(270deg, rgba(42,0,89,1) 0%, rgba(255,98,0,1) 40%, rgba(145,0,255,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#2a0059",endColorstr="#9100ff",GradientType=1);

```

# Licence

MIT

