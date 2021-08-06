# Default style Format

## Table

add `.lstyle` class name to parent element

```css
.lstyle table {
  border-spacing: 0;
  border-collapse: collapse;
}

.lstyle table td,
.lstyle table th {
  padding: 6px 13px;
  border: 1px solid #dfe2e5;
}

.lstyle table th {
  text-align: left;
}

.lstyle table tr:nth-child(even) {
  background-color: #f6f8fa;
}
```

## hr

break line

```css
.lstyle hr {
  border: 0;
  height: 0;
  border-top: 1px solid rgba(0, 0, 0, 0.1);
  border-bottom: 1px solid rgba(255, 255, 255, 0.3);
}
```
