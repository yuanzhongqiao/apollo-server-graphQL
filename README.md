<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><code>@apollo/server</code></h1><a id="user-content-apolloserver" class="anchor" aria-label="永久链接：@apollo/server" href="#apolloserver"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该</font></font><code>@apollo/server</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软件包是 Apollo Server 4 中新增的。以前的 Apollo Server 主要版本使用了一组以 开头的软件包名称</font></font><code>apollo-server</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，例如</font></font><code>apollo-server</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>apollo-server-express</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>apollo-server-core</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等。</font></font></p>
</blockquote>
<p dir="auto"><a href="https://badge.fury.io/js/%40apollo%2Fserver" rel="nofollow"><img src="https://camo.githubusercontent.com/37397ceb245534cff7b6a4775e8f885bd1cf4725ffcf9161c94803d4b57bf01e/68747470733a2f2f62616467652e667572792e696f2f6a732f25343061706f6c6c6f2532467365727665722e737667" alt="npm版本" data-canonical-src="https://badge.fury.io/js/%40apollo%2Fserver.svg" style="max-width: 100%;"></a>
<a href="https://circleci.com/gh/apollographql/apollo-server" rel="nofollow"><img src="https://camo.githubusercontent.com/38218922512de41a3eaea4e820be8fc3622b1dc88b82053213adc2a674c884fd/68747470733a2f2f636972636c6563692e636f6d2f67682f61706f6c6c6f6772617068716c2f61706f6c6c6f2d7365727665722e7376673f7374796c653d737667" alt="构建状态" data-canonical-src="https://circleci.com/gh/apollographql/apollo-server.svg?style=svg" style="max-width: 100%;"></a>
<a href="https://community.apollographql.com" rel="nofollow"><img src="https://camo.githubusercontent.com/d2b4896535e67d845f3f72fa3924b575c709e0555472c7ff7e2435b569c7c5d3/68747470733a2f2f696d672e736869656c64732e696f2f646973636f757273652f7374617475733f6c6162656c3d4a6f696e253230746865253230636f6d6d756e697479267365727665723d6874747073253341253246253246636f6d6d756e6974792e61706f6c6c6f6772617068716c2e636f6d" alt="加入社区" data-canonical-src="https://img.shields.io/discourse/status?label=Join%20the%20community&amp;server=https%3A%2F%2Fcommunity.apollographql.com" style="max-width: 100%;"></a>
<a href="https://discord.gg/graphos" rel="nofollow"><img src="https://camo.githubusercontent.com/ac7509cd02c28bf4615abbedb401506ba4ed022364bf26aa970278640b3c80ef/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f313032323937323338393436333638373232382e7376673f636f6c6f723d373338394438266c6162656c436f6c6f723d364137454332266c6f676f3d646973636f7264266c6f676f436f6c6f723d666666666666267374796c653d666c61742d737175617265" alt="加入我们的 Discord 服务器" data-canonical-src="https://img.shields.io/discord/1022972389463687228.svg?color=7389D8&amp;labelColor=6A7EC2&amp;logo=discord&amp;logoColor=ffffff&amp;style=flat-square" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TypeScript/JavaScript GraphQL 服务器</font></font></h2><a id="user-content-a-typescriptjavascript-graphql-server" class="anchor" aria-label="永久链接：TypeScript/JavaScript GraphQL 服务器" href="#a-typescriptjavascript-graphql-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Server 是一个</font></font><a href="https://github.com/apollographql/apollo-server"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、符合规范的 GraphQL 服务器，与任何 GraphQL 客户端（包括</font></font></strong><font style="vertical-align: inherit;"></font><a href="https://www.apollographql.com/docs/react" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Client）</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">兼容</font><font style="vertical-align: inherit;">。这是构建可以使用任何来源的数据的生产就绪、自记录的 GraphQL API 的最佳方式。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以将 Apollo 服务器用作：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">独立的 GraphQL 服务器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联合超级图</font></font><a href="https://www.apollographql.com/docs/federation/subgraphs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中子图</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的GraphQL 服务器</font></font></li>
<li><font style="vertical-align: inherit;"><a href="https://www.apollographql.com/docs/federation/" rel="nofollow"><font style="vertical-align: inherit;">联邦超级图</font></a><font style="vertical-align: inherit;">的网关</font></font><a href="https://www.apollographql.com/docs/federation/" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Server 提供了一个简单的 API，用于与任何 Node.js Web 框架或无服务器环境集成。该</font></font><code>@apollo/server</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">软件包本身附带了一个可最小配置的独立 Web 服务器，可以开箱即用地处理 CORS 和正文解析。与其他环境的集成由社区维护。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo 服务器提供：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简单的设置</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，让您的客户端开发人员可以快速开始获取数据</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">增量采用</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，使您能够根据需要添加功能</font></font></li>
<li><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与任何数据源、任何构建工具和任何 GraphQL 客户端的</font><strong><font style="vertical-align: inherit;">通用兼容性</font></strong></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生产准备就绪</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，使您能够自信地在生产中运行图形</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Server 的完整文档可在</font></font><a href="https://www.apollographql.com/docs/apollo-server/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的文档网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上找到。本自述文件展示了运行服务器（独立运行和使用 Express）的基础知识，但大多数功能仅记录在我们的文档网站上。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门：独立服务器</font></font></h2><a id="user-content-getting-started-standalone-server" class="anchor" aria-label="永久链接：入门：独立服务器" href="#getting-started-standalone-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以查看</font><font style="vertical-align: inherit;">Apollo Server 文档中的</font></font><a href="https://www.apollographql.com/docs/apollo-server/getting-started" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门指南以了解更多详细信息，包括 TypeScript 和 JavaScript 中的示例。</font></font></a><font style="vertical-align: inherit;"></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Server 的独立服务器可让您快速启动并运行 GraphQL 服务器，而无需自行设置 HTTP 服务器。它允许与 Express 集成相同的 GraphQL 逻辑配置，但不提供对服务器的 HTTP 特定行为进行细粒度调整的能力。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，安装 Apollo Server 和核心 GraphQL 算法的 JavaScript 实现：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm install @apollo/server graphql
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm install @apollo/server graphql" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，将以下内容写入</font></font><code>server.mjs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. （通过使用</font></font><code>.mjs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩展，Node 允许您</font></font><code>await</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在顶层使用关键字。）</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-kos">{</span> <span class="pl-v">ApolloServer</span> <span class="pl-kos">}</span> <span class="pl-k">from</span> <span class="pl-s">'@apollo/server'</span><span class="pl-kos">;</span>
<span class="pl-k">import</span> <span class="pl-kos">{</span> <span class="pl-s1">startStandaloneServer</span> <span class="pl-kos">}</span> <span class="pl-k">from</span> <span class="pl-s">'@apollo/server/standalone'</span><span class="pl-kos">;</span>

<span class="pl-c">// The GraphQL schema</span>
<span class="pl-k">const</span> <span class="pl-s1">typeDefs</span> <span class="pl-c1">=</span> <span class="pl-s">`#graphql</span>
<span class="pl-s">  type Query {</span>
<span class="pl-s">    hello: String</span>
<span class="pl-s">  }</span>
<span class="pl-s">`</span><span class="pl-kos">;</span>

<span class="pl-c">// A map of functions which return data for the schema.</span>
<span class="pl-k">const</span> <span class="pl-s1">resolvers</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span>
  <span class="pl-c1">Query</span>: <span class="pl-kos">{</span>
    <span class="pl-en">hello</span>: <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s">'world'</span><span class="pl-kos">,</span>
  <span class="pl-kos">}</span><span class="pl-kos">,</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>

<span class="pl-k">const</span> <span class="pl-s1">server</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">ApolloServer</span><span class="pl-kos">(</span><span class="pl-kos">{</span>
  typeDefs<span class="pl-kos">,</span>
  resolvers<span class="pl-kos">,</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-k">const</span> <span class="pl-kos">{</span> url <span class="pl-kos">}</span> <span class="pl-c1">=</span> <span class="pl-k">await</span> <span class="pl-en">startStandaloneServer</span><span class="pl-kos">(</span><span class="pl-s1">server</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s">`🚀 Server ready at <span class="pl-s1"><span class="pl-kos">${</span><span class="pl-s1">url</span><span class="pl-kos">}</span></span>`</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import { ApolloServer } from '@apollo/server';
import { startStandaloneServer } from '@apollo/server/standalone';

// The GraphQL schema
const typeDefs = `#graphql
  type Query {
    hello: String
  }
`;

// A map of functions which return data for the schema.
const resolvers = {
  Query: {
    hello: () => 'world',
  },
};

const server = new ApolloServer({
  typeDefs,
  resolvers,
});

const { url } = await startStandaloneServer(server);
console.log(`🚀 Server ready at ${url}`);" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在运行您的服务器：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>node server.mjs
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="node server.mjs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在网络浏览器中打开它打印的 URL。它将展示</font></font><a href="https://www.apollographql.com/docs/studio/explorer/sandbox/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Sandbox</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，一个用于运行 GraphQL 操作的基于 Web 的工具。尝试运行该操作</font></font><code>query { hello }</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门：Express 中间件</font></font></h2><a id="user-content-getting-started-express-middleware" class="anchor" aria-label="永久链接：入门：Express 中间件" href="#getting-started-express-middleware"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Server 的内置 Express 中间件可让您将 GraphQL 服务器作为使用</font></font><a href="https://expressjs.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Express</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（最流行的 Node.js Web 框架）构建的应用程序的一部分来运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，安装 Apollo Server、核心 GraphQL 算法的 JavaScript 实现、Express 和两个常见的 Express 中间件包：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm install @apollo/server graphql express cors body-parser
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm install @apollo/server graphql express cors body-parser" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果使用 Typescript，您可能还需要安装额外的类型声明包作为开发依赖项，以避免导入上述包时出现常见错误（即找不到模块“ </font></font><code>cors</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">”的声明文件）：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm install --save-dev @types/cors @types/express @types/body-parser
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm install --save-dev @types/cors @types/express @types/body-parser" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，将以下内容写入</font></font><code>server.mjs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. （通过使用</font></font><code>.mjs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩展，Node 允许您</font></font><code>await</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在顶层使用关键字。）</font></font></p>
<div class="highlight highlight-source-js notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">import</span> <span class="pl-kos">{</span> <span class="pl-v">ApolloServer</span> <span class="pl-kos">}</span> <span class="pl-k">from</span> <span class="pl-s">'@apollo/server'</span><span class="pl-kos">;</span>
<span class="pl-k">import</span> <span class="pl-kos">{</span> <span class="pl-s1">expressMiddleware</span> <span class="pl-kos">}</span> <span class="pl-k">from</span> <span class="pl-s">'@apollo/server/express4'</span><span class="pl-kos">;</span>
<span class="pl-k">import</span> <span class="pl-kos">{</span> <span class="pl-v">ApolloServerPluginDrainHttpServer</span> <span class="pl-kos">}</span> <span class="pl-k">from</span> <span class="pl-s">'@apollo/server/plugin/drainHttpServer'</span>
<span class="pl-k">import</span> <span class="pl-s1">express</span> <span class="pl-k">from</span> <span class="pl-s">'express'</span><span class="pl-kos">;</span>
<span class="pl-k">import</span> <span class="pl-s1">http</span> <span class="pl-k">from</span> <span class="pl-s">'http'</span><span class="pl-kos">;</span>
<span class="pl-k">import</span> <span class="pl-s1">cors</span> <span class="pl-k">from</span> <span class="pl-s">'cors'</span><span class="pl-kos">;</span>
<span class="pl-k">import</span> <span class="pl-s1">bodyParser</span> <span class="pl-k">from</span> <span class="pl-s">'body-parser'</span><span class="pl-kos">;</span>

<span class="pl-c">// The GraphQL schema</span>
<span class="pl-k">const</span> <span class="pl-s1">typeDefs</span> <span class="pl-c1">=</span> <span class="pl-s">`#graphql</span>
<span class="pl-s">  type Query {</span>
<span class="pl-s">    hello: String</span>
<span class="pl-s">  }</span>
<span class="pl-s">`</span><span class="pl-kos">;</span>

<span class="pl-c">// A map of functions which return data for the schema.</span>
<span class="pl-k">const</span> <span class="pl-s1">resolvers</span> <span class="pl-c1">=</span> <span class="pl-kos">{</span>
  <span class="pl-c1">Query</span>: <span class="pl-kos">{</span>
    <span class="pl-en">hello</span>: <span class="pl-kos">(</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s">'world'</span><span class="pl-kos">,</span>
  <span class="pl-kos">}</span><span class="pl-kos">,</span>
<span class="pl-kos">}</span><span class="pl-kos">;</span>

<span class="pl-k">const</span> <span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-en">express</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-k">const</span> <span class="pl-s1">httpServer</span> <span class="pl-c1">=</span> <span class="pl-s1">http</span><span class="pl-kos">.</span><span class="pl-en">createServer</span><span class="pl-kos">(</span><span class="pl-s1">app</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-c">// Set up Apollo Server</span>
<span class="pl-k">const</span> <span class="pl-s1">server</span> <span class="pl-c1">=</span> <span class="pl-k">new</span> <span class="pl-v">ApolloServer</span><span class="pl-kos">(</span><span class="pl-kos">{</span>
  typeDefs<span class="pl-kos">,</span>
  resolvers<span class="pl-kos">,</span>
  <span class="pl-c1">plugins</span>: <span class="pl-kos">[</span><span class="pl-v">ApolloServerPluginDrainHttpServer</span><span class="pl-kos">(</span><span class="pl-kos">{</span> httpServer <span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">]</span><span class="pl-kos">,</span>
<span class="pl-kos">}</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-k">await</span> <span class="pl-s1">server</span><span class="pl-kos">.</span><span class="pl-en">start</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-s1">app</span><span class="pl-kos">.</span><span class="pl-en">use</span><span class="pl-kos">(</span>
  <span class="pl-en">cors</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">,</span>
  <span class="pl-s1">bodyParser</span><span class="pl-kos">.</span><span class="pl-en">json</span><span class="pl-kos">(</span><span class="pl-kos">)</span><span class="pl-kos">,</span>
  <span class="pl-en">expressMiddleware</span><span class="pl-kos">(</span><span class="pl-s1">server</span><span class="pl-kos">)</span><span class="pl-kos">,</span>
<span class="pl-kos">)</span><span class="pl-kos">;</span>

<span class="pl-k">await</span> <span class="pl-k">new</span> <span class="pl-v">Promise</span><span class="pl-kos">(</span><span class="pl-kos">(</span><span class="pl-s1">resolve</span><span class="pl-kos">)</span> <span class="pl-c1">=&gt;</span> <span class="pl-s1">httpServer</span><span class="pl-kos">.</span><span class="pl-en">listen</span><span class="pl-kos">(</span><span class="pl-kos">{</span> <span class="pl-c1">port</span>: <span class="pl-c1">4000</span> <span class="pl-kos">}</span><span class="pl-kos">,</span> <span class="pl-s1">resolve</span><span class="pl-kos">)</span><span class="pl-kos">)</span><span class="pl-kos">;</span>
<span class="pl-smi">console</span><span class="pl-kos">.</span><span class="pl-en">log</span><span class="pl-kos">(</span><span class="pl-s">`🚀 Server ready at http://localhost:4000`</span><span class="pl-kos">)</span><span class="pl-kos">;</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import { ApolloServer } from '@apollo/server';
import { expressMiddleware } from '@apollo/server/express4';
import { ApolloServerPluginDrainHttpServer } from '@apollo/server/plugin/drainHttpServer'
import express from 'express';
import http from 'http';
import cors from 'cors';
import bodyParser from 'body-parser';

// The GraphQL schema
const typeDefs = `#graphql
  type Query {
    hello: String
  }
`;

// A map of functions which return data for the schema.
const resolvers = {
  Query: {
    hello: () => 'world',
  },
};

const app = express();
const httpServer = http.createServer(app);

// Set up Apollo Server
const server = new ApolloServer({
  typeDefs,
  resolvers,
  plugins: [ApolloServerPluginDrainHttpServer({ httpServer })],
});
await server.start();

app.use(
  cors(),
  bodyParser.json(),
  expressMiddleware(server),
);

await new Promise((resolve) => httpServer.listen({ port: 4000 }, resolve));
console.log(`🚀 Server ready at http://localhost:4000`);" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在运行您的服务器：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>node server.mjs
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="node server.mjs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在网络浏览器中打开它打印的 URL。它将展示</font></font><a href="https://www.apollographql.com/docs/studio/explorer/sandbox/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apollo Sandbox</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，一个用于运行 GraphQL 操作的基于 Web 的工具。尝试运行该操作</font></font><code>query { hello }</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></p>
</article></div>
