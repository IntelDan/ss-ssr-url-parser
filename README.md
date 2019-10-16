# ss-ssr-url-parser

> ss、ssr url parser, which can decode ss\ssr url

## Environment

- python3+

## How To Use

### Just Test:

```
python3 ss_ssr_decode  ssr_url/ss_url
```

## Result Format

### ss

```
{'method': 'aes-128-ctr', 'password': 'viencoding.com', 'ip': '152.89.208.146', 'port': '2333'}
```

### ssr

```
{'ip': '152.89.208.146', 'port': '2333', 'protocol': 'auth_sha1_v4', 'method': 'aes-128-ctr', 'obfs': 'plain', 'password': 'viencoding.com'}
```

## End

That's all. Hope you have a fun to use.

## Other

### TODO

some password fail to decode, only decode part and can't decode obfs params.

### Online QRCode Generator For ss/ssr

[ss-ssr-qrcode-generator](https://viencoding.com/ss-ssr-qrcode-generator)
