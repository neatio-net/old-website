<template>
  <div class="view-container">
    <div class="section">
      <div class="header-section">
        <div class="header-section__content content-container">
          <div class="header-section__heading">
            <div class="header-section__title">
              {{ $t("pages.terms.pageTitle") }}
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <div class="section__content content-container">
        <div class="disclaimer">
          <div class="list">
            <ul class="list__items">
              <li class="list__item" v-for="item in $t('pages.terms.listItems')" :key="item">
                {{ item }}
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
