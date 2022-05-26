<!-- header -->
<h1 style="text-align: left; margin-top:0px;">
  Url Shortener API
</h1>

> Url shortener API with Django and django rest framework.


How Url Shortener API Works:
- You can send (POST) a full url and retrieve a small encoded one with tier.app as the base web service url.

    Eg. POST http://localhost:8000/shorten-url
        with https://python.org/long-url
        result: https://karnameh.app/sY6f3J (6 digits id)
    
- You can get the original url with the encoded url on a GET request (done in previous step)

    Eg. GET https://karnameh.app/sY6f3J
        result: https://python.org/long-url
        

<br><br>


<br><br>

## USAGE
#### 1. Endpoint List
URI Example: `http://localhost:8000/shorten-url/`
(Eg. body: {'url':'https://www.epochconverter.com/')

| | Available Methods | URI | Example URL |
| -: | :- | :- | -: |
| | | | |
| | **Project Endpoints** | | |
| 1. | `POST` | `shorten-url/` | `http://localhost:8000/shorten-url` |
| 2. | `GET`  | `/<short_id>` | `http://localhost:8000/<short_id>` |


<br>
# urlShortner
