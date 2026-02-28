# ASMR AI Video Creator

> An n8n automation workflow.

## Nodes Used

| # | Node Name | Type |
|---|-----------|------|
| 1 | Schedule Trigger | `n8n-nodes-base.scheduleTrigger` |
| 2 | Google Gemini Chat Model | `@n8n/n8n-nodes-langchain.lmChatGoogleGemini` |
| 3 | Generate Prompts | `@n8n/n8n-nodes-langchain.chainLlm` |
| 4 | Output Parser | `n8n-nodes-base.code` |
| 5 | Generate Cartoon Image | `n8n-nodes-base.httpRequest` |
| 6 | Wait for Image | `n8n-nodes-base.wait` |
| 7 | Download Cartoon Image | `n8n-nodes-base.httpRequest` |
| 8 | Secret Payload | `n8n-nodes-base.code` |
| 9 | JWT | `n8n-nodes-base.jwt` |
| 10 | Exchange JWT for Access Token | `n8n-nodes-base.httpRequest` |
| 11 | Generate Video (Image-to-Video) | `n8n-nodes-base.httpRequest` |
| 12 | Wait | `n8n-nodes-base.wait` |
| 13 | Get Generated Video | `n8n-nodes-base.httpRequest` |
| 14 | isDone? | `n8n-nodes-base.if` |
| 15 | isFiltered? | `n8n-nodes-base.if` |
| 16 | isError? | `n8n-nodes-base.if` |
| 17 | Convert to File | `n8n-nodes-base.convertToFile` |
| 18 | Upload a video | `n8n-nodes-base.youTube` |
| 19 | Facebook Graph API | `n8n-nodes-base.facebookGraphApi` |
| 20 | Update Status to Done | `n8n-nodes-base.googleSheets` |
| 21 | Get row(s) in sheet | `n8n-nodes-base.googleSheets` |
| 22 | HTTP Request | `n8n-nodes-base.httpRequest` |

## How to Import

1. Download the .n8n file
2. Open n8n and go to Workflows then Import from File
3. Configure required credentials

## Author

**Sean Myk Daniel Jacinto** - Portfolio: https://seanjacintoportfolio.netlify.app - GitHub: https://github.com/mykd13
