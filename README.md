## facecent 的 Loon 资源

#### 转写自 [luestr 文档](https://github.com/luestr/ProxyResource/blob/main/README.md)

> [!CAUTION]
> 禁止在中华人民共和国境内平台公开传播本仓库内的任何内容或以此牟利！

> [!IMPORTANT]
> 本仓库提供的资源大部分引用自其他作者，并由我转写为 Loon 的配置，其余小部分配置为我自己编写。引用的资源均保留了原作者署名信息，在此感谢各位原作者。
> 
> 转载时你需要保留原作者署名信息，且遵守本仓库的 [CC BY-NC-SA 4.0](LICENSE.md) 许可协议。

***

#### 配置列表

> [!IMPORTANT]
> 如果你点击下面的链接发现跳转到了空白页面，建议恢复 Safari 为默认浏览器后重启设备。待网络完全恢复到正常状态之后，再打开 Loon，以重新下载统一链接的配置文件。

> [!NOTE]
> 下面的所有配置可直接点击链接一键添加，不要复制链接手动安装。遇到插件失效的，请先阅读[知识库](https://getupnote.com/share/notes/zSn1ShBmzNYISKcTgjXE5oHMrNf2/b6047d8b-621c-44af-bfa6-a28d35bcf928)排查。  

| 插件名称                  | 分流名称             | MaxMind 数据库       |
| :----------------------- | :------------------ | :------------------ |
| [Safari快捷搜索][1.1]      | [LAN][2.1]         | [GeoLite2][Country] |
| [Spotify去广告][1.2]       | [ChinaGeoIP][2.2]  | [GeoLite2-ASN][ASN] |
| [Bilibili每日等级任务][1.3] | [Apple][2.3]       |              
| [BoxJS配置][1.4]           | [Apple_Domain][2.4] |
| [YouTube去广告][1.5]       | [Facebook][2.5]    |
|                           | [GitHub][2.6]      |
|                           | [Google][2.7]      |
|                           | [OpenAI][2.8]      |
|                           | [Spotify][2.9]     |
|                           | [Telegram][2.10]   |
|                           | [Twitter][2.11]    |
|                           | [YouTube][2.12]    |


[Country]: https://www.nsloon.com/openloon/import?geoip=https://github.com/facecent/ProxyCent/raw/refs/heads/main/Databases/GeoLite2-Country.mmdb
[ASN]: https://www.nsloon.com/openloon/import?asn=https://github.com/facecent/ProxyCent/raw/refs/heads/main/Databases/GeoLite2-ASN.mmdb

[1.1]: https://www.nsloon.com/openloon/import?plugin=https://raw.githubusercontent.com/facecent/ProxyCent/main/Plugin/QuickSearch.plugin
[1.2]: https://www.nsloon.com/openloon/import?plugin=https://raw.githubusercontent.com/facecent/ProxyCent/main/Plugin/Spotify.plugin
[1.3]: https://www.nsloon.com/openloon/import?plugin=https://raw.githubusercontent.com/facecent/ProxyCent/main/Plugin/BilibiliDailyBonus.plugin
[1.4]: https://www.nsloon.com/openloon/import?plugin=https://raw.githubusercontent.com/facecent/ProxyCent/main/Plugin/BoxJS.plugin
[1.5]:https://www.nsloon.com/openloon/import?plugin=https://raw.githubusercontent.com/facecent/ProxyCent/main/Plugin/YouTube.plugin

[2.1]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/LAN.list
[2.2]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/ChinaGeoIP.list
[2.3]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Apple.list
[2.4]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Apple_Domain.list
[2.5]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Facebook.list
[2.6]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/GitHub.list
[2.7]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Google.list
[2.8]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/OpenAI.list
[2.9]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Spotify.list
[2.10]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Telegram.list
[2.11]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/Twitter.list
[2.12]: https://www.nsloon.com/openloon/import?rules=https://raw.githubusercontent.com/facecent/ProxyCent/main/Rule/YouTube.list

