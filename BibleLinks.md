
{% assign verse1 = page.bibleTitle1 %}
{% assign bgV1 = page.bibleGatewayRef1 %}
{% assign yvV1 = page.youVersionRef1 %}
{% assign verse2 = page.bibleTitle2 %}
{% assign bgV2 = page.bibleGatewayRef2 %}
{% assign yvV2 = page.youVersionRef2 %}

{% assign bgLink1 = "https://www.biblegateway.com/passage/?search=" | append:bgV1 | append: "&version=NIV" %}
{% assign yvLink1 = "https://www.bible.com/bible/111/" | append:yvV1 | append: ".NIV" %}

{% assign bgLink2 = "https://www.biblegateway.com/passage/?search=" | append:bgV2 | append: "&version=NIV" %}
{% assign yvLink2 = "https://www.bible.com/bible/111/" | append:yvV2 | append: ".NIV" %}

[bgLink1]: {{ bgLink1 }}
[bgLink2]: {{ bgLink2 }}
[yvLink1]: {{ yvLink1 }}
[yvLink2]: {{ yvLink2 }}