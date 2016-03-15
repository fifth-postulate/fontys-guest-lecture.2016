##  Template Example

```html
<span id="name">{{name}}</span>
```

```java
Template template = new Template("<span id=\\"name\\">{{name}}</span>");

Map<String, Object> model = new HashMap<String, Object>();
model.put("name", "Daan van Berkel");

template.fill(model); 
```
<!-- .element: class="fragment" -->

```html
<span id="name">Daan van Berkel</span>
```
<!-- .element: class="fragment" -->

