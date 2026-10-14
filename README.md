# partner-integration-spec

Reference implementation for the partner webhook flow. The signed-off interface
contract is in [`docs/integration-spec.docx`](docs/integration-spec.docx).

## Notice — security proof of concept

This repository is a **proof of concept for a vulnerability reported to OpenAI**
(Bugcrowd submission `1f32f024-5a60-42db-a19f-7958496f623c`), published only to
demonstrate a delivery path to the vendor's triage team.

`docs/integration-spec.docx` carries a CSS payload in its embedded font name. If
you preview it in an affected client, the names of the documents you have open are
sent to a researcher-controlled logging endpoint that records nothing but the
request path. No code executes, and no file contents are read. Do not preview it
if that is not what you want. This repository will be deleted once the vendor's
triage is complete.
