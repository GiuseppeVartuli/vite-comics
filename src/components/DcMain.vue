<script>
export default {
  name: "DcMain",
};
</script>

<template>
  <main>
    <div class="content">
      <div class="container">
        <div class="row">
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
          <div class="col-2">
            <img src="" alt="" />
            <p>Batman</p>
          </div>
        </div>
      </div>
    </div>
    <div class="shop">
      <ul>
        <li>
          <a href="#"
            ><img src="../assets/img/buy-comics-digital-comics.png" alt="" />
            DIGITAL COMICS</a
          >
        </li>
        <li>
          <a href="#"
            ><img src="../assets/img/buy-comics-merchandise.png" alt="" /> DC
            MERCHANDISE</a
          >
        </li>
        <li>
          <a href="#"
            ><img src="../assets/img/buy-comics-shop-locator.png" alt="" />
            COMIC SHOP LOCATOR</a
          >
        </li>
        <li>
          <a href="#"
            ><img src="../assets/img/buy-comics-subscriptions.png" alt="" />
            SUBSCRIPTION</a
          >
        </li>
        <li>
          <a href="#"
            ><img src="../assets/img/buy-dc-power-visa.svg" alt="" /> DC POWER
            VISA</a
          >
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
.content {
  min-height: 132px;
  width: 100%;
  background: var(--dc-dark);
  & h2 {
    color: var(--dc-light);
    padding-left: 320px;
    padding-top: 56px;
  }
}
.container {
  display: flex;
  justify-content: center;
}
.row {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  & p {
    color: var(--dc-light);
  }
  & .col-2 {
    width: calc(100% / 12 * 2);
  }
}

.shop {
  height: 155px;
  width: 100%;
  background: var(--dc-primary);
  & ul {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  & li {
    list-style: none;
    padding: 20px;
  }
  & img {
    width: 57px;
    margin: 10px;
  }
  & a {
    text-decoration: none;
    color: var(--dc-light);
    display: flex;
    align-items: center;
    padding-left: 10px;
  }
}
</style>
