# Polhem

[English](https://github.com/polhem-dev) | **繁體中文**

模組化的 .NET 框架，用來建構定義驅動的商業應用程式。

## 套件

- **[Polhem](https://github.com/polhem-dev/polhem)**：框架本體。以 `FormSchema` 定義驅動 UI 版面、資料庫結構與驗證規則；
  JSON-RPC 2.0 API 連接 Avalonia（桌面、iOS、Android、瀏覽器）、Blazor Server 與 JavaScript 用戶端，資料庫支援
  SQL Server、PostgreSQL、MySQL、Oracle、SQLite。前身是 Bee.NET。[NuGet](https://www.nuget.org/profiles/Polhem)
- **[Polhem.JsonRpc](https://github.com/polhem-dev/polhem-jsonrpc)**：以 System.Text.Json 實作的 .NET JSON-RPC 2.0 套件，
  包含與傳輸無關的伺服器、ASP.NET Core 端點與用戶端，另有選用的 payload 套件提供編碼、壓縮與 AES-CBC-HMAC 加密。
  Polhem 的 API 建立在它之上，但它本身不依賴 Polhem。[NuGet](https://www.nuget.org/packages?q=Polhem.JsonRpc)
- **[Polhem.OAuth2](https://github.com/polhem-dev/polhem-oauth2)**：輕量的 .NET OAuth2 登入套件，支援 Google、Facebook、LINE、
  Microsoft Entra ID、Auth0、Okta。桌面與主控台應用程式透過系統瀏覽器登入，也支援 ASP.NET Core 與 ASP.NET。
  前身是 Bee.OAuth2。[NuGet](https://www.nuget.org/packages/Polhem.OAuth2)

## 名稱由來

取自 Christopher Polhem（1661–1751）。他的「機械字母」教工程師用標準機構組合出機器。
