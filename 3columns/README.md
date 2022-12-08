## 對齊
### 垂直對齊
#### 整欄垂直對齊
![](./images/pic1.png)
- align-items-start
- align-items-center
- align-items-end
- [所有欄對齊範例](./vertical_alignment.html)

```html
<!--所有欄對齊範例-->
<div class="container text-center">
  <div class="row align-items-start">
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
  </div>
  <div class="row align-items-center">
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
  </div>
  <div class="row align-items-end">
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
  </div>
</div>
```

#### 單欄垂直對齊
![單欄對齊](./images/pic2.png)

- align-self-start
- align-self-center
- align-self-end
- [單欄對齊範例](./vertical_alignment_single_column.html)

```html
<div class="container text-center">
  <div class="row">
    <div class="col align-self-start">
      One of three columns
    </div>
    <div class="col align-self-center">
      One of three columns
    </div>
    <div class="col align-self-end">
      One of three columns
    </div>
  </div>
</div>
```
