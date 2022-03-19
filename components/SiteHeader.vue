<template>
  <header class="site-header">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 col-md-8">
          <div class="row align-items-center">
            <div class="col-12 col-md">
              <div class="row align-items-center">
                <div class="col-12 col-md-auto text-center">
                  <nuxt-link to="/" class="logo d-flex justify-content-center justify-content-md-start align-items-center me-3 nuxt-link-exact-active nuxt-link-active">
                    <!-- <img src="@/assets/images/logo-spp-01.svg"> -->
                    <span class="d-block ms-2 fw-bold">Civic Source</span>
                  </nuxt-link>
                </div>
                <div class="col-12 col-md">
                  <div class="site-navigation d-flex">
                    <div class="nav-item">
                      <nuxt-link to="/" class="nuxt-link-exact-active nuxt-link-active">
                        Home
                      </nuxt-link>
                    </div>
                    <div class="nav-item">
                      <nuxt-link to="/properties" class="nuxt-link-exact-active nuxt-link-active">
                        Properties
                      </nuxt-link>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>