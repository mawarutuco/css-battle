```html
<div class="d-flex justify-content-center col">
  <div class="d-flex justify-content-evenly align-items-end">
    <div class="primary square-s circle-top "></div>

    <div
      class="primary square-l d-flex justify-content-center  circle-top align-items-end"
    >
      <div class="square-m circle-top secondary"></div>
    </div>

    <div class="primary square-s circle-top "></div>
  </div>

  <div class="d-flex justify-content-evenly">
    <div
      class="primary square-l circle-bottom d-flex justify-content-center align-items-start"
    >
      <div class="square-m circle-bottom secondary"></div>
    </div>

    <div
      class="primary square-l circle-bottom d-flex justify-content-center align-items-start"
    >
      <div class="square-m circle-bottom secondary"></div>
    </div>
  </div>

  <style>
    body {
      background: #f5d6b4;
    }

    .d-flex {
      display: flex;
    }

    .col {
      flex-direction: column;
      height: 100%;
    }

    .justify-content-evenly {
      justify-content: space-evenly;
    }

    .justify-content-center {
      justify-content: center;
    }

    .align-items-end {
      align-items: flex-end;
    }

    .align-items-start {
      align-items: flex-start;
    }

    .primary {
      background: #d86f45;
    }

    .secondary {
      background: #f5d6b4;
    }

    .square-l {
      width: 99.5px;
      height: 50px;
    }

    .square-m {
      width: 60px;
      height: 30px;
    }

    .square-s {
      width: 19px;
      height: 10px;
    }

    .circle-bottom {
      border-radius: 0 0 200px 200px;
    }

    .circle-top {
      border-radius: 200px 200px 0 0;
    }
  </style>
</div>
```
