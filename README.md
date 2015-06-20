Deploy Image plugin for Dokku
===

A plugin to allow Dokku to deploy docker images directly.

Usage
---

```bash
dokku deploy-image my-user/my-image:my-tag my-website
```

Should deploy the image with Dokku so it's available at `http://my-website.example.com`.

Installation
---

```bash
git clone https://github.com/ubuntudesign/dokku-deploy-image-plugin /var/lib/dokku/plugins/deploy-image
```
