<template>
    <div class="page">
        <header class="header">
            <div class="header__inner">
                <div class="header__content">
                    <div class="header__logo">
                        logo
                    </div>
                    <div class="header__nav">
                        <div class="header__nav-item">
                            <a href="#" class="header__nav-link">Workers</a>
                        </div>
                        <div class="header__nav-item">
                            <a href="#" class="header__nav-link">Projects</a>
                        </div>
                        <div class="header__nav-item">
                            <a href="#" class="header__nav-btn ui-btn ui-btn-primary">Publish project</a>
                            <div class="header__nav-dropdown">
                                <div class="header__nav-dropdown-content">
                                    <div class="header__nav-dropdown-column">
                                        <a href="#" class="header__nav-dropdown-title">
                                            Category 1
                                        </a>
                                        <div class="header__nav-dropdown-list">
                                            <a href="#" class="header__nav-dropdown-link">
                                                Subcategory name
                                            </a>
                                            <a href="#" class="header__nav-dropdown-link">
                                                Subcategory
                                            </a>
                                            <a href="#" class="header__nav-dropdown-link">
                                                Select Subcategory
                                            </a>
                                            <a href="#" class="header__nav-dropdown-link">
                                                Subcategory name
                                            </a>
                                            <a href="#" class="header__nav-dropdown-link">
                                                Subcategory
                                            </a>
                                        </div>
                                    </div>
                                    <div class="header__nav-dropdown-column">
                                        <a href="#" class="header__nav-dropdown-title">
                                            Category 2
                                        </a>
                                        <div class="header__nav-dropdown-list">
                                            <a href="#" class="header__nav-dropdown-link">
                                                Subcategory name
                                            </a>
                                            <a href="#" class="header__nav-dropdown-link">
                                                Subcategory
                                            </a>
                                        </div>
                                    </div>
                                </div>
                                <div class="header__nav-dropdown-all">
                                    <a href="#" class="header__nav-dropdown-all-i">
                                        See all categories
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="header__search">
                        <form action="#">
                            <div class="ui-search">
                                <div class="ui-search-body">
                                    <input type="text" class="ui-search-input">
                                    <div class="ui-search-select">
                                        <input type="text" value="All categories">
                                        <div class="ui-search-select-dropdown">
                                            <div class="ui-search-select-option" data-value="Name of category">
                                                Name of category
                                            </div>
                                        </div>
                                        <div class="ui-search-select-dropdown">
                                            <div class="ui-search-select-option" data-value="Name of category">
                                                Name of category
                                            </div>
                                        </div>
                                        <div class="ui-search-select-dropdown">
                                            <div class="ui-search-select-option" data-value="Name of category">
                                                Name of category
                                            </div>
                                        </div>
                                    </div>
                                    <button class="ui-search-btn">
                                        <img src="#" alt="search ico">
                                    </button>
                                </div>
                            </div>
                        </form>
                    </div>
                    <div class="header__profile">
                        <a href="#" class="header__profile-link">
                            <span class="header__profile-count">9+</span>
                            My profile
                            <span class="header__profile-ico">
                                ico profile
                            </span>
                        </a>
                    </div>
                    <div class="header__basket">
                        <a href="#" class="header__basket-link">
                            <span class="header__basket-count">9+</span>
                            My profile
                            <span class="header__basket-ico">
                                ico profile
                            </span>
                        </a>
                    </div>
                    <div class="header__lang">
                        <a href="#" class="header__basket-link">
                            <span class="header__basket-count">9+</span>
                            My profile
                            <span class="header__basket-ico">
                                ico profile
                            </span>
                        </a>
                    </div>
                </div>
            </div>
        </header>
    </div>
</template>

<script>
  export default {
    name: "Layout"
  }
</script>

<style lang="scss">

</style>