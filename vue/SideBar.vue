<template>
  <div>
    <div class="sidebar shadow-sm">
      <div class="sidebar__header">
        <img
          src="http://via.placeholder.com/160x160"
          alt=""
          class="rounded-circle"
        />
        <div class="header">
          <a href="#">
            <h4>Monsieur Dupont</h4>
          </a>
          <p><i class="fa fa-circle text-success mr-1"></i>connecté</p>
        </div>
      </div>
      <div class="sidebar__nav">
        <div
          class="sidebar__item "
          :class="[nav.active ? 'sidebar__item--active' : '']"
          v-for="(nav, i) in menu"
          :key="i"
          @click.prevent="activeNav(i)"
        >
          <div>
            <a
              :href="nav.href"
              class="sidebar__link d-flex justify-content-between"
            >
              <div>
                <span>
                  <i class="fa  text-success" :class="nav.icon"></i>
                </span>
                {{ nav.title }}
              </div>
              <i class="fa fa-angle-down drop" v-if="dropdownlength(i)"></i
            ></a>
          </div>
          <transition name="slide-fade">
            <div class="sidebar__dropdown" v-if="nav.droped">
              <ul>
                <li
                  class="drop-item"
                  v-for="(drop, index) in nav.dropdown"
                  :key="index"
                >
                  <a href="#">{{ drop.title }}</a>
                </li>
              </ul>
            </div>
          </transition>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    menu: [
      {
        title: "accueil",
        href: "#",
        icon: "fa-home",
        active: true,
        droped: false,
        dropdown: [
          {
            title: "home services",
            href: "#",
            icon: "fa-folder-open",
            active: false
          },
          {
            title: "home birus-prime",
            href: "#",
            icon: "fa-folder-open",
            active: false
          },
          {
            title: "recherche de l'arrivage",
            href: "#",
            icon: "fa-folder-open",
            active: false
          }
        ]
      },
      {
        title: "appel d’offres",
        href: "#",
        icon: "fa-shapes",
        active: false,
        droped: false,
        dropdown: []
      },
      {
        title: "listes des emplois",
        href: "#",
        icon: "fa-folder-open",
        active: false,
        droped: false,
        dropdown: []
      },
      {
        title: "recherche prestataire",
        href: "#",
        icon: "fa-chalkboard",
        active: false,
        droped: false,
        dropdown: [
          {
            title: "prestataire de services",
            href: "#",
            icon: "fa-folder-open",
            active: false
          },
          {
            title: "recherche birus-prime",
            href: "#",
            icon: "fa-folder-open",
            active: false
          },
          {
            title: "recherche de l'arrivage",
            href: "#",
            icon: "fa-folder-open",
            active: false
          }
        ]
      }
    ]
  }),
  computed: {},
  methods: {
    activeNav(i) {
      this.menu.forEach(el => (el.active = false));
      this.menu[i].active = true;
      this.dropdownActive(i);
    },
    dropdownlength(i) {
      if (this.menu[i].dropdown.length) {
        return true;
      } else {
        return false;
      }
    },
    dropdownActive(i) {
      if (this.menu[i].droped === false) {
        if (this.menu[i].dropdown) {
          this.menu.forEach(d => (d.droped = false));
          if (this.menu[i].dropdown.length > 0) {
            this.menu[i].droped = true;
          }
        }
      } else {
        this.menu[i].droped = false;
      }
    }
  }
};
</script>
<style lang="scss" scoped>
.sidebar {
  background-color: black;
  width: 300px;
  min-height: 100vh;
  padding: 1rem 2p;

  &__dropdown {
    background-color: white;
    margin-left: 2px;
    margin-bottom: 2px;
    margin-top: 10px;
    color: black;
    display: flex;
    flex-direction: column;
    font-weight: bold;
    text-transform: uppercase;
    text-align: left;
    font-size: 0.9rem;
    ul {
      list-style: none;
      margin-left: -10px;
    }
    .drop-item {
      color: black !important;
      padding: 5px 5px 7px 10px;
      a {
        border-bottom: 1px solid gray;
        padding: 4px;
      }
    }
  }
  a {
    color: white;
    text-decoration: none;
    &:hover {
      color: rgb(97, 220, 97);
    }
  }
  &__header {
    font-size: 0.9rem;
    display: flex;
    justify-content: space-around;
    font-weight: bold;
    padding: 2rem 1rem 1rem;
    border-bottom: 1px solid white;
    color: white;
    i {
      color: rgb(37, 216, 37);
    }
    h4 {
      margin-top: 2px;
      font-size: 1.1rem;
    }

    img {
      width: 100%;
      max-width: 60px;
      max-height: 60px;
      height: auto;
    }
  }
  &__nav {
    margin-top: 2rem;
  }
  &__item {
    font-weight: bold;
    list-style: none;
    text-align: left;
    padding: 7px 6px;
    font-size: 0.9rem;
    border-radius: 5px;
    border-bottom-right-radius: 0px;
    cursor: pointer;
    margin-bottom: 10px;
    text-transform: uppercase;
    .drop {
      margin-right: 4px;
      margin-top: 2px;
      font-size: 18px;
    }
    &:hover {
      background-color: white;
      color: black;
    }
    &__link {
      color: black;
      &:hover {
        background-color: white;
        color: black;
        a {
          color: rgb(75, 192, 75);
        }
      }
    }
    &--active {
      background-color: white;
      a {
        color: black;
      }
    }
    span {
      font-weight: 800;
      margin-right: 0.9rem;
      margin-left: 0.2rem;
      color: rgb(75, 192, 75);
    }
    .slide-fade-enter-active {
      transition: all 0.2s ease;
    }
    .slide-fade-leave-active {
      transition: all 0.2s cubic-bezier(1, 0.5, 0.8, 1);
    }
    .slide-fade-enter, .slide-fade-leave-to
/* .slide-fade-leave-active below version 2.1.8 */ {
      transform: translateX(10px);
      opacity: 0;
    }
  }
}
</style>
