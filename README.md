## Objective:

Guide developers in their migration from vue 2 to vue 3, specifically in their dependencies

## Contents

- name of library
- name of the branch where the vue 3 work has started
- how to install the vue 3 compatible version
- The GH issue where the progress is tracked
- if the author(s) has started documenting how to migrate from vue 2 to vue 3, add a link to the docs.

| Framework                                         | Branch name                                                                                | npm install           | GH Issue #                                                             | Docs |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------ | --------------------- | ---------------------------------------------------------------------- | ---- |
| [NuxtJS](https://nuxtjs.org/)                     | -                                                                                          | -                     | [5708](https://github.com/nuxt/nuxt.js/issues/5708)                    |      |
| [Gridsome](https://gridsome.org/)                 | [vue-next](https://github.com/gridsome/gridsome/tree/vue-next)                             | -                     | [1289](https://github.com/gridsome/gridsome/issues/1289)               |      |
| [Quasar](https://quasar.dev/)                     | [vue3-work](https://github.com/quasarframework/quasar/tree/vue3-work)                      | -                     | [7836](https://github.com/quasarframework/quasar/issues/7836)          |      |
| [vuepress](https://vuepress.vuejs.org/)           | [vuepress-next](https://github.com/vuepress/vuepress-next) (other repo)                    | -                     | [2550](https://github.com/vuejs/vuepress/issues/2550)                  |      |
| [NativeScript-Vue](https://nativescript-vue.org/) | [rigor789/nativescript-vue-next](https://github.com/rigor789/nativescript-vue-next) (fork) | nativescript-vue@next | [583](https://github.com/nativescript-vue/nativescript-vue/issues/583) |      |

| Library                                          | Branch name                                                                                 | npm install  | GH Issue #                                                         | Docs                                                                                |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| [vuetify](https://vuetifyjs.com/)                | [next](https://github.com/vuetifyjs/vuetify/tree/next)                                      | -            | -                                                                  | [Notion board](https://www.notion.so/Vuetify-Next-edf8fdb074eb4643a7196aaf8e5d5cad) |
| [bootstrap-vue](https://bootstrap-vue.org/)      | [lamebear/vue3](https://github.com/lamebear/bootstrap-vue/tree/vue3/) (fork)                | -            | [5196](https://github.com/bootstrap-vue/bootstrap-vue/issues/5196) |                                                                                     |
| [buefy](https://buefy.org/)                      | -                                                                                           | -            | [2505](https://github.com/buefy/buefy/issues/2505)                 |                                                                                     |
| [chakra-ui](https://vue.chakra-ui.com/)          | -                                                                                           | -            | [116](https://github.com/chakra-ui/chakra-ui-vue/issues/116)       |                                                                                     |
| [element-ui](https://element.eleme.io/)          | [element-plus](https://github.com/element-plus/element-plus/) (other repo)                  | element-plus | [20061](https://github.com/ElemeFE/element/issues/20061)           |                                                                                     |
| [inkline](https://inkline.io/)                   | -                                                                                           | -            | [207](https://github.com/inkline/inkline/issues/207)               |                                                                                     |
| [primevue](https://www.primefaces.org/primevue/) | [master](https://github.com/primefaces/primevue)                                            | primevue     |                                                                    |                                                                                     |
| [oruga](https://oruga.io/)                       | [oruga-next](https://github.com/oruga-ui/oruga/tree/develop/packages/oruga-next) (monorepo) | oruga-next   |                                                                    |                                                                                     |

| Tool                                                    | Branch name                                                                                   | npm install                           | GH Issue #                                                                              | Docs                                            |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------- |
| [Vue Formulate](https://vueformulate.com/)              | [axwalker/support-vue-3](https://github.com/axwalker/vue-formulate/tree/support-vue-3) (fork) | -                                     | [198](https://github.com/wearebraid/vue-formulate/issues/198)                           |                                                 |
| [@testing-library/vue](https://testing-library.com/vue) | [vue3](https://github.com/testing-library/vue-testing-library/tree/vue3)                      | @testing-library/vue@next             | -                                                                                       |                                                 |
| [vue-apollo](https://apollo.vuejs.org)                  | [v4](https://github.com/vuejs/vue-apollo/tree/v4)                                             | -                                     | [1011](https://github.com/vuejs/vue-apollo/issues/1011)                                 | [V4 docs (Vue 3)](https://v4.apollo.vuejs.org/) |
| [vue-meta](https://vue-meta.nuxtjs.org/)                | [next](https://github.com/nuxt/vue-meta/tree/next)                                            | -                                     | [558](https://github.com/nuxt/vue-meta/issues/558)                                      |                                                 |
| [vue-axe](axe.vue-a11y.com/)                            | [vue-axe-next](https://github.com/vue-a11y/vue-axe-next) (other repo)                         | vue-axe@beta                          | [1](https://github.com/vue-a11y/vue-axe-next/issues/1)                                  | [demo site](https://vue-axe-next.surge.sh/)     |
| [vee-validate](https://vee-validate.logaretm.com/)      | [next](https://github.com/logaretm/vee-validate/tree/next)                                    | vee-validate@next                     | [2670](https://github.com/logaretm/vee-validate/issues/2670)                            | [v4 docs](https://vee-validate.logaretm.com/v4) |
| [vuelidate](https://vuelidate.js.org/)                  | [next](https://github.com/vuelidate/vuelidate/tree/next)                                      | @vuelidate/core @vuelidate/validators | [2.0](https://github.com/vuelidate/vuelidate/issues?q=is%3Aissue+is%3Aopen+label%3A2.0) | [V2 docs](https://vuelidate-next.netlify.app/)  |
| [jsdoc-vuejs](https://github.com/Kocal/jsdoc-vuejs)     | -                                                                                             | -                                     | [386](https://github.com/Kocal/jsdoc-vuejs/issues/386)                                  |                                                 |

| Workbench                                               | Branch name                                                            | npm install | GH Issue #                                                             | Docs |
| ------------------------------------------------------- | ---------------------------------------------------------------------- | ----------- | ---------------------------------------------------------------------- | ---- |
| [Storybook](https://storybook.js.org/)                  | -                                                                      | -           | [10654](https://github.com/storybookjs/storybook/issues/10654)         |      |
| [Vue Styleguidist](https://vue-styleguidist.github.io/) | [next](https://github.com/vue-styleguidist/vue-styleguidist/tree/next) | -           | [997](https://github.com/vue-styleguidist/vue-styleguidist/issues/997) |      |

| Component                                                     | Branch name                                                                    | npm install            | GH Issue #                                                                | Docs                                                                                                                               |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [vue-multiselect](https://vue-multiselect.js.org/)            | -                                                                              | -                      | [1291](https://github.com/shentao/vue-multiselect/issues/1291)            |                                                                                                                                    |
| [vue2-leaflet](https://vue2-leaflet.netlify.app/)             | [vue-leaflet](https://github.com/vue-leaflet/vue-leaflet) (other repo)         | -                      | [455](https://github.com/vue-leaflet/Vue2Leaflet/issues/455)              |                                                                                                                                    |
| [tiptap](https://tiptap.dev/)                                 | -                                                                              | -                      | [735](https://github.com/ueberdosis/tiptap/issues/735)                    |                                                                                                                                    |
| [tsParticles](https://particles.matteobruni.it/)              | [vue3](https://github.com/matteobruni/tsparticles/tree/master/components/vue3) | particle.vue3          | -                                                                         | [migration docs](https://github.com/matteobruni/tsparticles/blob/master/components/vue3/README.md#migrating-from-vue-2x-to-vue-3x) |
| [vue-live](http://vue-live.surge.sh/)                         | [next](https://github.com/vue-styleguidist/vue-live/tree/next)                 | vue-live@next          | [54](https://github.com/vue-styleguidist/vue-live/issues/54)              |                                                                                                                                    |
| [vue-prism-editor](https://prism-editor.netlify.app/)         | [feature/next](https://github.com/koca/vue-prism-editor/tree/feature/next)     | vue-prism-editor@alpha | [90](https://github.com/koca/vue-prism-editor/issues/90)                  |                                                                                                                                    |
| [vue-ctk-date-time-picker](https://prism-editor.netlify.app/) | -                                                                              | -                      | [315](https://github.com/chronotruck/vue-ctk-date-time-picker/issues/315) |                                                                                                                                    |
