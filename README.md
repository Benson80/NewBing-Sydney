# NewBing-Sydney
NewBing和Sydney无法使用? -> 自建cf代理,并替换wsslink

注意cfworker有额度限制,如达到额度,请自行注册小号更替使用

(1). 点击这个链接https://dash.cloudflare.com/ ，登录或注册一个 Cloudflare 账号。

(2). 在侧边栏，选择 Workers & Pages。

(3). 在打开的页面，点击 Create application。

(4). 选择 Create Worker。

(5). 给你的 worker 起一个名字，然后点击 Deploy。

(6). 在 worker 详情页面，点击 edit code。

(7). 从worker.js复制所有的代码，然后粘贴到 worker.js 中，覆盖原有的代码。然后点击 Save and deploy。

(8). 复制 worker 域名，看起来像 xxxx-xxxx-xxxx.xxxx.workers.dev（请填入域名，而不是URL：不是https://xxxx-xxxx-xxxx.xxxx.workers.dev/ ，请移除前后缀https:// 和/

(9). 在webui中将newbing的wsslink替换为"wss://域名/sydney/ChatHub",示例"wss://proxy.111111111.workers.dev/sydney/ChatHub"
