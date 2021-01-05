<template>
  <div>
    <div class="bar">
      <b-navbar type="light" variant="white" class=" shadow-sm">
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse class="d-flex flex-wrap" id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto d-flex flex-wrap">
            <b-nav-item-dropdown text="Mon compte  ">
              <b-dropdown-item href="#"> EN</b-dropdown-item>
              <b-dropdown-item href="#">ES</b-dropdown-item>
              <b-dropdown-item href="#">RU</b-dropdown-item>
              <b-dropdown-item href="#">FA</b-dropdown-item>
            </b-nav-item-dropdown>

            <b-nav-item>
              <span class="text-success">
                <i class="fa fa-user-tie ml-sm-2 mr-sm-1"></i>
              </span>
              Monsieur dupont
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.bar {
  a {
    &:hover {
      color: green;
    }
  }
}
</style>
