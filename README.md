# pranav.com.au marketplace

Claude Code plugin marketplace.

## Plugins

| Plugin | Description |
|--------|-------------|
| [product-wiki](https://github.com/esxr/product-wiki) | Self-healing DAG of LLM-authored wiki pages synced with your codebase |
| [builder](https://github.com/esxr/builder) | Recursive task orchestrator with parallel agent execution |

## Install

Add to your Claude Code settings:
```json
{
  "extraKnownMarketplaces": {
    "pranav.com.au": {
      "source": {
        "source": "github",
        "repo": "esxr/marketplace"
      }
    }
  }
}
```
