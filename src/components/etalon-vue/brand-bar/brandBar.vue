<template>
  <section class="brands">
    <ul class="brands-list">
      <li>
        <a href="#" title="Check Out the Adidas Collection">
          <img
            class="adidas"
            src="@/assets/images/Adidas-group-logo-fr (2).svg"
            alt="Adidas logo"
            title="adidas"
          />
        </a>
      </li>
      <li>
        <a href="#" title="Check Out the Prada Collection">
          <img
            class="prada"
            src="./../../../assets/images/Prada-Logo (1).svg"
            alt="Prada logo"
            title="Prada"
          />
        </a>
      </li>
      <li>
        <a href="#" title="Check Out the Nike Collection">
          <img
            class="nike"
            src="./../../../assets/images/Logo_NIKE (1).svg"
            alt="Nike logo"
            title="Nike"
          />
        </a>
      </li>
      <li>
        <a href="#" title="Check Out the H&M Collection">
          <img
            class="hm"
            src="./../../../assets/images/H&M-Logo (1).svg"
            alt="H&M logo"
            title="H&M"
          />
        </a>
      </li>
      <li>
        <a href="#" title="Check Out the Gucci Collection">
          <img
            class="gucci"
            src="./../../../assets/images/Gucci_Logo (1).svg"
            alt="Gucci logo"
            title="Gucci"
          />
        </a>
      </li>
      <li>
        <a href="#" title="Check Out the Blk sports Collection">
          <img
            class="blk"
            src="./../../../assets/images/Blk_sports_logo (1).svg"
            alt="Blk logo"
            title="Blk"
          />
        </a>
      </li>
    </ul>
  </section>
</template>
<style scoped>
.brands {
  background: var(--color-five);
  padding: 12px 15px;
  margin-top: -60px;
}
.brands-list {
  list-style: none;
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
  justify-content: space-between;
}

.brands-list img {
  height: 10px;
}
</style>
