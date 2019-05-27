<p>[^<>]*</p>

<p>([A-Z]+[ ]*)+\.<\/p>

<p>([A-Z])(?:\s+[A-Z]+)\b.</p>

---

Replace <p> Chapters with <h3>

<p>([A-Z]\s)+\.<\/p>

<h3>$1\L$2</h3>