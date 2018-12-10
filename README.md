## china_domains

这是一个由 bricks 引申出的子项目

保存和维护一个必须通过中国内地IP才能访问的域名列表，一般会用于海外用户访问有地区限制的音视频内容时使用

使用方法请参考下面的说明


## Usage

* List all websites blocked by the GFW

    `$ ./bricks list`

    or just simply `$ cat gfw.bricks`

* Add a domain to BRICKS

	`$ ./bricks add 'google.com'`

* Remove a domain from BRICKS

	`$ ./bricks remove 'facebook.com'`

* Make .PAC file with BRICKS

	`$ ./bricks makpac 'SOCKS5 127.0.0.1:8964; SOCKS 127.0.0.1:8964; DIRECT'`

* Make .PAC file and launch HTTP server

	`$ ./bricks pacsrv 'SOCKS5 127.0.0.1:8964; SOCKS 127.0.0.1:8964; DIRECT'`

* Make Surge configuration file with BRICKS

	`$ ./bricks maksurge 'custom, 1.2.3.4, 443, rc4-md5, password, http://surge.run/SSEncrypt.module'`

* Make Surge configuration file and launch HTTP server

	`$ ./bricks surgesrv 'custom, 1.2.3.4, 443, rc4-md5, password, http://surge.run/SSEncrypt.module'`

* Show help infomation

	`$ ./bricks help`


## Contributing

* Fork -> features implement -> tests -> pull request

* Fork -> add domain to list -> tests -> pull request


## See also

Flora_Pac: [https://github.com/Leask/Flora_Pac](https://github.com/Leask/Flora_Pac)


## Getting help

Email / iMessage / Hangouts: i@leaskh.com
