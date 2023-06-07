<script setup lang="ts"></script>

<template>
  <div class="app-shop">
    <a
      href="/"
      target="_blank"
      rel="noopener"
      class="app-shop__link"
    >
      <picture>
        <source
          srcset="
            @/assets/images/app-badges/googlePlay.webp    1x,
            @/assets/images/app-badges/googlePlay@2x.webp 2x,
            @/assets/images/app-badges/googlePlay@3x.webp 3x
          "
          type="image/webp"
        />
        <source
          srcset="
            @/assets/images/app-badges/googlePlay.png    1x,
            @/assets/images/app-badges/googlePlay@2x.png 2x,
            @/assets/images/app-badges/googlePlay@3x.png 3x
          "
          type="image/png"
        />
        <img
          src="@/assets/images/app-badges/googlePlay.png"
          alt="Ikona sklepu Google Play"
          loading="lazy"
        />
      </picture>
    </a>

    <a
      href="/"
      target="_blank"
      rel="noopener"
      class="app-shop__link"
    >
      <picture>
        <source
          srcset="
            @/assets/images/app-badges/appStore.webp    1x,
            @/assets/images/app-badges/appStore@2x.webp 2x,
            @/assets/images/app-badges/appStore@3x.webp 3x
          "
          type="image/webp"
        />
        <source
          srcset="
            @/assets/images/app-badges/appStore.png    1x,
            @/assets/images/app-badges/appStore@2x.png 2x,
            @/assets/images/app-badges/appStore@3x.png 3x
          "
          type="image/png"
        />
        <img
          src="@/assets/images/app-badges/appStore.png"
          alt="Ikona sklepu App Store"
          loading="lazy"
        />
      </picture>
    </a>

    <a
      href="/"
      target="_blank"
      rel="noopener"
      class="app-shop__link"
    >
      <picture>
        <source
          srcset="
            @/assets/images/app-badges/appGallery.webp    1x,
            @/assets/images/app-badges/appGallery@2x.webp 2x,
            @/assets/images/app-badges/appGallery@3x.webp 3x
          "
          type="image/webp"
        />
        <source
          srcset="
            @/assets/images/app-badges/appGallery.png    1x,
            @/assets/images/app-badges/appGallery@2x.png 2x,
            @/assets/images/app-badges/appGallery@3x.png 3x
          "
          type="image/png"
        />
        <img
          src="@/assets/images/app-badges/appGallery.png"
          alt="Ikona sklepu App Gallery"
          loading="lazy"
        />
      </picture>
    </a>
  </div>
</template>

<style lang="scss">
.app-shop {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: flex-start;

  &__link {
    width: auto;
    height: 40px;

    &:not(:last-child) {
      margin: 0 0.5rem 0.5rem 0;
    }

    &:last-child {
      margin: 0 0 0.5rem;
    }

    img {
      width: auto;
      height: 100%;
    }
  }
}
</style>
