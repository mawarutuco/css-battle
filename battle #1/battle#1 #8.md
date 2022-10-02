```html
<div class="display-col">
  <div class="display-row">
    <div class="blue top-border long-rectangle"></div>
    <div class="light-blue bottom-border long-rectangle"></div>
    <div class="blue top-border long-rectangle"></div>
    <div class="light-blue bottom-border long-rectangle"></div>
    <div class="blue top-border long-rectangle"></div>
    <div class="light-blue bottom-border long-rectangle"></div>
    <div class="blue top-border long-rectangle"></div>
  </div>

  <div class="fork-plam blue"></div>
  <div class="rectangle blue"></div>
</div>
<style>
  body {
    background: #6592cf;
    margin: 0;
  }

  .display-col {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
    height: 100%;
  }

  .display-row {
    display: flex;
    position: fixed;
    top: 50px;
  }

  .blue {
    background: #060f55;
  }

  .light-blue {
    background: #6592cf;
  }

  .rectangle {
    width: 20px;
    height: 50px;
  }

  .long-rectangle {
    width: 20px;
    height: 110px;
  }

  .top-border {
    border-radius: 40px 40px 0 0;
  }

  .bottom-border {
    border-radius: 0px 0px 40px 40px;
  }

  .fork-plam {
    width: 140px;
    height: 140px;
    border-radius: 0px 0px 70px 70px;
  }
</style>
```
