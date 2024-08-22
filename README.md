# versions
The version management of the Escape app uses Appcast. Appcast is based on the Sparkle framework by Andy Matuschak. You can read the Sparkle documentation here: https://sparkle-project.org/documentation/publishing/.

## example
- file location : https://escapeorg.github.io/versions/versions.xml
```
<?xml version="1.0" encoding="utf-8"?>
<rss version="2.0"
  xmlns:sparkle="http://www.andymatuschak.org/xml-namespaces/sparkle">
  <channel>
    <title>Releases</title>
    <!-- v1.1.0 -->
    <item>
      <title>Android Release</title>
      <description>Bug fix</description>
      <enclosure sparkle:version="1.1.0" sparkle:os="android" url="https://play.google.com/store/apps/details?id=com.esc.escape&pcampaignid=web_share"/>
    </item>
    <item>
      <title>iOS Release</title>
      <description>Bug fix</description>
      <enclosure sparkle:version="1.1.0" sparkle:os="ios" url="https://apps.apple.com/ca/app/escape-platforms/id6477789767?ign-itscg=30200&ign-itsct=apps_box_link"/>
    </item>
  </channel>
</rss>
```
