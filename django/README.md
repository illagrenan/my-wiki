# Django misc #

## Misc ##

Graph models:

```bash
python manage.py graph_models -a --pygraphviz -o out.png
```

## Django translation ##

Gettext instalátor pro Windows: https://mlocati.github.io/gettext-iconv-windows/

## Testing ##

### Locust ###

Homepage: [http://locust.io/](http://locust.io/)

```bash
locust -f locustfile.py -H http://example.com
# Then open browser on given address... http://localhost:8089/
```

### Boom ###

Homepage: [https://github.com/tarekziade/boom](https://github.com/tarekziade/boom)

```bash
pip install boom

# c = CONCURENCY
# n = REQUESTS
boom http://example.com:8000 -c 10 -n 100
```