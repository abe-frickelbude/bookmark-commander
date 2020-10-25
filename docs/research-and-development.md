
# Ongoing R&D

## Possible implementation approaches

### Currently leaning towards:

* TypeScript as implementation  language
* `Electron`
* `Vue 3.x`, possibly fall back to Vue 2.x if ecosystem proves to be still unstable
* Potentially use `VueX` for application state mangement (but could be done with singleton services and DI instead)
* `PrimeVue` for UI layer
* `inversify-props` <https://github.com/CKGrafico/inversify-props> for DI and IOC, seems to integrate nicely into Vue (there's also `vue-injector` and some others, but `inversify-props` uses an existing IOC container and
is otherwise a neat, lean wrapper that doesn't force too many assumptions)

### Alternatives:

* `Angular` for everything, but might be too heavyweight for this, and it's less flexible than `Vue`
* `Ember` for everything, but less flexible and also less performant than `Vue`
