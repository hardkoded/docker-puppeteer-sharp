# docker-puppeteer-sharp-base
Base docker images for puppeteer-sharp

## Example

```
FROM hardkoded/puppeteer-sharp-base:latest

COPY bin/Release/netcoreapp2.1/publish/ /app/
ENTRYPOINT ["dotnet", "/app/PuppeteerSharpPdfDemo-Local.dll"]
```
