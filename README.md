# test_mcp_server

my test mcp server

# MCP 服务：

MCP echo服务器，用于测试

## 📦 安装与部署

1. 克隆项目： \`\`\`bash git clone https://github.com/Zongheng-Yu/mcp_test_server cd mcp-calculator \`\`\`
2. 启动服务： \`\`\`uvx mohe_mcp_server \`\`\` <sub index="1" url="https://my.oschina.net/u/5783135/blog/18499385" title="社区造数服务接入MCP｜得物技术" snippet="mcp.mount()if&nbsp;\*\*name\*\* ==&nbsp;&quot;\*\*main\*\*&quot;:&nbsp; &nbsp; uvicorn.run(app, host=&quot;0.0.0.0&quot;, port=8000)"></sub>

服务将在 \`http://0.0.0.0:8000\` 启动，支持通过 HTTP 接入。

## 🔧 使用方式

### 作为本地服务运行 \`\`\`bash uvx mohe_mcp_server \`\`\`

## 🔄 支持的操作

- \`echo(input_str)\`
- \`echo_image(command)\`

## 测试

使用 \`@modelcontextprotocol/inspector\` 工具连接服务进行调试和验证 <sub index="4" url="https://www.cnblogs.com/BNTang/p/18815937" title="一文彻底搞懂MCP：AI 大模型的标准化工具箱- BNTang" snippet="https://img2023.cnblogs.com/blog/2105804/202504/2105804-20250407223635542-1014683565.png这里我为他提供了创建仓库的权限，请将 \*\*Administration\*\*  权限设置为 \*\*Read and write\*\* 。https://img2023.cnblogs.com/blog/2105804/202504/2105804-20250407223717922-772225430.png此外，还有 \*\*编写代码的权限\*\* ，请将 \*\*Codespaces 权限\*\*  设置为 \*\*Read and write\*\* 。![](https://img2023.cnblogs.com/blog/21"></sub>。

## 📄 许可证

MIT
