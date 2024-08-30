🌍 *[English](README.md) ∙ [简体中文](README-zh.md)*


<a href="https://302.ai/" target="_blank">
  <img src="./public/302banner1.jpg" alt="302.ai">
</a>

> [Sponsor - 赞助]  
> <a href="https://302.ai/" target="_blank">302.AI</a>302.AI是一个汇集全球顶级品牌的AI超市，按需付费，零月费，零门槛使用各种类型AI。
>
> 新用户免费<a href="https://gpt302.saaslink.net/Y3CmW1" target="_blank">领1美元额度⚡️</a>   
> 每天5美金额度的<a href="https://weijunext-all.tools302.com?region=1&pwd=8729" target="_blank">GPT-4🤖</a>

# [SmartExcel.cc](https://www.smartExcel.cc/)

用AI在几秒钟内生成你想要的Excel公式。

[![生成Excel公式](./public/screenshot.png)](https://www.smartExcel.cc/)

## 工作原理

该项目使用[ChatGPT API](https://openai.com/api/)和具有流功能的[Vercel AI SDK](https://sdk.vercel.ai/docs)。它基于表单和用户输入构建提示，将其发送至ChatGPT API通过Vercel边缘函数，然后将响应流式传输回应用程序界面。

## 技术栈

SmartExcel构建于以下技术栈：

- Next.js – 前端/后端
- TailwindCSS – 样式
- Postgres和Prisma - 数据库和存储（[如何使用？](https://weijunext.com/article/061d8cd9-fcf3-4d9e-bd33-e257bc4f9989)）
- Next-auth - 认证（[如何使用？](https://weijunext.com/article/061d8cd9-fcf3-4d9e-bd33-e257bc4f9989)） 
- Chat GPT - 生成Excel公式
- Upstash - Redis（[如何使用？](https://weijunext.com/article/6510121c-90da-4d20-85a1-72cbbdb3983b)）
- Lemon Squeezy - 支付（[如何使用？](https://weijunext.com/article/integrate-lemonsqueezy-api)）
- Google Analytics - 访问分析（[如何使用？](https://weijunext.com/article/979b9033-188c-4d88-bfff-6cf74d28420d)）
- Docker - 开发存储（[如何使用？](https://weijunext.com/article/b33a5545-fd26-47a6-8641-3c7467fb3910)）
- Vercel - 托管

如果您对某些技术栈不熟悉，请点击上面的“如何使用”链接，阅读我的中文博客。或者到我的另一个开源仓库学习 —— [Learn Next.js Stack](https://github.com/weijunext/nextjs-learn-demos)

## 本地运行

克隆仓库后，你需要复制`.env.example`文件来创建一个`.env`文件，并填写所需字段。

然后，在命令行运行应用程序，它将在`http://localhost:3000`上可用。

```bash
pnpm i

pnpm run dev
```

## 一键部署

使用[Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples)部署示例：

[![使用Vercel部署](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/weijunext/smart-excel-ai&project-name=&repository-name=smart-excel-ai&demo-title=SmartExcel&demo-description=Generate%20the%20Excel%20formulas%20you%20need%20in%20seconds%20using%20AI.&demo-url=https://smartexcel.cc&demo-image=https://smartexcel.cc/opengraph-image.png)

## 关于我

**Full-Stack Engineer, Open-Source Next.js Artist & AI Enthusiast.**

**全栈工程师，Next.js 开源手艺人，AI降临派。**

[博客](https://weijunext.com)  
[Github](https://github.com/weijunext)  
[Twitter/X](https://x.com/weijunext)  
[Medium](https://medium.com/@weijunext)  
[掘金](https://juejin.cn/user/26044008768029)  
[知乎](https://www.zhihu.com/people/mo-mo-mo-89-12-11)  
[微信交流群](https://weijunext.com/make-a-friend)  

如果这个项目对您有帮助，请给仓库点个star，能赞助一下就更好了👇

<a href="https://www.buymeacoffee.com/weijunextz" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="请我喝咖啡" style="height: 41px !important;width: 174px !important;" ></a>


<a href="https://afdian.net/a/weijunext" target="_blank"><img src="./public/afd.png" alt="在爱发电支持我" style="height: 50px !important"></a>

<img src="./public/zs.jpeg" alt="赞赏作者" style="height: 200px; width: 200px">

## Star 记录

![Star History Chart](https://api.star-history.com/svg?repos=weijunext/smart-excel-ai&type=Date)