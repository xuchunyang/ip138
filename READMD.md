# `ip138`

## Demo

```bash
~ $ curl -s ifconfig.io | ip138 --format=jsonp | jq '.'
{
  "ret": "ok",
  "ip": "121.234.35.228",
  "data": [
    "中国",
    "江苏",
    "盐城",
    "电信"
  ]
}
```

## Usage

``` shell
~ $ ip138
ip138 - IP 地理位置查询 powered by http://www.ip138.com/api/

Usage:
    ip138 [--format=jsonp|xml|text] ip

Option:
    --format=jsonp|xml|text    The format of output (defaults to text)
```

## Links

- IP138.com 的 API: http://www.ip138.com/api/
