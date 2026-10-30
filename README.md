# dotxautomation-claude-open

The public [Claude Code](https://code.claude.com) plugin marketplace of dotX Automation s.r.l.

| Plugin | What it does |
| --- | --- |
| [dua-claude](https://github.com/dotX-Automation/dua-claude) | Lets Claude Code develop inside DUA projects: resolves the project container, executes builds, tests and nodes in it, while editing files on the host. |

## Install

The marketplace and its plugins are public GitHub repositories, so no credentials are required.

```bash
/plugin marketplace add dotX-Automation/dotxautomation-claude-open
/plugin install dua-claude@dotxautomation-claude-open
```

Updates are pulled with `/plugin marketplace update dotxautomation-claude-open`.

## Adding a plugin

Add an entry to `plugins` in `.claude-plugin/marketplace.json`, with a `url` source pointing at the plugin's public repository, and validate with `claude plugin validate --strict .` before publishing.

---

## Copyright and License

Copyright 2026 dotX Automation s.r.l.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at <http://www.apache.org/licenses/LICENSE-2.0>.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and limitations under the License.
