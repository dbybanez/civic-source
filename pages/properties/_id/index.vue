<template>
  <div class="site-contents h-100">
    <div class="content-section h-100">
      <div class="container-fluid h-100">
        <div class="row align-items-center h-100">
          <div class="col px-0 h-100">
            <div class="position-absolute h-100 w-100">
              <div class="container-fluid" style="margin-top: 3.75rem;">
                <div class="row">
                  <div class="col">
                    <div class="d-block bg-body p-3" style="--bs-bg-opacity: .8;">
                      <div class="row align-items-center">
                        <div class="col">
                          Paper image
                        </div>
                        <div class="col">
                          Property ID: {{ this.$route.params.id }}
                        </div>
                        <div class="col">
                          Map Marker image
                        </div>
                        <div class="col text-center">
                          <p class="mb-0">To <br/> Start<br/> Place Deposit</p>
                        </div>
                        <div class="col">
                          Bookmark image
                        </div>
                        <div class="col">
                          <p class="mb-0">Market value $40,000</p>
                          <p class="mb-0">$5,000</p>
                          <p class="mb-0">Reserve Price</p>
                        </div>
                        <div class="col">
                          Manual image
                        </div>
                      </div>
                    </div>
                    <div class="d-block bg-body py-2 px-3" style="--bs-bg-opacity: .5;">
                      <div class="row align-items-center">
                        <div class="col">
                          <p class="mb-0">Outbid <br/> 12</p>
                        </div>
                        <div class="col">
                          <p class="mb-0">Active <br/> 24</p>
                        </div>
                        <div class="col">
                          <p class="mb-0">Winning <br/> 12</p>
                        </div>
                        <div class="col">
                          <p class="mb-0">14 Flood St</p>
                          <div class="d-flex">
                            <div class="me-3">$1,000</div>
                            <div>$5,000</div>
                          </div>
                        </div>
                        <div class="col">
                          <p class="mb-0">14 Flood St</p>
                          <div class="d-flex">
                            <div class="me-3">$1,000</div>
                            <div>$5,000</div>
                          </div>
                        </div>
                        <div class="col">
                          <p class="mb-0">14 Flood St</p>
                          <div class="d-flex">
                            <div class="me-3">$1,000</div>
                            <div>$5,000</div>
                          </div> 
                        </div>
                        <div class="col">
                          <p class="mb-0">14 Flood St</p>
                          <div class="d-flex">
                            <div class="me-3">$1,000</div>
                            <div>$5,000</div>
                          </div>
                        </div>
                        <div class="col">
                          <p class="mb-0">Winning <br/> $100,000</p>
                        </div>
                        <div class="col">
                          <p class="mb-0">Active <br/> $100,000</p>
                        </div>
                        <div class="col">
                          <p class="mb-0">Outbid <br/> $100,000</p>
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