---
aliases:
- ../../install/macos/
- /docs/grafana-cloud/agent/flow/setup/install/macos/
- /docs/grafana-cloud/monitor-infrastructure/agent/flow/setup/install/macos/
- /docs/grafana-cloud/monitor-infrastructure/integrations/agent/flow/setup/install/macos/
- /docs/grafana-cloud/send-data/agent/flow/setup/install/macos/
canonical: https://grafana.com/docs/agent/latest/flow/setup/install/macos/
description: Learn how to install Grafana AgentFlow on macOS
menuTitle: macOS
title: Install Grafana Agent Flow on macOS
weight: 400
---

# Install {{< param "PRODUCT_NAME" >}} on macOS

You can install {{< param "PRODUCT_NAME" >}} on macOS with Homebrew .

{{% admonition type="note" %}}
The default prefix for Homebrew on Intel is `/usr/local`. The default prefix for Homebrew on Apple Silicon is `/opt/Homebrew`. To verify the default prefix for Homebrew on your computer, open a terminal window and type `brew --prefix`.
{{% /admonition %}}

## Before you begin

* Install [Homebrew][] on your computer.

## Install

To install {{< param "PRODUCT_NAME" >}} on macOS, run the following commands in a terminal window.

1. Add the Grafana Homebrew tap:

   ```shell
   brew tap grafana/grafana
   ```

1. Install {{< param "PRODUCT_NAME" >}}:

   ```shell
   brew install grafana-agent-flow
   ```

## Upgrade

To upgrade {{< param "PRODUCT_NAME" >}} on macOS, run the following commands in a terminal window.

1. Upgrade {{< param "PRODUCT_NAME" >}}:

   ```shell
   brew upgrade grafana-agent-flow
   ```

1. Restart {{< param "PRODUCT_NAME" >}}:

   ```shell
   brew services restart grafana-agent-flow
   ```

## Uninstall

To uninstall {{< param "PRODUCT_NAME" >}} on macOS, run the following command in a terminal window:

```shell
brew uninstall grafana-agent-flow
```

## Next steps

- [Start {{< param "PRODUCT_NAME" >}}][Start]
- [Configure {{< param "PRODUCT_NAME" >}}][Configure]

[Homebrew]: https://brew.sh

{{% docs/reference %}}
[Start]: "/docs/agent/ -> /docs/agent/<AGENT_VERSION>/flow/setup/start-agent.md#macos"
[Start]: "/docs/grafana-cloud/ -> /docs/grafana-cloud/send-data/agent/flow/setup/start-agent.md#macos"
[Configure]: "/docs/agent/ -> /docs/agent/<AGENT_VERSION>/flow/setup/configure/configure-macos.md"
[Configure]: "/docs/grafana-cloud/ -> /docs/grafana-cloud/send-data/agent/flow/setup/configure/configure-macos.md"
{{% /docs/reference %}}
