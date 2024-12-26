# `api-forward` 

利用 `vercel` 反向代理 `openapi`/`coze` 等 `api` 模型接口 .

---  
## 前置
- `vercel` 帐号。 若为新建帐号, 区域建议优先选择 `Washington, D.C., USA (East) – iad1`(也可以在项目创建成功后，在`设置`-`Functions` - `Function Region` 中修改)
- 一个任意域名，虽说`vercel`部署成功后会主动分配一个`*.vercel.app`的域名, 但大陆多数是直接被墙，可以通过设置自定义域名解决。

## 一键部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/0x5c0f/api-forward)  

**注: 一键部署需要克隆到项目到自己的`github`中，如果不想关联`github`，可以通过`vercel cli`来从本地部署，详情参看文档[`Vercel CLI Overview`](https://vercel.com/docs/cli)**    


## 使用
`example.com` 为自己设置的域名  
- 访问 `https://api.example.com/openai`，代理到 `https://api.openai.com`  
- 访问 `https://api.example.com/coze`, 代理到 `https://api.coze.com`
- ...

## 其他问题 
- 其他代理方式可以参考 [`那些杂七杂八的记录`](https://blog.0x5c0f.cc/posts/linux/%E9%82%A3%E4%BA%9B%E6%9D%82%E4%B8%83%E6%9D%82%E5%85%AB%E7%9A%84%E8%AE%B0%E5%BD%95.1/#openai-api%E6%8E%A5%E5%8F%A3%E5%8F%8D%E5%90%91%E4%BB%A3%E7%90%86%E5%AE%9E%E7%8E%B0%E5%9B%BD%E5%86%85%E7%9B%B4%E6%8E%A5%E4%BD%BF%E7%94%A8)  
