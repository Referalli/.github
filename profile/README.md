# Referalli

Attribution-first referral and affiliate programs: tracked links and coupons, partner portals, commissions, payouts and fraud review, with an API for everything.

- Docs: [referalli.com/docs](https://referalli.com/docs)
- API reference: [referalli.com/docs](https://referalli.com/docs), with the OpenAPI spec and Postman collection in [referalli-openapi](https://github.com/Referalli/referalli-openapi)
- Status: [referalli.com/status](https://referalli.com/status)

## SDKs and tools

| | Install | Source |
| --- | --- | --- |
| JavaScript / TypeScript | `npm install referalli` | [referalli-js](https://github.com/Referalli/referalli-js) |
| React | `npm install @referalli/react` | [referalli-js](https://github.com/Referalli/referalli-js) |
| Next.js | `npm install @referalli/next` | [referalli-js](https://github.com/Referalli/referalli-js) |
| Express | `npm install @referalli/express` | [referalli-js](https://github.com/Referalli/referalli-js) |
| React Native | `npm install @referalli/react-native` | [referalli-react-native](https://github.com/Referalli/referalli-react-native) |
| Python | `pip install referalli` | [referalli-python](https://github.com/Referalli/referalli-python) |
| Ruby | `gem "referalli", git: "https://github.com/Referalli/referalli-ruby"` (RubyGems soon) | [referalli-ruby](https://github.com/Referalli/referalli-ruby) |
| Go | `go get github.com/referalli/referalli-go` | [referalli-go](https://github.com/Referalli/referalli-go) |
| PHP | `composer require referalli/referalli-php` with the [VCS repository](https://github.com/Referalli/referalli-php#install) (Packagist soon) | [referalli-php](https://github.com/Referalli/referalli-php) |
| Swift (iOS, macOS) | `.package(url: "https://github.com/Referalli/referalli-swift", from: "0.1.0")` | [referalli-swift](https://github.com/Referalli/referalli-swift) |
| Kotlin / JVM | `com.github.Referalli:referalli-kotlin:0.2.0` from [JitPack](https://jitpack.io/#Referalli/referalli-kotlin) (Maven Central soon) | [referalli-kotlin](https://github.com/Referalli/referalli-kotlin) |
| Android | `com.github.Referalli:referalli-android:0.2.0` from [JitPack](https://jitpack.io/#Referalli/referalli-android) (Maven Central soon) | [referalli-android](https://github.com/Referalli/referalli-android) |
| CLI | `npm install -g @referalli/cli` | [referalli-cli](https://github.com/Referalli/referalli-cli) |
| MCP server | `npx -y @referalli/mcp` | [referalli-mcp](https://github.com/Referalli/referalli-mcp) |
| OpenAPI and Postman | [openapi.json](https://referalli.com/v1/openapi.json), [openapi.yaml](https://referalli.com/v1/openapi.yaml), [Postman collection](https://github.com/Referalli/referalli-openapi/blob/main/postman_collection.json) | [referalli-openapi](https://github.com/Referalli/referalli-openapi) |

Every SDK defaults to `https://referalli.com` and authenticates with an API key from **Settings → API keys** (`rk_test_…` for test mode).

## Contributing

These repositories are published from Referalli's main codebase, so each sync replaces their contents. Issues are welcome in any of them. See [CONTRIBUTING.md](https://github.com/Referalli/.github/blob/main/CONTRIBUTING.md) before opening a pull request.
