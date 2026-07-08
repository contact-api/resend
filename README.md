# Contact API Resend
Resend email provider for `@contact-api/core`.

[![CI](https://github.com/contact-api/resend/actions/workflows/ci.yml/badge.svg)](https://github.com/contact-api/resend/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

## Usage
```ts
import { createResendProvider } from "@contact-api/resend";
const provider = createResendProvider(); // reads RESEND_API_KEY
```

## Environment Variables
| Variable | Description |
| --- | --- |
| `RESEND_API_KEY` | Resend API key |

## License
MIT License - see [LICENSE](./LICENSE) for details.
