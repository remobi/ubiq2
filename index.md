---
layout: default
---
<script>
    var lang = navigator.language || navigator.userLanguage;
    if (lang.indexOf('fr') == 0)
        window.location = "{{ site.url }}{{ site.baseurl }}/fr/";
        // Other languages here
    else
        // Default to English
        window.location = "{{ site.url }}{{ site.baseurl }}/en/";
</script>
