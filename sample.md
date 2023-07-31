<script src="/path/to/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>
# sample

sample

- aaaa
- bbbb
- cccc

<div class="mermaid">
sequenceDiagram
    actor user
    participant app

    user ->> app: request
    app -->> user: response
</div>
