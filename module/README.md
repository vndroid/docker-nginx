## nginx alpine

### Upstream

- [docker-nginx](https://github.com/nginxinc/docker-nginx/tree/master/stable)

### MIME types

The [Internet Assigned Numbers Authority (IANA)](https://www.iana.org/) is responsible for all official MIME types, and you can find the most up-to-date and complete list at their [Media Types](https://www.iana.org/assignments/media-types/media-types.xhtml) page.

## Patch

Make the patch file.

```bash
diff -Naur alpine/ deluxe/ > reduce.patch
```