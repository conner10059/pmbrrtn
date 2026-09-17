<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%20%E7%A7%91%E6%99%AE%E7%BB%86%E8%8F%8C%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E5%92%8C%E7%99%BB3%E7%9A%84%E5%8C%BA%E5%88%AB-%E6%8A%A5%E5%85%B3%E8%AE%BA%E5%9D%9B.md?/qek
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f7ceb727ada88cbbf7f49105580aa95d038e6d45?/UyS
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E4%B8%93%E6%A0%8F%E6%9C%88%E5%BA%A6%E8%AF%84%E6%B5%8B%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB1%E7%99%BB2%E7%99%BB3%E6%98%AF%E4%BB%80%E4%B9%88-%E8%A7%86%E9%87%8E%E8%B4%A2%E7%BB%8F.md
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5bcdabb6229c26255935225f5fb9f71aa2666d92
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5bcdabb6229c26255935225f5fb9f71aa2666d92?/0b=ojd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5bcdabb6229c26255935225f5fb9f71aa2666d92?/lFj
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6d2fcc823dacafbeb1b5f36ddd26ea3544df424d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6d2fcc823dacafbeb1b5f36ddd26ea3544df424d?/Yw=DHR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6d2fcc823dacafbeb1b5f36ddd26ea3544df424d?/W0U
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e70347ec02f1224fc0d588e38aa3cb02ad71d528
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e70347ec02f1224fc0d588e38aa3cb02ad71d528?/ND=Rvs
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e70347ec02f1224fc0d588e38aa3cb02ad71d528?/OMp
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9bbe6be41fa263a0206ebd9038c8393c84568778
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9bbe6be41fa263a0206ebd9038c8393c84568778?/u1=Iqx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9bbe6be41fa263a0206ebd9038c8393c84568778?/9c6
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3a31af9017028db3a6a2f8657479a330c7003e9c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3a31af9017028db3a6a2f8657479a330c7003e9c?/lR=L9G
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3a31af9017028db3a6a2f8657479a330c7003e9c?/wPN
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b47ceb36e2aca15ab6c443264862f6671a85217d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b47ceb36e2aca15ab6c443264862f6671a85217d?/ZJ=nno
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b47ceb36e2aca15ab6c443264862f6671a85217d?/gAe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c4869e3f8158e72ae87eea260bdb661b8efcd3e2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c4869e3f8158e72ae87eea260bdb661b8efcd3e2?/zM=dBI
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c4869e3f8158e72ae87eea260bdb661b8efcd3e2?/TxR
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/84530cd8a73685b217113d4997c2c8bdb12f4996
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/84530cd8a73685b217113d4997c2c8bdb12f4996?/JD=XAU
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/84530cd8a73685b217113d4997c2c8bdb12f4996?/nHk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/17289223c5e00c236a44a54bfa65165c43ab9e9c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/17289223c5e00c236a44a54bfa65165c43ab9e9c?/zG=qXu
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/17289223c5e00c236a44a54bfa65165c43ab9e9c?/a4X
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e2a9bf643d47d7aa7faa72ba562a4f8b36453ec
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e2a9bf643d47d7aa7faa72ba562a4f8b36453ec?/tm=6kY
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e2a9bf643d47d7aa7faa72ba562a4f8b36453ec?/NrL
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d2b288348b89beece2abbccb53befabb0a00ede4
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d2b288348b89beece2abbccb53befabb0a00ede4?/Ku=4v9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d2b288348b89beece2abbccb53befabb0a00ede4?/8b5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/22bf1daf10ae117d17257d7baf2ace478520084d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/22bf1daf10ae117d17257d7baf2ace478520084d?/LC=QNo
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/22bf1daf10ae117d17257d7baf2ace478520084d?/MqK
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/415247d5030f94ea2a2f1931124109f85dabd5b3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/415247d5030f94ea2a2f1931124109f85dabd5b3?/uy=8S9
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/415247d5030f94ea2a2f1931124109f85dabd5b3?/iCf
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2598e7a9c41bf894d8caa7564dbddf7c8585b925
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2598e7a9c41bf894d8caa7564dbddf7c8585b925?/uf=FwJ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2598e7a9c41bf894d8caa7564dbddf7c8585b925?/zTw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d4e5eaa80675ec263ce77d344da1c1de1170d561
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d4e5eaa80675ec263ce77d344da1c1de1170d561?/Kl=bpJ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d4e5eaa80675ec263ce77d344da1c1de1170d561?/ImG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/03949de11f020304c9970a50b9b47db8ec5e9550
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/03949de11f020304c9970a50b9b47db8ec5e9550?/Yv=Ckr
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/03949de11f020304c9970a50b9b47db8ec5e9550?/X0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/23288ab814c227f071b077bfe6586f6e9fdfe53b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/23288ab814c227f071b077bfe6586f6e9fdfe53b?/CT=XeO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/23288ab814c227f071b077bfe6586f6e9fdfe53b?/nHl
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4004eec82ae557a27354af0868f646758b0905ea
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4004eec82ae557a27354af0868f646758b0905ea?/OV=Gmq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4004eec82ae557a27354af0868f646758b0905ea?/d7b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/63a6d2e101095b55c5a8f704b5e1205018b382b4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/63a6d2e101095b55c5a8f704b5e1205018b382b4?/xu=o8I
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/63a6d2e101095b55c5a8f704b5e1205018b382b4?/OrL
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e57b612c6287561b4ed5fae583119bb76778f6b8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e57b612c6287561b4ed5fae583119bb76778f6b8?/VC=aNy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e57b612c6287561b4ed5fae583119bb76778f6b8?/hB8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1ea272a9e168e0f7763a0222b57c038a0a10ba49
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1ea272a9e168e0f7763a0222b57c038a0a10ba49?/nT=NBI
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1ea272a9e168e0f7763a0222b57c038a0a10ba49?/ySv
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/eb302e75e460795a6c53201ecdace96f6795cee1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/eb302e75e460795a6c53201ecdace96f6795cee1?/h1=i5M
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/eb302e75e460795a6c53201ecdace96f6795cee1?/FiC
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/725a1142822ec47f693ab5fc0f5346c614309438
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/725a1142822ec47f693ab5fc0f5346c614309438?/mN=a1v
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/725a1142822ec47f693ab5fc0f5346c614309438?/4Y2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4ef4f6d3ef580b11c07145a17fc8e58b3c705568
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4ef4f6d3ef580b11c07145a17fc8e58b3c705568?/rl=5FZ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4ef4f6d3ef580b11c07145a17fc8e58b3c705568?/pJm
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/561bd89ee59176be540f2ccd502e096ccf866784
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/561bd89ee59176be540f2ccd502e096ccf866784?/cw=7UE
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/561bd89ee59176be540f2ccd502e096ccf866784?/e8c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8ebda923b052c581984fd84b5e164d8b8dbab86e
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8ebda923b052c581984fd84b5e164d8b8dbab86e?/5Z=3XX
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8ebda923b052c581984fd84b5e164d8b8dbab86e?/xRv
<br>
gitlab.com/EHWGW/fxleljy/-/commit/af02fd682cd9df5ff717cf781b9a81477a3bf7b2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/af02fd682cd9df5ff717cf781b9a81477a3bf7b2?/Bz=dNR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/af02fd682cd9df5ff717cf781b9a81477a3bf7b2?/kEi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/86c96ca9af0ad743a248a7d76821f68a56a08a34
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/86c96ca9af0ad743a248a7d76821f68a56a08a34?/rb=bc9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/86c96ca9af0ad743a248a7d76821f68a56a08a34?/VzT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/470c6eb38824a51552518b136997fba0479e1778
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/470c6eb38824a51552518b136997fba0479e1778?/7o=h19
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/470c6eb38824a51552518b136997fba0479e1778?/ImG
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9b2e774cdddadd964c555ba193271aa063d403d3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9b2e774cdddadd964c555ba193271aa063d403d3?/0o=vCj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9b2e774cdddadd964c555ba193271aa063d403d3?/5Z3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6367a6e593684f432d748fcb6dfade3ae8cc67a8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6367a6e593684f432d748fcb6dfade3ae8cc67a8?/hO=Icn
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6367a6e593684f432d748fcb6dfade3ae8cc67a8?/qKo
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e5c7796a53749d06d61e958d7c66012c42c87bde
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e5c7796a53749d06d61e958d7c66012c42c87bde?/Vm=Jta
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e5c7796a53749d06d61e958d7c66012c42c87bde?/9d7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7204474fe4f72126865180fc89ba61cd020634b8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7204474fe4f72126865180fc89ba61cd020634b8?/FT=QKe
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7204474fe4f72126865180fc89ba61cd020634b8?/OsM
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e0fcf6b8434b8c660015db752758e5bacf18eb04
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e0fcf6b8434b8c660015db752758e5bacf18eb04?/JK=rR8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e0fcf6b8434b8c660015db752758e5bacf18eb04?/hBf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3a6e596b7ed08a3ab07dff424e4dde531ac14579
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3a6e596b7ed08a3ab07dff424e4dde531ac14579?/vC=mTq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3a6e596b7ed08a3ab07dff424e4dde531ac14579?/W0U
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5708822e8e85da94ecce8f5155b364aa0043aa06
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5708822e8e85da94ecce8f5155b364aa0043aa06?/E2=gx0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5708822e8e85da94ecce8f5155b364aa0043aa06?/JnH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7493faa43fb4d16cd9d633afe7145cb38fef0056
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7493faa43fb4d16cd9d633afe7145cb38fef0056?/Cg=Aee
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7493faa43fb4d16cd9d633afe7145cb38fef0056?/4Y2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/33169e7d015760044ca353af4cb5693916acc033
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/33169e7d015760044ca353af4cb5693916acc033?/CQ=Nof
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/33169e7d015760044ca353af4cb5693916acc033?/rLp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/47130713fbb12f33b2dfac557f167b12b697228b
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/47130713fbb12f33b2dfac557f167b12b697228b?/2m=mnK
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/47130713fbb12f33b2dfac557f167b12b697228b?/gAe
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b28ae23d3501b85bd19158772c65eaa9a157748a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b28ae23d3501b85bd19158772c65eaa9a157748a?/b4=YWT
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b28ae23d3501b85bd19158772c65eaa9a157748a?/zTx
<br>
gitlab.com/EHWGW/fxleljy/-/commit/468a0e7292fe5d4a1da51f01e476332042ab8a35
<br>
gitlab.com/EHWGW/fxleljy/-/commit/468a0e7292fe5d4a1da51f01e476332042ab8a35?/iZ=mDa
<br>
gitlab.com/EHWGW/fxleljy/-/commit/468a0e7292fe5d4a1da51f01e476332042ab8a35?/GkE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/41fe386dbf134797d3a078fa818c1d04a5bee431
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/41fe386dbf134797d3a078fa818c1d04a5bee431?/q4=ysg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/41fe386dbf134797d3a078fa818c1d04a5bee431?/VzT
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/62ff1d8b548786d6048499a6092cf73db1254630
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/62ff1d8b548786d6048499a6092cf73db1254630?/LI=CWh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/62ff1d8b548786d6048499a6092cf73db1254630?/GkE
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1c2001a4660049af3a9d68a61dad9ed6f1c22592
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1c2001a4660049af3a9d68a61dad9ed6f1c22592?/WJ=ub2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1c2001a4660049af3a9d68a61dad9ed6f1c22592?/5Z3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fb7633ce79f41cc739eba6bf416970a0de01cf7f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fb7633ce79f41cc739eba6bf416970a0de01cf7f?/VT=uo7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fb7633ce79f41cc739eba6bf416970a0de01cf7f?/QuO
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9cb3660a61033d0f754cadc4b6ac7f92011da205
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9cb3660a61033d0f754cadc4b6ac7f92011da205?/jA=0Ei
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9cb3660a61033d0f754cadc4b6ac7f92011da205?/hBf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b4fb108c862c4c03fc5f4ba13eb429c3a04d3d20
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b4fb108c862c4c03fc5f4ba13eb429c3a04d3d20?/oZ=69n
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b4fb108c862c4c03fc5f4ba13eb429c3a04d3d20?/wQu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b6cc64c10db8b2fdcaabb7424fdf6b8488daf54a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b6cc64c10db8b2fdcaabb7424fdf6b8488daf54a?/rs=P0h
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b6cc64c10db8b2fdcaabb7424fdf6b8488daf54a?/DhB
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/172d7756c6bc91bd1229cdb9a11457ce9774ca2e
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/172d7756c6bc91bd1229cdb9a11457ce9774ca2e?/WJ=xEo
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/172d7756c6bc91bd1229cdb9a11457ce9774ca2e?/4Y2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f6f1e5cf4ac875a9ab26f5492f6aeed57294a5c1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f6f1e5cf4ac875a9ab26f5492f6aeed57294a5c1?/Ct=mah
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f6f1e5cf4ac875a9ab26f5492f6aeed57294a5c1?/NrL
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a692d8d4f03ff2b97620de3417823d97b18cd916
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a692d8d4f03ff2b97620de3417823d97b18cd916?/au=4vc
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a692d8d4f03ff2b97620de3417823d97b18cd916?/8c6
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fcd558b4b65c164e88908b9e68fe3e4878bd158b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fcd558b4b65c164e88908b9e68fe3e4878bd158b?/Y5=fMj
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fcd558b4b65c164e88908b9e68fe3e4878bd158b?/PtN
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fba33271a40f5969033151ef6daaf7396083a8e5
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fba33271a40f5969033151ef6daaf7396083a8e5?/qR=71p
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fba33271a40f5969033151ef6daaf7396083a8e5?/e8c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0bd0675d481c7dc40d00c72ca11ce18ee8a781f7
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0bd0675d481c7dc40d00c72ca11ce18ee8a781f7?/AE=LcA
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0bd0675d481c7dc40d00c72ca11ce18ee8a781f7?/zTx
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6171b804da7a9b5189a478a52552e924510069cc
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6171b804da7a9b5189a478a52552e924510069cc?/Yj=ZHE
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6171b804da7a9b5189a478a52552e924510069cc?/kEi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0c84bc0d7c39938167562ce1a71801e6cdda42a2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0c84bc0d7c39938167562ce1a71801e6cdda42a2?/M3=xHS
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0c84bc0d7c39938167562ce1a71801e6cdda42a2?/1Vz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b664d18d61bfe3773ac8f1fc6742079a3c965adb
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b664d18d61bfe3773ac8f1fc6742079a3c965adb?/9q=jXe
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b664d18d61bfe3773ac8f1fc6742079a3c965adb?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6a5d246059e6342de51688c942887dc16aae52f2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6a5d246059e6342de51688c942887dc16aae52f2?/JN=0ov
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6a5d246059e6342de51688c942887dc16aae52f2?/b5Z
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d6815952d8599d21341525824abc97f33587c51
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d6815952d8599d21341525824abc97f33587c51?/b8=iPm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d6815952d8599d21341525824abc97f33587c51?/SwQ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ab8f281c012d54a01b8bf7c5e2e64e794c61d14c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ab8f281c012d54a01b8bf7c5e2e64e794c61d14c?/jA=1Ei
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ab8f281c012d54a01b8bf7c5e2e64e794c61d14c?/hBf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/14f90757fabc426a43f1a8a0ada0cce6820d66d3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/14f90757fabc426a43f1a8a0ada0cce6820d66d3?/1R=L9G
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/14f90757fabc426a43f1a8a0ada0cce6820d66d3?/SwQ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/014a7ebc9dffedc52e7ad226e14955a2b359f7ed
<br>
gitlab.com/EHWGW/fxleljy/-/commit/014a7ebc9dffedc52e7ad226e14955a2b359f7ed?/YF=9Te
<br>
gitlab.com/EHWGW/fxleljy/-/commit/014a7ebc9dffedc52e7ad226e14955a2b359f7ed?/DhB
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/959dcb2e2cea5e9a430cfad0f1511e9d9c36f5cd
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/959dcb2e2cea5e9a430cfad0f1511e9d9c36f5cd?/Eo=VtA
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/959dcb2e2cea5e9a430cfad0f1511e9d9c36f5cd?/W0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7bdb1384d32307b018fbf9ccbf1265ed79e19291
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7bdb1384d32307b018fbf9ccbf1265ed79e19291?/QO=LFZ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7bdb1384d32307b018fbf9ccbf1265ed79e19291?/pJn
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/208095122eb918b978d8ff02e479ba11baa693c5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/208095122eb918b978d8ff02e479ba11baa693c5?/3K=u5w
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/208095122eb918b978d8ff02e479ba11baa693c5?/8c6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4a31f152309a3cd8ceb1dd1a7e0f3fdf22f7c797
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4a31f152309a3cd8ceb1dd1a7e0f3fdf22f7c797?/DO=ESP
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4a31f152309a3cd8ceb1dd1a7e0f3fdf22f7c797?/vPt
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2bfe2f004bc64e59c15263f0cff08ad96613eecc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2bfe2f004bc64e59c15263f0cff08ad96613eecc?/7O=y90
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2bfe2f004bc64e59c15263f0cff08ad96613eecc?/CgA
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/51c58049820fe466ac3de86f35e476bea707ec3a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/51c58049820fe466ac3de86f35e476bea707ec3a?/Yz=QGU
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/51c58049820fe466ac3de86f35e476bea707ec3a?/TxR
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe038160ca2a416e9b97a6968b13e3024c19082c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe038160ca2a416e9b97a6968b13e3024c19082c?/Gb=Hfw
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe038160ca2a416e9b97a6968b13e3024c19082c?/ImG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a6f89f2229b82aa9337dbdf4ee787bc7a21d5ec2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a6f89f2229b82aa9337dbdf4ee787bc7a21d5ec2?/A8=ZTm
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a6f89f2229b82aa9337dbdf4ee787bc7a21d5ec2?/Z3X
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1ba0011d75b64f9750521d0faa825dce5bfaa551
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1ba0011d75b64f9750521d0faa825dce5bfaa551?/W6=H7L
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1ba0011d75b64f9750521d0faa825dce5bfaa551?/KoI
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1bc94556e8de2d8aa916a640f5cf7bd0d610dfbe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1bc94556e8de2d8aa916a640f5cf7bd0d610dfbe?/O5=zIw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1bc94556e8de2d8aa916a640f5cf7bd0d610dfbe?/Z3X
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/324eda2192f903f62ae9dd09fb7096d92f8b8ea8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/324eda2192f903f62ae9dd09fb7096d92f8b8ea8?/xv=smd
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/324eda2192f903f62ae9dd09fb7096d92f8b8ea8?/MqK
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/09bcf8d313c047ca7c8302d487b36a70a6bba469
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/09bcf8d313c047ca7c8302d487b36a70a6bba469?/wa=ruY
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/09bcf8d313c047ca7c8302d487b36a70a6bba469?/hBf
<br>
gitlab.com/EHWGW/fxleljy/-/commit/56478ab595e471545682face506247415e4a108c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/56478ab595e471545682face506247415e4a108c?/3N=2td
<br>
gitlab.com/EHWGW/fxleljy/-/commit/56478ab595e471545682face506247415e4a108c?/Z3X
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/49f124fd9d1c0c3cc2c3116fd7fd5dc8290daa7a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/49f124fd9d1c0c3cc2c3116fd7fd5dc8290daa7a?/bL=pIm
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/49f124fd9d1c0c3cc2c3116fd7fd5dc8290daa7a?/lFj
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9de5b4100d6f4e9c88648338f0a7ccf143410eba
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9de5b4100d6f4e9c88648338f0a7ccf143410eba?/6a=ab8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9de5b4100d6f4e9c88648338f0a7ccf143410eba?/UyS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bcbd01bb7db324649722fb3eb62462fb570bc551
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bcbd01bb7db324649722fb3eb62462fb570bc551?/qK=HiZ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bcbd01bb7db324649722fb3eb62462fb570bc551?/lFj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c7eefa56b3d5bdad633d289c6399c4592a71d2a0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c7eefa56b3d5bdad633d289c6399c4592a71d2a0?/HL=SjH
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c7eefa56b3d5bdad633d289c6399c4592a71d2a0?/6a4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/76e61830da8c8359b6006fb5aa806bdef5223510
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/76e61830da8c8359b6006fb5aa806bdef5223510?/wt=n7H
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/76e61830da8c8359b6006fb5aa806bdef5223510?/NrL
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/85195e851dd37e2a475f9fae31dca8b45010f16c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/85195e851dd37e2a475f9fae31dca8b45010f16c?/PW=Hor
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/85195e851dd37e2a475f9fae31dca8b45010f16c?/Ae8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/574f04e61ea881ca396cece393234012ddd2066c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/574f04e61ea881ca396cece393234012ddd2066c?/UR=Lfp
<br>
gitlab.com/EHWGW/fxleljy/-/commit/574f04e61ea881ca396cece393234012ddd2066c?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b008e00c24affde0ee55fcd2bb9cb31ce84ac81d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b008e00c24affde0ee55fcd2bb9cb31ce84ac81d?/nl=icT
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b008e00c24affde0ee55fcd2bb9cb31ce84ac81d?/CgA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/10f3de7bc4858975a8df015663e7071c7a94f627
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/10f3de7bc4858975a8df015663e7071c7a94f627?/ec=ZTn
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/10f3de7bc4858975a8df015663e7071c7a94f627?/3X1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d073a83ccfe941b26d79d01a50583122a9dbd9a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d073a83ccfe941b26d79d01a50583122a9dbd9a?/bi=T04
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d073a83ccfe941b26d79d01a50583122a9dbd9a?/qKo
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/83b12e471033676bcb2ad04c84745c4ac73cfa44
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/83b12e471033676bcb2ad04c84745c4ac73cfa44?/TD=hhi
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/83b12e471033676bcb2ad04c84745c4ac73cfa44?/b5Z
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0a3dedff5fd324dec81c85194ea2a161d003c52e
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0a3dedff5fd324dec81c85194ea2a161d003c52e?/X4=eof
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0a3dedff5fd324dec81c85194ea2a161d003c52e?/OMq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/63eb6663b56eac2db186300b035470c9441069a0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/63eb6663b56eac2db186300b035470c9441069a0?/0h=bS9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/63eb6663b56eac2db186300b035470c9441069a0?/f9d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/570db1a7923156a83cb4866870b5cf694063ac8c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/570db1a7923156a83cb4866870b5cf694063ac8c?/oI=mGk
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/570db1a7923156a83cb4866870b5cf694063ac8c?/Ae8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/83d1c8d508c3d51210b33014a80b76a598f5f3e3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/83d1c8d508c3d51210b33014a80b76a598f5f3e3?/Ax=YF8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/83d1c8d508c3d51210b33014a80b76a598f5f3e3?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/87c58d035655a95c8ebf09d665c21d9c940386fb
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/87c58d035655a95c8ebf09d665c21d9c940386fb?/LZ=zth
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/87c58d035655a95c8ebf09d665c21d9c940386fb?/W0U
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eb5ae6805f28995f6e5e4bcbb3740938294c4f36
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eb5ae6805f28995f6e5e4bcbb3740938294c4f36?/7r=sPS
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eb5ae6805f28995f6e5e4bcbb3740938294c4f36?/lFj
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8f90c9f5ac630716021b03e6475f3c43f6c53f32
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8f90c9f5ac630716021b03e6475f3c43f6c53f32?/XO=8cc
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8f90c9f5ac630716021b03e6475f3c43f6c53f32?/2W0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/664108ee88cc67125da4097371dd035fd7732ab5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/664108ee88cc67125da4097371dd035fd7732ab5?/Sm=xoY
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/664108ee88cc67125da4097371dd035fd7732ab5?/ySw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d9d6606f7c01fbb4fc5b875bbfb897758c7a6d8d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d9d6606f7c01fbb4fc5b875bbfb897758c7a6d8d?/rv=3Jr
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d9d6606f7c01fbb4fc5b875bbfb897758c7a6d8d?/gAe
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/811f5af8cd9147dd93a5a59be4dc12cbdd184511
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/811f5af8cd9147dd93a5a59be4dc12cbdd184511?/Ja=8ES
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/811f5af8cd9147dd93a5a59be4dc12cbdd184511?/RvP
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/657054811a1689fc07bb962a5610a78d4b6d0746
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/657054811a1689fc07bb962a5610a78d4b6d0746?/i8=zDd
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/657054811a1689fc07bb962a5610a78d4b6d0746?/CgA
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5616a9fb5fc7ef3d3ebfa1b26983344a9af0dde2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5616a9fb5fc7ef3d3ebfa1b26983344a9af0dde2?/n0=URs
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5616a9fb5fc7ef3d3ebfa1b26983344a9af0dde2?/RvP
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7b6cb6b675bec4450c80893a95028f54c3a35a36
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7b6cb6b675bec4450c80893a95028f54c3a35a36?/dK=D19
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时50分05秒
