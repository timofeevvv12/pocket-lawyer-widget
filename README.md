# pocket-lawyer-widget
Pocket Lawyer Widget

Use this source:
```html
<script>
    document.addEventListener("DOMContentLoaded", function() {
        var script = document.createElement('script');
        script.src = "https://cdn.jsdelivr.net/gh/timofeevvv12/pocket-lawyer-widget@main/widget.js";
        script.onload = function() {
            pocket_lawyer_widget("USER-ID", "TOPIC-ID");
        };
        document.body.appendChild(script);
    });
</script>
```
