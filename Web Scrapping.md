# Web Scrapping

---

`requests` package를 import해야 한다.

    value = request.get("https://fora22.github.io")

`reuest.get` 함수를 사용하면 해당 URL에 있는 html 정보를 다 가져올 수 있다.

`value.text` 하면 text 정보만, `value.json` 하면 json 정보만, `value.headers` 하면 headers,

`value.status_code` 하면 status_code만 필터링 할 수 있다.

# Beautiful Soup

---

Python library(package)

`pip install beautifulsoup4` 를 통해 install해야한다.