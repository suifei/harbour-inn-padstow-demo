# The Harbour Inn, Padstow — 公开信息搜集纪要

- 搜集日期：2026-08-28（Asia/Shanghai）
- 原则：只记实际打开或在检索摘要中见到的原文；未亲眼见到的写「未找到」。不编造、不联系店家。
- 演示站路径：`/workspace/demos/harbour-inn-padstow/index.html`
- 注意：Padstow 另有 Harbour Hotel（Station Road）和 Harbour Kitchen / The Jetty，与本店无关，已排除。Southwold / 其他 Harbour Inn 亦排除。

---

## 1. 身份与联系方式

| 字段 | 见到的内容 | 来源 |
|---|---|---|
| 完整店名 | **The Harbour Inn** / **The Harbour Inn, Padstow** / 页内 **HARBOUR INN PADSTOW** | https://www.harbourinnpadstow.co.uk/ ；https://www.harbourinnpadstow.co.uk/contact-us |
| 地址（欢迎文） | **Strand Street, South Quay in Padstow** | 首页欢迎段 |
| 地址（联系页） | **HARBOUR INN PADSTOW / STRAND STREET / PADSTOW / PL28 8BU** | https://www.harbourinnpadstow.co.uk/contact-us |
| 演示站对外地址 | **Strand Street, South Quay, Padstow PL28 8BU**（两处拼在一起，未另编门牌号） | 上两行 |
| 电话 | 页上显示 **01841 533 148**。`tel:+441841533148` | 全站页脚；联系页 PHONE |
| 邮箱（真） | **info@harbourinnpadstow.co.uk** | 首页页脚 CONTACT；联系页 EMAIL |
| 邮箱（模板残留） | 联系页 HTML 里另有 **info@mysite.com** | 2026-08-28 `curl` https://www.harbourinnpadstow.co.uk/contact-us 。**演示站禁用，也不要念给老板** |
| 浏览器标题 | 各页均为 **Home / Contact Us / Menu / … \| My Site** | 各页 `<title>` |
| 技术栈 | Wix（`x-meta-site-id`、`generator: Wix.com Website Builder`、siteRevision 106） | 响应头与首页 HTML。**只写本纪要，演示页不提 Wix / My Site** |
| 网站 | https://harbourinnpadstow.co.uk/ → 301 → https://www.harbourinnpadstow.co.uk/ | `curl -sI` |
| 导航页 | `/` · `/live-music-nights` · `/contact-us` · `/event-list`（What's On）· `/menu` · `/blog` · `/blog-feed` · `/search` | 首页 HTML 抽出 |
| 社交账号 | 联系页有 **SOCIAL MEDIA** 标题，公开可见文字里**没有** Facebook / Instagram handle | 联系页。演示站没猜 |
| LinkedIn 转抄 | 邮箱 info@harbourinnpadstow.co.uk；电话 01841 533 148；1 人；分类 Recreational Facilities | https://linkedin.com/company/harbour-inn-padstow-limited （第三方，仅备查） |

演示站**没有**把 harbourinnpadstow.co.uk 写成「我们的官网」。这页是替换草图。

---

## 2. 他们自己的欢迎原文（首页，2026-08-28 打开）

https://www.harbourinnpadstow.co.uk/

> A traditional, family run pub tucked away on Strand Street, South Quay in Padstow.
>
> Serving freshly made & locally sourced food.
>
> A proper pub showcasing Cornwall’s speciality spirits, small batch brews plus fine wines & delicious cocktails.
>
> The perfect pub to while away the hours, whether it be a bite to eat at lunch, evening supper or a night of live acoustic music, the Harbour Inn has it all!
>
> Families & dogs are always welcome.
>
> Open 7 days a week.

另见标题：WELCOME TO THE HARBOUR INN, PADSTOW；按钮文案 take a look at our menu / VIEW OUR MENU；Happenings：LIVE MuSIc AT THE HARBOUR INN。

演示站把上面收成「我们」口吻，没有另编店主故事或开业年份。

---

## 3. 营业时间与厨房

### 3.1 官方页脚（全站重复）

**OPENING HOURS Monday - Sunday 11am - 11pm**

见于首页、联系、菜单、现场音乐、活动、博客各页页脚。演示站认这一张。

### 3.2 厨房（官方菜单页，没有菜名）

https://www.harbourinnpadstow.co.uk/menu

可见正文只有：

> OUR MENU
> our kitchen is open 12 - 3 & 5 - 8pm seven days a week
> PLEASE NOTE WE DO NOT TAKE RESERVATIONS.
> If you have any other enquiries, please do not hesitate to contact us.

**没有一道菜名、没有价格、没有 PDF。** 演示站厨房段只写钟点 + 不接受预订。没有做食品菜单。

### 3.3 第三方钟点（互相打架，页上没用）

| 来源 | 写的时间 | URL |
|---|---|---|
| Sluurpy（Updated 05 Jun 2025） | 周一至周五、周日 11:00 AM–11:00 PM；**周六 11:00 AM–10:30 PM** | https://www.sluurpy.com/en/padstow/restaurant/4903588/the-harbour-inn-padstow |
| Restaurantji（Updated Apr 08, 2025） | 周一至周六 11:00–23:00；**周日 11:00–22:30** | https://www.restaurantji.co.uk/cornwall/padstow/harbour-inn-padstow-/ |
| CAMRA | 每日 11:00am–11:00pm；食物 12:00–22:00（冬天 21:30）——与官方厨房 12–3 & 5–8 **不一致** | https://camra.org.uk/pubs/harbour-inn-padstow-139017 |
| Squaremeal | 每日 11:00–22:00；「Food is served from noon every day」；walk-ins only | https://www.squaremeal.co.uk/restaurants/harbour-inn-padstow_17035 |
| mymenuweb | 周一 11:0–22:30，其余 11:0–23:0（格式残缺） | https://mymenuweb.com/uk/restaurants/650430/ |
| Favouritetable | Monday–Sunday 11:00–23:00；地址误写 PL28 **8BL** | https://www.favouritetable.com/cornwall/harbour-inn-padstow |
| Big Red Directory | 多日 11:30 AM–11:00 PM | https://www.bigreddirectory.com/harbour-inn-padstow |

**结论：** 对外只用他们自己页脚的 11am–11pm，和菜单页厨房 12–3 & 5–8pm。

---

## 4. 现场音乐（官方，演示站采用）

https://www.harbourinnpadstow.co.uk/live-music-nights （标题 Live Music Nights \| My Site）

原文：

- **PADSTOW JAM** — Every Thursday is Open Mic Night. Play - Perform - Listen - Enjoy. Bringing Music to Padstow. From 8:30pm onwards.
- **ACOUSTIC FRIDAY'S.** — live music every Friday night from 8:30pm
- **SUNDAy Piano SESSIONS** — join our resident pianist **Johnny Holmes** playing all your favourite song requests from 3pm onwards.

活动列表页 https://www.harbourinnpadstow.co.uk/event-list ：**No events at the moment**。

博客 https://www.harbourinnpadstow.co.uk/blog 仍挂 2024-01 / 02 的义演与情人节帖（Harbour Bouys、girl power fundraiser 等）。**已过期，演示站未写。**

---

## 5. 评分（约数；未编评语）

未能打开 Google Maps 本身。TripAdvisor 英文详情页两次抓取为空。

### Google

| 数字 | 来源 | 备注 |
|---|---|---|
| **4.5/5，1,204 Google reviews** | Sluurpy 页内「Google Reviews」区块 | 2026-08-28 打开。同页顶部聚合是 3.9/5、拆分行 Google 4.3/866——与该区块不一致，**对外用带「Google reviews」字样的 4.5 / 1,204** |
| Restaurantji 4.5，165 ratings | https://www.restaurantji.co.uk/cornwall/padstow/harbour-inn-padstow-/ | 平台自有分，不是 Google |

演示站写法：**Google about 4.5 / about 1,204**。

### TripAdvisor

| 数字 | 来源 | 备注 |
|---|---|---|
| **4.4，1,336 条** | 检索摘要 / tripadvisor.cn 较早快照 | 用户任务给出的约数 |
| **4.4，1,351 条**；#2 of 18 快餐小吃（分类可能错） | 2026-08-28 打开 https://www.tripadvisor.cn/Restaurant_Review-g315948-d3470897-Reviews-The_Harbour_Inn_Padstow-Padstow_Cornwall_England.html | 地址 South Quay, Strand Street Padstow，确认是本店。条数已从 1336 涨到 1351 |
| Sluurpy「TA Trip 4.0/5，962」 | 同上 Sluurpy | 旧缓存，不采 |
| 英文 TA 详情 | https://www.tripadvisor.co.uk/Restaurant_Review-g186240-d1529935-Reviews-The_Harbour_Inn-Padstow_Cornwall_England.html 与 .com 同路径 | 本次抓取无正文 |

演示站写法：**TripAdvisor about 4.4 / about 1,336**（按任务约数；纪要记下 1351）。**没有引用任何顾客原话。**

Sluurpy 上能见到的评语原文（Liam Beard / Ian Weaving / Becky Ann / Rhea Banyard 等）**演示站没用**——任务禁止编评语，也不要求摘录。

---

## 6. 第三方点过名、演示站故意不用的菜

他们自己的 `/menu` **没有菜名**。下列只出现在目录/评语里，**页上没放**：

Restaurantji「Customers' Favorites」：Locally Caught Mussels in White Wine Sauce；Homemade Steak and Ale Pie；Sea Bass Potatoes and Veg；Beef Dripping Chips；Seafood Linguine；Roast Chicken；Garlic Prawns；Beef Sandwich；Fish and Chips；Pint of Korev。About 还写 fish finger sandwiches、crab sandwiches、porthilly mussels。

Sluurpy Popular Dishes：同上 mussels / Rattler Cider / Fish and Chips / Steak pie / Chocolate Fudge Cake with Ice Cream / Seafood linguine / Garlic Prawns。评语里还有 poutine（可改素）、crab sandwich、St Austell's Blue Ribbon（称 unique to the pub）。

Squaremeal：现场做的肉馅饼、本地鱼和贝、每日 specials、Sunday roast、儿童 miniature roasts——**不是店家菜单页原文**。

**一律不采。**

---

## 7. 店主 / 公司 / 卫生

| 项 | 结果 |
|---|---|
| 店主姓名 | **未从官方页找到**（音乐页有驻店钢琴 Johnny Holmes，不是店主） |
| 开业年份 | **未找到** |
| HARBOUR INN (PADSTOW) LIMITED | 05403572；注册地址 Harbour Inn, Strand Street, Padstow, Cornwall, PL28 8BU；成立 2005-03-24；SIC 56302；**Dissolved 2024-11-05** | https://find-and-update.company-information.service.gov.uk/company/05403572 。Datalog 仍写 Active - Proposal to Strike off，以 Companies House 为准。**页上没写** |
| 现经营主体 | **未在公开页核实**（旧公司已解散，店仍在营业） |

### 食品卫生（官方，页上没放）

https://ratings.food.gov.uk/business/en-GB/1475609

- 名称 / 地址与上文一致（Harbour Inn, Strand Street, Padstow, Cornwall PL28 8BU）
- 类型：Pub/bar/nightclub
- 检查日：**12 May 2026**
- 地方当局：Cornwall
- 处理 **Good**；清洁与设施 **Good**；管理 **Very good**
- 该 HTML **没有出现总分「5」或「4」**。演示站不猜分数，故未上页。

另：Harbour Hotel Padstow（Station Road, PL28 8DB）是另一家，FSA 1222318，勿混。

---

## 8. CAMRA 与其它未采用描述

https://camra.org.uk/pubs/harbour-inn-padstow-139017 （Cornwall Branch）

- 小酒吧，藏在港边小巷；木吧台、新石板地（冰雹淹水后换的）；航海纪念品
- 食物多半全天 12:00–22:00（冬天 21:30）
- 钢琴可供本地人随便弹；后面有台球桌
- 渔民常来；Peace (Blue) 'oss 之家
- 停车在附近码头公共停车场
- 设施勾选：Lunchtime / Evening meals、Garden、Family Friendly、Dog Friendly、Camping、Games、Real Fire、Wi Fi、Cask Ale、Quiet
- 营业：每日 11:00am–11:00pm

**以上不是店家自己的正文。** 演示站只用了与官方页重合的部分（家庭/狗、现场音乐、七天、地址电话）。Peace Oss、台球、淹水、花园、壁炉等没写。

Squaremeal 另写皮沙发、开放壁炉、后面有遮雨吸烟区、walk-ins only。Favouritetable 写舒适沙发和 log burner。Yelp 3.0（1 条）、未认领。均未上页。

---

## 9. 演示站采用 / 故意留白

**上页的：**

- 店名、Strand Street / South Quay / PL28 8BU
- 01841 533 148 与 info@harbourinnpadstow.co.uk
- 家庭经营传统酒吧；现做本地食材；康沃尔酒 / 小批量啤酒 / 葡萄酒 / 鸡尾酒；原声现场；欢迎家庭和狗；七天营业
- 11am–11pm；厨房 12–3 & 5–8pm
- 不接受预订（用他们的那句话，改成句子大小写）
- 周四 / 周五 / 周日三场音乐（官方 live-music 页）
- Google / TripAdvisor 约数
- 按钮只有 `tel:` 和 `mailto:`
- 页脚：The Harbour Inn · Padstow
- Also around（不含本店）：Lezzet, Scarborough；The Salcombe Delicatessen；The Wardroom, Salcombe；The London Inn, Padstow

**不上页的：**

- 任何菜名或价格
- 顾客引言
- info@mysite.com、Wix、My Site、「我们的官网」链接
- FSA 分数猜测、已解散公司、CAMRA 掌故、2024 博客活动
- 假表单
- Flynn / suifei / GitHub 用户名 / made with AI

---

## 10. 打开情况（2026-08-28）

| URL | 结果 |
|---|---|
| https://www.harbourinnpadstow.co.uk/ 及 /contact-us /menu /live-music-nights /event-list /blog | 已打开（Wix 大 HTML，可见文字已抽出） |
| https://www.harbourinnpadstow.co.uk/contact | 404 |
| https://www.harbourinnpadstow.co.uk/sitemap.xml | 404（robots.txt 仍指向它） |
| Google Maps | 未打开稳定公开 HTML |
| TripAdvisor 英文详情 | 抓取空；中文站已打开 |
| Facebook / Instagram 主页 | 官方可见文字无 handle，未追登录墙 |
