# Portal Mark 2

For Brotli Compression added `web.config` file.

```
<configuration>
  <system.webServer>
    <staticContent>
      <mimeMap fileExtension=".js" mimeType="application/javascript" />
      <mimeMap fileExtension=".css" mimeType="text/css" />
      <mimeMap fileExtension=".json" mimeType="application/json" />
      <mimeMap fileExtension=".xml" mimeType="application/xml" />
    </staticContent>
  </system.webServer>
</configuration>
```