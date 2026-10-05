<p align="center">
  <a href="https://mixos.org">
    <img src="mixos-logo.png" alt="MixOS" width="96" height="92">
  </a>
</p>

<h1 align="center">MixOS</h1>

<p align="center">
  A free, open-source workspace you host yourself, where all your apps share one place to run.
</p>

<p align="center">
  <a href="https://mixos.org">Website</a> ·
  <a href="https://mixos.org/docs/what-is-mixos">Docs</a> ·
  <a href="https://mixos.org/docs/install">Install</a> ·
  <a href="https://mixos.org/extend">Registry</a>
</p>

---

**Building software is no longer the hard part. Running it is.**

Anyone can describe an app to an AI coding tool and have it working by the
afternoon. But every one of those apps still needs somewhere to run, a database,
sign-in, a safe place for its secrets, and a plan for when something breaks.
Multiply that by a dozen small tools, and the setup costs more than the software.

**MixOS sets all of that up once.** Your apps share one platform with sign-in,
permissions, encryption, databases, connections and scheduling already in place.
Every new app starts on solid ground, works alongside the others, and can be
shared with anyone running MixOS.

## The building blocks

A MixOS workspace is assembled, not shipped whole. You mix and match three kinds
of extension:

- **Apps**: dashboards, workflows, admin panels, reports and small utilities.
  Each one can take over the full screen or sit on the dashboard as a widget.
- **Connectors**: shared, credentialed bridges to your data sources, such as
  databases, object storage and mail servers, so each app doesn't need its own
  integration.
- **Themes**: one look across every app. Bring your own colours, type and logo
  to whitelabel the whole workspace.

Install them from the [Registry](https://mixos.org/extend), build your own, or
both.

## How it works

1. **Build it.** Write an app yourself or generate one with AI. If it runs as a
   web app, it can be a MixOS app: `/mixos convert` brings an existing one in,
   whatever framework it uses.
2. **Run it.** Deploy MixOS once, on infrastructure you already use: a laptop, a
   VPS, company servers or a managed platform. After that, adding an app is an
   install, not a deployment.
3. **Share it.** Publish to the Registry so anyone running MixOS can install it.

## What we stand for

- **Your data stays yours.** MixOS runs on your hardware. Your files and
  connector credentials never pass through a server we operate.
- **Open source, with a clear line.** The platform is licensed under MPL-2.0.
  The apps, connectors and themes you build on it are yours to license however
  you like, including commercially.
- **Free.** There is no paid tier, and you don't need an account to run it.
- **Built to work with AI.** Claude Code handles setup and scaffolding
  (`/mixos init`, `/mixos app`, `/mixos convert`). A built-in MCP server lets
  Claude answer questions using your apps' data, read-only and never beyond
  your own permissions.

## Get started

- [What is MixOS?](https://mixos.org/docs/what-is-mixos): the model, and what
  MixOS is and isn't
- [Install MixOS](https://mixos.org/docs/install): run it on your own machine
- [Convert an existing app](https://mixos.org/docs/extending/converting)
- Build an [app](https://mixos.org/docs/extending/apps), a
  [connector](https://mixos.org/docs/extending/connectors) or a
  [theme](https://mixos.org/docs/extending/themes)
- [Publish to the Registry](https://mixos.org/docs/extending/publishing)

---

<p align="center">
  <em>Let computers do computer things, so humans can do human things.</em>
</p>
