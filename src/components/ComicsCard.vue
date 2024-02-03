<script>
export default {
  name: "ComicsCard",
};
</script>
<template>
  <div class="container">
    <div class="row">
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
      <div class="col-2">
        <img
          src="https://www.coverbrowser.com/image/action-comics/1-1.jpg"
          alt=""
        />
        <p>Batman</p>
      </div>
    </div>
  </div>
</template>
<style>
.container {
  display: flex;
  justify-content: center;
}
.row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  width: 70%;
  & p {
    color: var(--dc-light);
  }
  & .col-2 {
    width: calc(100% / 12 * 2);
    margin: 15px 5px;
  }
  & img {
    width: 180px;
  }
}
</style>
