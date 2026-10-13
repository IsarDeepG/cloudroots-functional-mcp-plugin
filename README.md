# CloudRoots Functional Testing

Grok Build plugin for the CloudRoots functional-testing connector.

It does not ship server code. It points Grok at the hosted MCP server.

- Server: https://mcp.cloudroots.co.in/mcp
- Docs: https://mcp.cloudroots.co.in/docs
- Privacy: https://mcp.cloudroots.co.in/privacy
- Support: Info@cloudroots.co.in
- Website: https://www.cloudroots.co.in

No sign-in. The server fetches public HTML from a URL you name, then writes, scores, and reports functional test cases. It does not click, submit, pay, or delete in Phase 1.

## Network

The only endpoint this plugin calls is `https://mcp.cloudroots.co.in/mcp`. That server then fetches the public page the user asks it to inspect.

## Credentials

None. Do not paste an API key or OAuth secret.

## License

MIT. See LICENSE.
