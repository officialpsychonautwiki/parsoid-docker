### parsoid-docker

```
docker build -t foo/parsoid:latest
```

Then use in *docker-compose* et al. accordingly.

Or from command line:

```
docker run \
  -p 8142:8142 \
    -e MW_URL="http://wiki" \
    foo/parsoid
```

-- apx
