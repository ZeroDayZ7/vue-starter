<template>
  <div class="menu-router">
    <router-link to="/login" class="menu-rou">
      <div class="icons">
        <div class="names">
          Sign in
        </div>
        <svg class="icon" xmlns="http://www.w3.org/2000/svg" height="24" viewBox="0 -960 960 960" width="24">
          <path
            d="M480-120v-80h280v-560H480v-80h280q33 0 56.5 23.5T840-760v560q0 33-23.5 56.5T760-120H480Zm-80-160-55-58 102-102H120v-80h327L345-622l55-58 200 200-200 200Z"
            fill="currentColor" />
        </svg>
      </div>
    </router-link>
  </div>
</template>

<style scoped>
.icons {
  display: flex;
  align-items: center;
  color: var(--font-color);
}
.icon path {
  fill: currentColor;
}  

@media (max-width: 600px) {
  .menu-router{
    display: none;
  }
  }
</style>