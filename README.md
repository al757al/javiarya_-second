## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/javiarya/second/master/Eternity)
- [Clash](https://raw.githubusercontent.com/javiarya/second/master/Eternity.yaml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/javiarya/second@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/javiarya/second@master/Eternity.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `92`
<details>
  <summary>展开复制节点</summary>

    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.230.66.40:443#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A116
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.228.30.25:443#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A103
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@52.221.240.172:443#%F0%9F%87%B8%F0%9F%87%AC%20%E6%96%B0%E5%8A%A0%E5%9D%A111
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAzMjgwMDciLCJhZGQiOiIxNDAuODMuNjMuMzgiLCJwb3J0IjoiMjQ0NDUiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTRjNWVmMzctNGQ4Mi00OWY5LWM2MjQtZjAxMjU5Mzc0YTE3IiwiYWlkIjoiNjQiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_127
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzAzMjg0ODAiLCJhZGQiOiIxNjUuMTU0LjI0Ni4xMDMiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNThjZTJhNDYtOGZhZS0zM2M4LWEzMjMtMTExMWFjZThhNGY1IiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9hZG9iZSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1663#JP_67
    ssr://anAyLnZmdW4uaWN1OjQ0MzphdXRoX2FlczEyOF9zaGExOmFlcy0yNTYtY2ZiOnBsYWluOmRubDFibTFsLz9ncm91cD1VMU5TVUhKdmRtbGtaWEkmcmVtYXJrcz1TbEJmTlRJdU1Ua3pMalkyTGpFeU0xOHdNekkzTWpBeU16Sm1aR1l0TVRBNU1uTnpKU1Umb2Jmc3BhcmFtPVlXSTVNekV4TnpReU1pNXFaQzVvSlNVbCZwcm90b3BhcmFtPU1UYzBNakk2VkZSd01GTlk
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzAzMjgxMjIiLCJhZGQiOiI4LjIxOS4xNzIuMzUiLCJwb3J0IjoiODQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJiYzc0NTA1Yy00ZmI3LTQ2YTgtZmMyMy00YzQ5NjFlYzFlMTciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJhLnR3aXR0ZXIubm93LmNjIiwidGxzIjoidGxzIn0=
    trojan://b291d129-ee55-4801-a9b8-b5316e5c37b7@138.2.113.84:443?allowInsecure=1&sni=jgwcc3.gaox.ml#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29_5
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.138:805#Pool_%F0%9F%87%B8%F0%9F%87%ACSG_126
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:811#Pool_%F0%9F%87%B8%F0%9F%87%ACSG_125
    trojan://cd27884b-c5af-34ec-b75f-8248077818fe@2.hg.kr.cat77.cloud:8443?allowInsecure=1#%F0%9F%87%B0%F0%9F%87%B7%20KR%28AzadNet.t.me%29_2
    trojan://7118b5f4-0ea4-4c11-be7f-11471cb91e4a@jgwcc1.gaox.ml:443?allowInsecure=0#%F0%9F%87%AF%F0%9F%87%B5%20%E6%97%A5%E6%9C%AC%28%E6%AC%A2%E8%BF%8E%E8%AE%A2%E9%98%85Youtube%E7%A0%B4%E8%A7%A3%E8%B5%84%E6%BA%90%E5%90%9B%29
    trojan://91ef9bbb-25d9-4593-9f9e-d17e713f5aad@805hk.ok365.cyou:443?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_30
    trojan://7f9ef59e-20fb-4343-bafc-3a84fa22fe70@de01.awcloud.top:443?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_11
    trojan://ed6546d9-4aea-4aa9-a335-24e3e7427c01@jp01.awcloud.top:443?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_12
    trojan://5a035db3-34ea-48ca-9aa2-72c8229e1532@ru.mjt001.com:443?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_17
    trojan://9f0ae767-0156-460c-acd6-67cb3000faf1@bgroup.node4.t.nodelist-gfwairport1.download:50001?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_18
    trojan://265f092f-418b-30c9-a479-4800fd44dd19mielink@kaizen-hk-8.mielink-dns2.com:443?allowInsecure=1&sni=paydiu.com#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_19
    trojan://d4e41ff772c7fd45@45.11.104.94:3389?allowInsecure=1&sni=sbank.ir#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_22
    trojan://99252428-a8f3-37ba-8c73-3ba8f18a196e@zzcm10.cacbce.com:2670?allowInsecure=1&sni=sg04.thecndate.com#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_29
    trojan://7f9ef59e-20fb-4343-bafc-3a84fa22fe70@sg02.awcloud.top:443?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_10
    trojan://d2c435dd-f5d6-4b27-b2af-daddcf85b56c@58.152.47.118:443?allowInsecure=1&sni=download2hkt.windowsupdate.lol#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_33
    trojan://SyOxpKxC8u5jgNa3DCZ34y3D9CRenFcaABpYATEeqI2RSaXD76zS8YF0Owl3lZ@219.76.13.181:443?allowInsecure=1&sni=arbettp.freetrade.link#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_39
    trojan://ZRYSly2IRuFlgpZCaep3Ey3DDXqTDczO04aeC8F36OjaYSCABnA573wN8xxK9S@47.52.101.237:443?allowInsecure=1&sni=httah.freetrade.link#%F0%9F%87%AD%F0%9F%87%B0%20HK%28AzadNet.t.me%29_40
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKV80MSIsImFkZCI6IjIwLjIzOS45Mi4xMDgiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDI5NTgwNGEtMmQxOC0zYmNiLWExMTgtOWU1MDJmMWY2ZDEwIiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9hZG9iZSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKV80MiIsImFkZCI6IjI3LjEyNi4xOTIuMjE1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZhMzRhZTg0LTBhYWUtNDFkMC04NjViLTJlNzYzZjI5MjUyOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgSEsoQXphZE5ldC50Lm1lKV80MyIsImFkZCI6IjI3LjEyNi4xOTIuMjEzIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZhMzRhZTg0LTBhYWUtNDFkMC04NjViLTJlNzYzZjI5MjUyOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://share.mjj-home.com@share.softbank.mjj-home.com:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_1
    trojan://98ccbde8-a407-4d43-9463-4b0ee12e238e@ssrsub.o07.trojan.tel:80?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_3
    trojan://9f0ae767-0156-460c-acd6-67cb3000faf1@bgroup.node1.t.nodelist-gfwairport1.download:50001?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_4
    trojan://26188b3e-c28e-4230-8bee-53d77ff5ff49@agroup.node1.t.nodelist-gfwairport1.download:50001?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_5
    trojan://4d106bd6-5d63-475a-9986-21ad3de1cf40@jp-tk-34.fuckjdieng.uk:50340?allowInsecure=1&sni=jp-tk-34.fuckjdieng.uk#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_6
    trojan://515a3204-b835-4ee0-b6d3-4e24a61e5a7d@gzdx0.170203.xyz:14515?allowInsecure=1&sni=ru04.170203.xyz#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_7
    trojan://515a3204-b835-4ee0-b6d3-4e24a61e5a7d@gzdx1.170203.xyz:24798?allowInsecure=1&sni=sgmax03.170203.xyz#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_13
    trojan://b57f94c6-7385-47f7-9c8a-55de6098bd2b@zzjp01.fuqiangren.com:20220?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_32
    trojan://7a566d21dfcd0f12490275fd3dd3cfc4@trs09.bolab.net:443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_33
    trojan://96983eb4-c8f1-316e-ab00-500014ed3d8b@49.212.221.47:2053?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_34
    trojan://750a29bf-0a40-437f-b120-38de74ae7eaf@155.248.172.87:28443?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_35
    trojan://40c89b10235c40321e7a3cef82b53a03@trs16.bolab.net:22?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_36
    trojan://40c89b10235c40321e7a3cef82b53a03@trs17.bolab.net:22?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_37
    trojan://96983eb4-c8f1-316e-ab00-500014ed3d8b@133.167.100.203:2053?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_38
    trojan://96983eb4-c8f1-316e-ab00-500014ed3d8b@160.16.145.107:2053?allowInsecure=1#%F0%9F%87%AF%F0%9F%87%B5%20JP%28AzadNet.t.me%29_39
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKV8zMiIsImFkZCI6Ijc0LjEyMC4xNjkuMjI5IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImQ0ZDk3YWVlLWViZGEtNGE0NC1iMjA4LTliNTQxNGQ5MjAzMyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKV80MiAzIiwiYWRkIjoicXVyYW53ZWIyMy54eXoiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjhiYmQ5MWZlLWEzMGItNGUyOS1iZmM3LWMyOGE0NGMwY2I4ZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvY3VycmVudF90aW1lIiwiaG9zdCI6InF1cmFud2ViMjMueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS00Q0ROIiwiYWRkIjoiMjAzLjMwLjE5MC4xIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6IjE1NC52MnJheTMueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu944CQ5LuY6LS55o6o6I2Q77yaaHR0cHMvL3R0LnZnL3ZpcOOAkTE0NiIsImFkZCI6ImZyZ3QxLnNzci1mcmVlMi54eXoiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjkzNzlmZWEwLTAwNmQtNGZkMy04ZTM1LWQ0NWE1YWY3MmFhMiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvVU1XMzYyNjIiLCJob3N0IjoiZnJndDEuc3NyLWZyZWUyLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MSIsImFkZCI6ImFzdC5pcmNmLnNwYWNlIiwicG9ydCI6IjIwOTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiZmE1YTZmMGUtYWI5ZC00NWJmLWUzZWQtMTAyZGQ1ZmVlNmIyIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9ub2RlanMiLCJob3N0IjoiZGwuZmlsbWluby5vbmxpbmUiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@172.99.190.87:5500#US_187
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@172.99.190.61:8000#US_200
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@172.99.188.99:5003#%F0%9F%87%BA%F0%9F%87%B8%20github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%208
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@172.99.188.71:8000#US_209
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKV80NCIsImFkZCI6InF1cmFud2ViMjIueHl6IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI4YmJkOTFmZS1hMzBiLTRlMjktYmZjNy1jMjhhNDRjMGNiOGYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2N1cnJlbnRfdGltZSIsImhvc3QiOiJxdXJhbndlYjIyLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1NyIsImFkZCI6IjE3Mi42Ni40MS45OSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDRiYWIzMGItZDFkYS00MGI0LWI2NWQtZTBhM2E5OGMwZGU2IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92bWVzc3dzIiwiaG9zdCI6InNzLjIzOTAwMC54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMjgxNDkiLCJhZGQiOiI0NS45Mi4xNjMuMjIiLCJwb3J0IjoiNDQ0NDciLCJ0eXBlIjoibm9uZSIsImlkIjoiZTcwYjJkNTUtNWNjOS00OWFlLWUyMDItNmY0ZjA4ODExMzI4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yYXkiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAzMjgyODciLCJhZGQiOiIxNzIuNjcuMTMyLjE2NyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiOGJiZDkxZmUtYTMwYi00ZTI5LWJmYzctYzI4YTQ0YzBjYjhmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jdXJyZW50X3RpbWUiLCJob3N0IjoiaG9seXF1cmFuMTEuc3RvcmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My04Q0ROIiwiYWRkIjoiNjYuMjM1LjIwMC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6Ijc3LnYycmF5MS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xMDAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0IjoiY2xhc2gxLnNzci1mcmVlMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2NC05IiwiYWRkIjoiMjMuMjI3LjM4LjIwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjNWEyZDdiOC1iZjg0LTRmOTctODU3Ny1iOWI4N2YyYmFhZjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0FVSUtOOEFVIiwiaG9zdCI6Im9wbGcxLmNmY2RuMi54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggVVMoQXphZE5ldC50Lm1lKV8yIiwiYWRkIjoiNzcudjJyYXkxLnh5eiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiI3Ny52MnJheTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My01Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OS4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6Ijc3LnYycmF5MS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My03Q0ROIiwiYWRkIjoiMjAzLjI0LjEwOC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6Ijc3LnYycmF5MS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6Ijc3LnYycmF5MS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjM5IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6ImNsYXNoMS5zc3ItZnJlZTIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggX0JaX+S8r+WIqeWFuS0+8J+HuvCfh7hfVVNf576O5Zu9IDciLCJhZGQiOiIyMDMuMzAuMTkwLjE5MSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@172.99.190.149:8080#US_147
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6IjE1NC52MnJheTMueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDUg5rOV5Zu9Q0ROMS0yIiwiYWRkIjoiMTQxLjEwMS4xMTQuMTExIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyYjIxNDEyMi0xOTA2LTQyOGEtYmJiNy1hMDM5Y2JiN2NkNWMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzlKWkZEVEtFIiwiaG9zdCI6ImZyMS52MnJheTUueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDUg5rOV5Zu9Q0ROMS0zIiwiYWRkIjoiMTk4LjQxLjIxMi4xIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyYjIxNDEyMi0xOTA2LTQyOGEtYmJiNy1hMDM5Y2JiN2NkNWMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzlKWkZEVEtFIiwiaG9zdCI6ImZyMS52MnJheTUueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6og5b635Zu9XzAzMjgwMTIiLCJhZGQiOiI0NS43Ny4xNDEuMjMwIiwicG9ydCI6IjU0MDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjI3NTk2Y2MtNjdhMi00MTI3LWUyNzQtYjY1YzE5NmJhNTJmIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvOUpaRkRUS0UiLCJob3N0IjoiZnIxLnYycmF5NS54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDUg5rOV5Zu9Q0ROMS00IiwiYWRkIjoiMTQxLjEwMS4xMTUuMTAwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyYjIxNDEyMi0xOTA2LTQyOGEtYmJiNy1hMDM5Y2JiN2NkNWMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzlKWkZEVEtFIiwiaG9zdCI6ImZyMS52MnJheTUueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDUg5rOV5Zu9Q0ROMSIsImFkZCI6IjE0MS4xMDEuMTE1LjExMSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMmIyMTQxMjItMTkwNi00MjhhLWJiYjctYTAzOWNiYjdjZDVjIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii85SlpGRFRLRSIsImhvc3QiOiJmcjEudjJyYXk1Lnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS00Q0ROIDIiLCJhZGQiOiIyMDMuMzAuMTkwLjEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoiMTU0LnYycmF5My54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS01Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OS4xIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6IjE1NC52MnJheTMueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsfCfh7og5Y2i5qOu5aChXzAzMjgwMDEiLCJhZGQiOiJzaHQuaXJjZi5zcGFjZSIsInBvcnQiOiIyMDk2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImZhNWE2ZjBlLWFiOWQtNDViZi1lM2VkLTEwMmRkNWZlZTZiMiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbm9kZWpzIiwiaG9zdCI6ImRsLmZpbG1pbm8ub25saW5lIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hs/Cfh7Eg6I235YWwXzAzMjgwNzAiLCJhZGQiOiIxODguMTE0Ljk5LjExNiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODIzYzMxZGEtNzAxZi00ODNkLWIzNmUtODk2ZTVjZjA5ODdhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kcDEuc2Nwcm94eS50b3Avc2hpcmtlciIsImhvc3QiOiJmcmVlbm9kZS5kZXNpZ25ub3ZhdGlvbi1tZS53b3JrZXJzLmRldiIsInRscyI6InRscyJ9
    trojan://cb43b7c2-b744-41c5-bcc2-fd7467b332cf@140.238.205.173:443?allowInsecure=1&sni=jamnews.ir#%F0%9F%87%A6%F0%9F%87%BA%20AU%28AzadNet.t.me%29_27
    vmess://eyJ2IjoiMiIsInBzIjoifCAyLjk3TWIiLCJhZGQiOiIxODUuMjI1LjY5LjEzNCIsInBvcnQiOiI0NTA4MSIsInR5cGUiOiJub25lIiwiaWQiOiIzYzNiZmQ3NS1kYzMwLTRlNzYtODk0MC00N2UxMTM3ZTIxZjkiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiamFtbmV3cy5pciIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@169.197.141.187:5003#ZZ_277
    vmess://eyJ2IjoiMiIsInBzIjoiQ0YgVmxlc3MiLCJhZGQiOiIxc3Quc3RhcnZza2lpMndvcmxkLnRvcCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiM2M1MzBhNTctZjFmMC00ZmUwLTkyYzMtNzI4N2E1MjUxZjk3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jZjAxIiwiaG9zdCI6IjFzdC5zdGFydnNraWkyd29ybGQudG9wIiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.59:5000#Pool_%F0%9F%87%B3%F0%9F%87%B1NL_109
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.22:8888#Pool_%F0%9F%87%B3%F0%9F%87%B1NL_91
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@85.208.108.60:8000#%F0%9F%87%B8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E6%B2%99%E7%89%B9%E9%98%BF%E6%8B%89%E4%BC%AFArabic%20Computer%20System%20Co.%2022
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@134.195.196.149:7307#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29
    trojan://3e1890e7-4746-4378-89ba-10c7bbe06094@176.32.32.223:443?allowInsecure=1&sni=1.hk1997.pro#%F0%9F%87%B7%F0%9F%87%BA%20RU%28AzadNet.t.me%29_6
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.75.136.21:5001#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2019
    ss://YWVzLTI1Ni1nY206cEtFVzhKUEJ5VFZUTHRN@38.114.114.19:443#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2044
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@38.143.66.99:8118#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2046
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@172.99.190.39:5500#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%20108
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg6Ziy5aSx5pWIZ2l0aHViIFN1YkNyYXdsZXLkuK3lm71fMDMyODAwMSIsImFkZCI6IjExMS4yMy4yNTIuMjE1IiwicG9ydCI6IjM0MjE0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjQxODA0OGFmLWEyOTMtNGI5OS05YjBjLTk4Y2EzNTgwZGQyNCIsImFpZCI6IjY0IiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMS5oazE5OTcucHJvIiwidGxzIjoiIn0=
    

</details>

### 所有节点
合并节点总数: `1294`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `113`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `90`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `35`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `1`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `1401`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `221`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `308`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `26`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `36`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `46`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `276`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `47`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `35`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `1`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `169`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `250`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `292`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `50`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

