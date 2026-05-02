# Dutch Data Marketplace

Claude Code plugin marketplace for the DutchDataPlugin.

## Install

```bash
# 1. Add this marketplace (one-time)
/plugin marketplace add stromy-org/dutch-data-marketplace

# 2. Install the plugin
/plugin install dutch-data

# 3. Install dependencies (one-time)
cd ~/.claude/plugins/cache/dutch-data
npm install
uv sync
```

## Skills

| Skill | Command | Description |
|-------|---------|-------------|
| dutch-gov-data | `/dutch-data:dutch-gov-data` | Query Dutch government APIs (Tweede Kamer, Rijksoverheid, BWB, WGK, ROO) |
| pdf | `/dutch-data:pdf` | Create and process branded PDFs |
| docx | `/dutch-data:docx` | Create branded Word documents |
| pptx | `/dutch-data:pptx` | Create branded presentations |
| pptx-hd | `/dutch-data:pptx-hd` | High-fidelity branded presentations |
| mermaid | `/dutch-data:mermaid` | Generate Mermaid diagrams |

## Prerequisites

- Claude Code v2.1.49+
- Node.js 18+
- Python 3.11+ with [uv](https://docs.astral.sh/uv/)
- GitHub access: `gh auth login`

## Update

```bash
/plugin update dutch-data
```
