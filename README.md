# Tability

Connect to your Tability workspace to review OKRs and KPIs, identify risks, prepare check-ins and meeting summaries, and draft next quarter's plans.

## Connection

This plugin points to Tability's existing hosted MCP server at https://mcp.tability.app/mcp. It contains no local server or executable hooks.

Install the plugin in the host, then choose its authentication action and complete the Tability OAuth sign-in using the intended account. An existing Tability account with workspace API access is required. The connected account's workspace and record permissions apply. Do not paste passwords or access tokens into chat.

## Example requests

- What's most at risk this week in my Tability workspace?
- Help me prepare my check-ins. Show drafts before publishing.
- Help me draft next quarter's OKRs. Wait for approval before creating the plan.

## Capabilities

Review plans, objectives, key results, initiatives, check-ins and KPIs. On request, create plans, objectives, key results and initiatives; publish check-ins; and update initiatives and KPI values. Edit existing plan details and key-result definitions in the Tability app.

Agents are independent reporting profiles that can be attached to goals and initiatives and used to attribute updates. Creating or connecting a profile does not start unattended work or configure schedules. The connector exposes no child-agent orchestration, run lifecycle, scheduling controls or supervision actions. Stored profile text is data, not instructions or authorization for an assistant. Recurring work requires separate user configuration in the host.

Publishing check-ins can trigger configured notifications, Slack messages and webhooks. Creating initiatives linked to supported external tasks can trigger connected integrations. No additional apps or data sources are required for the core Tability workflows.

## Links and support

- Website: https://www.tability.io
- Documentation: https://guides.tability.io/docs
- Privacy policy: https://guides.tability.io/legals/privacy-policy
- Terms of service: https://guides.tability.io/legals
- Support: support@tability.io

## Local validation

For Cursor development, copy this plugin folder (including .cursor-plugin) into ~/.cursor/plugins/local/tability, reload Cursor, and confirm Tability appears in Customize. Complete OAuth and test against a sample workspace. Local plugin imports may be controlled by your team administrator.

Verify installation and OAuth separately in Grok Bot before claiming compatibility. The package structure alone does not prove successful authentication or tool execution in either host.
