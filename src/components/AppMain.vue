<script>
export default {
  name: "AppMain",
};
</script>

<template>
  <main>
    <section class="content">
      <div class="container">
        <h1>Content goes here</h1>
      </div>
    </section>

    <section class="thumbs">
      <div class="container">
        <ul class="d-flex justify-between">
          <li class="d-flex align-items-center">
            <img
              src="/src/assets/img/buy-comics-digital-comics.png"
              alt="digital-comics"
            />
            <span>Digital comics</span>
          </li>
          <li class="d-flex align-items-center">
            <img
              src="/src/assets/img/buy-comics-merchandise.png"
              alt="digital-comics"
            />
            <span>DC Merchandise</span>
          </li>
          <li class="d-flex align-items-center">
            <img
              src="/src/assets/img/buy-comics-subscriptions.png"
              alt="digital-comics"
            />
            <span>Subscription</span>
          </li>
          <li class="d-flex align-items-center">
            <img
              src="/src/assets/img/buy-comics-shop-locator.png"
              alt="digital-comics"
            />
            <span>Comic shop locator</span>
          </li>
          <li class="d-flex align-items-center">
            <img
              src="/src/assets/img/buy-dc-power-visa.svg"
              alt="digital-comics"
            />
            <span>DC Power Visa</span>
          </li>
        </ul>
      </div>
    </section>
  </main>
</template>

<style scoped>
.content,
.thumbs {
  padding-block: 55px;
  color: var(--dc-comics-light);
}

.content {
  background: var(--dc-comics-dark);
}

.thumbs {
  background: var(--dc-comics-primary);
}

li {
  flex-grow: 1;
}

span {
  margin-left: 16px;
}

img {
  max-width: 55px;
  max-height: 55px;
}
</style>
