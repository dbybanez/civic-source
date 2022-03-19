<template>
  <div class="site-contents h-100">
    <div class="content-section h-100">
      <div class="container-fluid h-100">
        <div class="row justify-content-center align-items-center h-100">
          <div class="col-8">
            <div class="row">
              <div class="col-3">
                <div class="shadow-sm rounded p-3 mb-3">
                  <h5>Property Name One</h5>
                  <p>Some details about property name one.</p>
                  <nuxt-link :to="{ name: 'properties-id', params: { id: 1 }}" class="nuxt-link-exact-active nuxt-link-active btn btn-primary">
                    View Property
                  </nuxt-link>
                </div>
              </div>
              <div class="col-3">
                <div class="shadow-sm rounded p-3 mb-3">
                  <h5>Property Name Two</h5>
                  <p>Some details about property name two.</p>
                  <nuxt-link :to="{ name: 'properties-id', params: { id: 2 }}" class="nuxt-link-exact-active nuxt-link-active btn btn-primary">
                    View Property
                  </nuxt-link>
                </div>
              </div>
              <div class="col-3">
                <div class="shadow-sm rounded p-3 mb-3">
                  <h5>Property Name Three</h5>
                  <p>Some details about property name three.</p>
                  <nuxt-link :to="{ name: 'properties-id', params: { id: 3 }}" class="nuxt-link-exact-active nuxt-link-active btn btn-primary">
                    View Property
                  </nuxt-link>
                </div>
              </div>
              <div class="col-3">
                <div class="shadow-sm rounded p-3 mb-3">
                  <h5>Property Name Four</h5>
                  <p>Some details about property name four.</p>
                  <nuxt-link :to="{ name: 'properties-id', params: { id: 4 }}" class="nuxt-link-exact-active nuxt-link-active btn btn-primary">
                    View Property
                  </nuxt-link>
                </div>
              </div>
              <div class="col-3">
                <div class="shadow-sm rounded p-3 mb-3">
                  <h5>Property Name Five</h5>
                  <p>Some details about property name five.</p>
                  <nuxt-link :to="{ name: 'properties-id', params: { id: 5 }}" class="nuxt-link-exact-active nuxt-link-active btn btn-primary">
                    View Property
                  </nuxt-link>
                </div>
              </div>
              <div class="col-3">
                <div class="shadow-sm rounded p-3 mb-3">
                  <h5>Property Name Six</h5>
                  <p>Some details about property name six.</p>
                  <nuxt-link :to="{ name: 'properties-id', params: { id: 6 }}" class="nuxt-link-exact-active nuxt-link-active btn btn-primary">
                    View Property
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// export default {
//   data() {
//     return {
//       default: 0
//     }
//   },
//   methods: {
//     goToProperty(id) {

//     }
//   },
// }
</script>