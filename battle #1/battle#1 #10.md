```html

<div class="display-row middle">
  <div class="rectangle-row yellow middle-bottom"></div>
  <div class="rectangle-col yellow middle-bottom"></div>

  <div class="display-row middle">
    <div class="display-col middle">
      <div class="big-sqare"></div>
      <div class="big-sqare circle pink-purple ">
        <div class="small-sqare circle orange"></div>
      </div>
    </div>

    <div class="display-col middle">
      <div class="big-sqare circle orange heiger">
        <div class="small-sqare circle pink-purple"></div>
      </div>
      <div class="big-sqare"></div>
    </div>

    <div class="display-col middle">
      <div class="big-sqare"></div>
      <div class="big-sqare circle pink-purple">
        <div class="small-sqare circle orange"></div>
      </div>
    </div>
  </div>
</div>

<style>
  body {
    background: #62306d;
    margin: 0px;
  }

  .middle-bottom {
    position: absolute;
    transform: translate(-50%);
    bottom: 0px;
    left: 50%;
  }

  .display-row {
    display: flex;
    height: 100%;
  }

  .display-col {
    display: flex;
    flex-direction: column;
    height: 100%;
  }

  .middle {
    justify-content: center;
    align-items: center;
  }

  .rectangle-row {
    width: 300px;
    height: 100px;
  }

  .rectangle-col {
    width: 100px;
    height: 200px;
  }

  .circle {
    border-radius: 50%;
  }

  .big-sqare {
    width: 100px;
    height: 100px;
    z-index: 1;
    position: relative;
  }

  .small-sqare {
    width: 60px;
    height: 60px;
    z-index: 2;
    position: absolute;
    transform: translate(-50%, -50%);
    top: 50%;
    left: 50%;
  }

  .heiger {
  }

  .lower {
  }

  .yellow {
    background: #f7ec7d;
  }

  .pink-purple {
    background: #aa445f;
  }

  .orange {
    background: #e38f66;
  }
</style>
```
