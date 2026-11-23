# Agreement.new

Send PDFs for e-signature, track signing progress, and download signed copies. Ask Claude to send a saved draft, check who still needs to sign, or remind pending signers. Recipients sign in Agreement.new, not in Claude.

## Connect

Open the plugin's **Connectors** tab in Claude or Cowork and connect **Agreement.new**. In Claude Code, use `/mcp` to sign in. Choose one Agreement.new team in the consent screen. You need an Agreement.new account and a team with an active subscription. The connection uses your existing permissions in the selected team.

## Try it

- “Which agreements are waiting for signatures, and who still needs to sign?”
- “Send the saved Consulting Agreement draft for signing. Ask me for the recipients and confirm before sending.”
- “Find the signed Renewal Agreement and give me a download link.”

For a new PDF, use the temporary upload link to add it directly in Agreement.new. Confirm the document and recipients before sending invitations or reminders; those emails cannot be recalled.

## Privacy and support

The plugin runs no local code. It connects only to `https://agreement.new/mcp` and uses OAuth rather than collecting credentials in chat. The connector sends task-specific details such as search terms, document references, and signer names and email addresses to Agreement.new. It returns relevant agreement and signing details, and short-lived links when requested. Sending invitations or reminders delivers email to the recipients; Agreement.new records actions in the team's audit log. The bundle has no separate storage or telemetry.

See the [Privacy Policy](https://agreement.new/privacy), [Terms of Service](https://agreement.new/terms), and [Claude connection guide](https://agreement.new/docs/connect-claude). For help, [contact Agreement.new](https://agreement.new/contact) or email hello@agreement.new.
