# resume-template
Resume (CV) Template in HTML. See [resume.html](https://github.com/fadavi/resume-template/blob/master/resume.html)

[Sample](http://resume.fadavi.net)

## Templates:


* **عنوان:**
```html
<tr id="{Title-ID}">
  <td><hr></td>
  <td><a href="#{Title-ID}"><h2>{Title}</h2></a></td>
</tr>
```


* **ردیف عادی:**
```html
<tr>
  <td>{Something}</td>
  <td>{Description}</td>
</tr>
```


* **شماره پانویس در متن:**
```html
<sup><a href="#pn{N}"><strong>({N})</strong></a></sup>
```


* **پانویس:**
```html
<h6 id="pn{N}">
  <strong>({N}):</strong> {Text}
</h6>
```
