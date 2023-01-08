# header

## Request Header

- Accept（浏览器可接受的数据格式）
- Accept-Encoding（浏览器可接受的压缩算法，如：gzip）
- Accept-Language（浏览器可接受的语言，如：zh-CN）
- Cache-Control（控制缓存时效性）
- Connection（链接方式，如是keep-alive，则会复用链接）
- Host（Http访问使用的域名）
- If-Modified-Since（上次访问时的更改时间，如果服务端认为此时间后自己没有更新，则给出304响应）
- If-None-Match（上次访问时使用的E-Tag，通常是页面的信息摘要，这个比更改时间更准确一些）
- User-Agent（客户端标识）
- cookie（客户端存储的cookie字符串）
- Content-type（发送数据的格式，如：application/json）

## Response Header

- Cache-Control（缓存控制，用于通知缓存保存的时间，max-age=0，表示不要缓存）
- Connection（链接类型，keep-alive，表示复用）
- Content-Encoding（内容编码方式，gzip）
- Content-Length（内容长度，有利于浏览器判断内容是否已经结束）
- Content-Tyoe（内容类型，所有请求网页都是text/html）
- Date（当前服务器时间）
- ETag（页面信息摘要，判断是否重新取回页面）
- Expires（过期时间，用于判断下次请求是否需要到服务端取回页面）
- Keep-Alive（保持链接不断是需要的信息，timeout=5，max=100）
- Last-Modified（页面上次修改时间，资源的最后修改时间）
- Server（服务端软件类型）
- Ser-Cookie（设置cookie，可以存多个）
- Via（服务器的请求链路）
