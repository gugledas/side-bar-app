<script>
export default {
  data: () => ({
    menu: [
      {
        key: "5b97b927-89a6-4d98-8c0d-3e660325c0e9",
        title: "Mon compte",
        description: null,
        uri: "",
        alias: "",
        external: false,
        absolute: "http://airportlome.kksa/",
        relative: "/",
        existing: true,
        weight: "-50",
        expanded: false,
        enabled: true,
        uuid: null,
        options: [],
        below: [
          {
            key: "b2211112-60ed-4e28-8f98-38bf03e128dc",
            title: "Proposer  un emploi",
            description: null,
            uri: "node/add/jobs",
            alias: "node/add/jobs",
            external: false,
            absolute: "http://airportlome.kksa/node/add/jobs",
            relative: "/node/add/jobs",
            existing: true,
            weight: "-50",
            expanded: false,
            enabled: true,
            uuid: "b5d88bae-d4c9-4273-8f09-540914769c95",
            options: {
              query: []
            }
          },
          {
            key: "1ad90ed3-b8c3-4c32-961b-d1cafee765fd",
            title: "Proposer un appel d'offre",
            description: null,
            uri: "node/add/appel_d_offres",
            alias: "node/add/appel_d_offres",
            external: false,
            absolute: "http://airportlome.kksa/node/add/appel_d_offres",
            relative: "/node/add/appel_d_offres",
            existing: true,
            weight: "-49",
            expanded: false,
            enabled: true,
            uuid: "a76f3c4e-3985-46b1-a7db-4a5b7ce6dc68",
            options: {
              query: []
            }
          },
          {
            key: "b4c736a1-e41d-4df0-ac08-9f8081dbaabb",
            title: "Proposer une formations",
            description: null,
            uri: "node/add/formations",
            alias: "node/add/formations",
            external: false,
            absolute: "http://airportlome.kksa/node/add/formations",
            relative: "/node/add/formations",
            existing: true,
            weight: "-48",
            expanded: false,
            enabled: true,
            uuid: "03c6bd77-f1db-40de-a0fd-649146faf9b6",
            options: {
              query: []
            }
          },
          {
            key: "82ab8cfd-6866-4b57-8a7c-4016201275f2",
            title: "Proposer  un service comme prestataire",
            description: null,
            uri: "node/add/prestataires",
            alias: "node/add/prestataires",
            external: false,
            absolute: "http://airportlome.kksa/node/add/prestataires",
            relative: "/node/add/prestataires",
            existing: true,
            weight: "-47",
            expanded: false,
            enabled: true,
            uuid: "18d668ff-5bae-4b3e-ad0a-94ff73012d7d",
            options: {
              query: []
            }
          },
          {
            key: "762b76fb-fc61-4e75-abb8-8357fc7aeb60",
            title: "Proposer un hôtel",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-46",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "a3fbe589-c041-44d8-bb74-ec9bc57a0822",
            title: "Proposer  une publicité",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-45",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "966cbab7-5937-433b-b0f1-22a518930a0c",
            title: "Mes payements",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-44",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "e0b4e3a7-79e6-43d2-b4fe-b78224cd86db",
            title: "Ajouter mon cv",
            description: null,
            uri: "multistepvalidation/CheckRoute/identification_du_candidat",
            alias: "multistepvalidation/CheckRoute/identification_du_candidat",
            external: false,
            absolute:
              "http://airportlome.kksa/multistepvalidation/CheckRoute/identification_du_candidat",
            relative:
              "/multistepvalidation/CheckRoute/identification_du_candidat",
            existing: true,
            weight: "-43",
            expanded: false,
            enabled: true,
            uuid: null,
            options: {
              query: {
                go: "identification_du_candidat"
              }
            }
          },
          {
            key: "1c8008db-2f89-452a-b2bd-e5bd4c4edaf9",
            title: "Postuler a des emplois",
            description: null,
            uri: "base:recherche",
            alias: null,
            external: false,
            absolute: "http://airportlome.kksa/recherche",
            relative: "/recherche",
            existing: true,
            weight: "-42",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "9e629704-f775-486c-804c-4db489ed645d",
            title: "Liste des emplois postules",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-41",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "2fc88ddc-cf72-459f-9abe-d6ec475118cd",
            title: "Participer a des formations",
            description: null,
            uri: "liste-des-formations",
            alias: "liste-des-formations",
            external: false,
            absolute: "http://airportlome.kksa/liste-des-formations",
            relative: "/liste-des-formations",
            existing: true,
            weight: "-40",
            expanded: false,
            enabled: true,
            uuid: null,
            options: {
              query: []
            }
          },
          {
            key: "657ce10b-766f-44b9-81ef-4ceb4a74c27e",
            title: "Activer des alertes pour recevoir les publications",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-39",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "e68b5a4f-c06c-4ebc-a716-c1f5ada3904b",
            title: "proposer des services comme prestataire",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-38",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "e3b1d40d-eb4c-4862-927f-0925cfba3973",
            title: "Vendre son entreprise",
            description: null,
            uri: "multistepvalidation/CheckRoute/emploi",
            alias: "multistepvalidation/CheckRoute/emploi",
            external: false,
            absolute:
              "http://airportlome.kksa/multistepvalidation/CheckRoute/emploi",
            relative: "/multistepvalidation/CheckRoute/emploi",
            existing: true,
            weight: "-37",
            expanded: false,
            enabled: true,
            uuid: null,
            options: {
              query: {
                go: "/node/add/vendre_son_entreprise"
              }
            }
          },
          {
            key: "73df5571-d1d8-4de9-810d-9c55713084f2",
            title: "Facturation",
            description: null,
            uri: "",
            alias: "",
            external: false,
            absolute: "http://airportlome.kksa/",
            relative: "/",
            existing: true,
            weight: "-36",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "user.page",
            title: "Mon compte",
            description: "",
            uri: "user",
            alias: "user",
            external: false,
            absolute: "http://airportlome.kksa/user",
            relative: "/user",
            existing: true,
            weight: "-35",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          },
          {
            key: "user.logout",
            title: "Se déconnecter",
            description: "",
            uri: "user/logout",
            alias: "user/logout",
            external: false,
            absolute: "http://airportlome.kksa/user/logout",
            relative: "/user/logout",
            existing: true,
            weight: "-34",
            expanded: false,
            enabled: true,
            uuid: null,
            options: []
          }
        ]
      },
      {
        key: "f7777d8b-687d-4887-bb84-0aa15f3edd0e",
        title: "Se connecter",
        description: null,
        uri: "user/login",
        alias: "user/login",
        external: false,
        absolute: "http://airportlome.kksa/user/login",
        relative: "/user/login",
        existing: true,
        weight: "0",
        expanded: false,
        enabled: true,
        uuid: null,
        options: {
          query: []
        }
      }
    ],
    sideMenu: []
  }),
  mounted() {
    this.sideMenu = this.newMenu;
  },
  computed: {
    actif(i) {
      if (this.newMenu[i].actived === true) {
        return true;
      } else {
        return false;
      }
    },
    newMenu() {
      var active = false;
      var droped = false;
      for (let item of this.menu) {
        item.actived = active;
        item.droped = droped;
      }
      return this.menu;
    }
  },
  methods: {
    activeNav(i) {
      this.sideMenu.forEach(el => (el.actived = false));
      this.sideMenu[i].actived = true;
      console.log(this.sideMenu[i]);
    },
    dropdownlength(i) {
      var element = this.sideMenu[i];

      var newObject = Object.keys(element);
      if (newObject.indexOf("below") === -1) {
        return false;
      } else {
        return true;
      }
    },
    check() {
      console.log(this.newMenu);
    },
    esses(i) {
      if (this.sideMenu[i].droped === false) {
        if (this.sideMenu[i].dropdown) {
          this.sideMenu.forEach(d => (d.droped = false));
          if (this.sideMenu[i].below.length > 0) {
            this.sideMenu[i].droped = true;
          }
        }
      } else {
        this.sideMenu[i].droped = false;
      }
    },
    dropdownActive(i) {
      console.log(this.newMenu[i].droped);
      if (this.newMenu[i].droped === false) {
        this.newMenu[i].droped = true;
      } else {
        this.newMenu[i].droped = false;
      }
    }
  }
};
</script>

// nav-bar correct one
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
              @click.prevent="dropdownActive(i)"
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
                  :class="drop.active ? 'drop-item--active' : ''"
                  v-for="(drop, index) in nav.dropdown"
                  :key="index"
                >
                  <a
                    href="#"
                    @click="linkActive(i, index)"
                    :style="drop.active ? 'color: rgb(97, 220, 97);' : ''"
                    >{{ drop.title }}</a
                  >
                  <pre>{{ drop.active }} {{ i }} {{ index }}</pre>
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
            active: true
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
    },
    linkActive(i, index) {
      this.menu[i].dropdown.forEach(el => (el.active = false));
      this.menu[i].dropdown[index].active = true;
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
      &--active {
        color: rgb(97, 220, 97);
      }
      a {
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
