<template>
  <div class="modal-for-invoice modal-for-quotes prepare-new-quote request-new-quote-modal">
    <div class="offcanvas offcanvas-end" tabindex="-1"  id="myModal5" aria-labelledby="offcanvasRightLabel">
      <div class="modal-dialog modal-dialog-centered modal-md">
        <div class="modal-content">
          <!-- Modal Header -->
          <div class="modal-header">
            <h2 class="modal-title"><img src="../assets/images/invoice-paper.svg" alt="Invoice">Send a new quote request</h2>
            <a href="/" data-bs-dismiss="offcanvas">
              <img src="../assets/images/right-arrow-border.svg" alt="Arrow">
            </a>

          </div>
          <!-- Modal body -->
          <div class="modal-body">
            <div class="container">
              <div class="create-quote">
                <div class="form">
                  <div class="form-group">
                    <div class="row">
                      <div class="col-12">
                        <label for="name">Customer reference</label>
                        <input type="text" class="form-control" placeholder="Type your reference here ...">
                      </div>
                      <div class="col-md-6 col-12">
                        <label for="email">Business name</label>
                        <input type="text" class="form-control" placeholder="Type Business name here ...">
                      </div>
                      <div class="col-md-6">
                        <label for="search">Business address</label>
                        <input type="search" class="form-control" placeholder="Type Business address here ...">
                      </div>
                      <div class="col-md-4">
                        <label for="address">Business email</label>
                        <input type="text" class="form-control" placeholder="Type Business mail here ...">
                      </div>
                      <div class="col-md-8"></div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="quotes-message">
              <div class="content-wrapper">
                <p>Meeting with client today, having a nice chat. Client wants something and something done.
                  Something seems doable.</p>
                <p>
                  Meeting notes continue, going to put a lot of loirem ipsum here dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
                </p>
              </div>
              <div class="btn-wrapper">
                <a href="#" class="btn-style">Send request</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'RequestNewModal',
  data(){
    return{
      isMenuActive: false,
    }
  }
}
</script>
