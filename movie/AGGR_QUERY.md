```http
GET movie/_search?size=0
{
  "aggs": {
    "genre": {
      "terms": {
        "field": "genreAlt"
      }
    }
  }
}
```
