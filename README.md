# Bulk IP Lookup

A Python script to get IP address's data and save all of them in a MongoDB collection. Compatible with Python3.

## Usage

* Register in [IPGeoLocation.io](https://ipgeolocation.io) and get your API-KEY
* Place your API-KEY in code

```
python3 -m pip install -r requirements.txt
python3 main.py
```

## Sample Output

```
{
    "_id": "5df93aed9cff3a156575e7e5",
    "ip": "46.209.226.153",
    "continent_code": "AS",
    "continent_name": "Asia",
    "country_code2": "IR",
    "country_code3": "IRN",
    "country_name": "Iran",
    "country_capital": "Tehran",
    "state_prov": "Tehrān",
    "district": "",
    "city": "Tehran",
    "zipcode": "1313913994",
    "latitude": "35.68920",
    "longitude": "51.38900",
    "is_eu": false,
    "calling_code": "+98",
    "country_tld": ".ir",
    "languages": "fa-IR,ku",
    "country_flag": "https://ipgeolocation.io/static/flags/ir_64.png",
    "geoname_id": "112931",
    "isp": "Respina",
    "connection_type": "",
    "organization": "Respina Networks & Beyond PJSC",
    "currency": {
        "code": "IRR",
        "name": "Iranian Rial",
        "symbol": "﷼"
    },
    "time_zone": {
        "name": "Asia/Tehran",
        "offset": 3.5,
        "current_time": "2019-12-18 00:00:36.530+0330",
        "current_time_unix": 1576614636.53,
        "is_dst": false,
        "dst_savings": 1
    }
}
```
