# Polhem

**English** | [繁體中文](https://github.com/polhem-dev/.github/blob/main/profile/README.zh-TW.md)

A modular .NET framework for building definition-driven business applications.

## Packages

- **[Polhem](https://github.com/polhem-dev/polhem)**: the framework. `FormSchema` definitions drive the UI layout, the
  database schema and validation. A JSON-RPC 2.0 API connects Avalonia (desktop, iOS, Android, browser), Blazor Server
  and JavaScript clients to the server, on SQL Server, PostgreSQL, MySQL, Oracle or SQLite. The successor of Bee.NET.
  [NuGet](https://www.nuget.org/profiles/Polhem)
- **[Polhem.JsonRpc](https://github.com/polhem-dev/polhem-jsonrpc)**: JSON-RPC 2.0 for .NET on System.Text.Json, with a
  transport-independent server, an ASP.NET Core endpoint and a client, plus optional payload packages for codecs,
  compression and AES-CBC-HMAC encryption. Polhem builds its API on it, but it does not depend on Polhem.
  [NuGet](https://www.nuget.org/packages?q=Polhem.JsonRpc)
- **[Polhem.OAuth2](https://github.com/polhem-dev/polhem-oauth2)**: lightweight OAuth2 sign-in for .NET, with Google,
  Facebook, LINE, Microsoft Entra ID, Auth0 and Okta. Desktop and console applications sign in through the system
  browser; ASP.NET Core and ASP.NET are supported too. The successor of Bee.OAuth2.
  [NuGet](https://www.nuget.org/packages/Polhem.OAuth2)

## The name

Named after Christopher Polhem (1661–1751), whose "mechanical alphabet" taught engineers to compose machines from
standard mechanisms.
