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

<!-- OBJECTIVE -->
<!-- Write HTML/CSS in this editor and replicate the given target image in the least code possible. What you write here, renders as it is -->

<!-- SCORING -->
<!-- The score is calculated based on the number of characters you use (this comment included :P) and how close you replicate the image. Read the FAQS (https://cssbattle.dev/faqs) for more info. -->

<!-- IMPORTANT: remove the comments before submitting -->
```
