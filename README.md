### PG15-POSTGIS3

Con esta imagen podemos tener un postgresql 15 con postgis 3 y usar datos especiales

```bash
docker build . -t pg15-postgis3:lastest
docker tag pg15-postgis3:lastest cabupy/pg15-postgis3:latest
docker push cabupy/pg15-postgis3:latest
```

### Author

- Carlos Vallejos