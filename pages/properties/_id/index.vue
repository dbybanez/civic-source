<template>
  <div class="site-contents h-100">
    <div class="content-section h-100">
      <div class="container-fluid h-100">
        <div class="row align-items-center h-100">
          <div class="col px-0 h-100">
            <div class="position-absolute h-100 w-100">
              <div class="d-block bg-body" style="--bs-bg-opacity: .8;">
                <div class="container-fluid" style="margin-top: 3.75rem;">
                  <div class="row">
                    <div class="col">
                      <div class="d-block p-3">
                        <div class="row align-items-center">
                          <div class="col text-center">
                            <img src="~/assets/images/summary-list.png" style="width: 60px;">
                          </div>
                          <div class="col text-center">
                            Property ID: {{ this.$route.params.id }}
                          </div>
                          <div class="col text-center">
                            <img src="~/assets/images/place-marker.png" style="width: 60px;">
                          </div>
                          <div class="col text-center">
                            <p class="mb-0">To <br/> Start<br/> Place Deposit</p>
                          </div>
                          <div class="col text-center">
                            <img src="~/assets/images/bookmark-ribbon.png" style="width: 60px;">
                          </div>
                          <div class="col text-center">
                            <p class="mb-0">Market value $40,000</p>
                            <p class="mb-0">$5,000</p>
                            <p class="mb-0">Reserve Price</p>
                          </div>
                          <div class="col text-center">
                            <img src="~/assets/images/property-script.png" style="width: 60px;">
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="d-block bg-body" style="--bs-bg-opacity: .5;">
                <div class="container-fluid">
                  <div class="row">
                    <div class="col">
                      <div class="d-block py-2 px-3">
                        <div class="row align-items-center">
                          <div class="col-1">
                            <p class="mb-0">Outbid <br/> <span class="text-danger">12</span> </p>
                          </div>
                          <div class="col-1">
                            <p class="mb-0">Active <br/> <span class="text-secondary">24</span></p>
                          </div>
                          <div class="col-1">
                            <p class="mb-0">Winning <br/> <span class="text-success">12</span></p>
                          </div>
                          <div class="col">
                            <p class="mb-0"><img src="~/assets/images/sort-up.png" style="width: 16px; filter: invert(35%) sepia(51%) saturate(6794%) hue-rotate(144deg) brightness(89%) contrast(80%);"> 14 Flood St</p>
                            <div class="d-flex">
                              <div class="me-3 text-danger">$1,000</div>
                              <div>$5,000</div>
                            </div>
                          </div>
                          <div class="col">
                            <p class="mb-0"><img src="~/assets/images/sort-down.png" style="width: 16px; filter: invert(26%) sepia(55%) saturate(3589%) hue-rotate(338deg) brightness(92%) contrast(86%);"> 24 Washington Ave.</p>
                            <div class="d-flex">
                              <div class="me-3 text-danger">$1,000</div>
                              <div>$5,000</div>
                            </div>
                          </div>
                          <div class="col">
                            <p class="mb-0"><img src="~/assets/images/sort-right.png" style="width: 16px; filter: invert(28%) sepia(17%) saturate(307%) hue-rotate(169deg) brightness(99%) contrast(88%);"> 289 Hempstead St</p>
                            <div class="d-flex">
                              <div class="me-3">$1,000</div>
                              <div>$5,000</div>
                            </div> 
                          </div>
                          <div class="col">
                            <p class="mb-0"><img src="~/assets/images/sort-up.png" style="width: 16px; filter: invert(35%) sepia(51%) saturate(6794%) hue-rotate(144deg) brightness(89%) contrast(80%);"> 57 West Ave G.</p>
                            <div class="d-flex">
                              <div class="me-3">$1,000</div>
                              <div>$5,000</div>
                            </div>
                          </div>
                          <div class="col-1">
                            <p class="mb-0">Winning <br/> $100,000</p>
                          </div>
                          <div class="col-1">
                            <p class="mb-0">Active <br/> $100,000</p>
                          </div>
                          <div class="col-1">
                            <p class="mb-0">Outbid <br/> $100,000</p>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="img-container position-absolute top-0 start-0">
                <img src="~/assets/images/sample-property.png">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>