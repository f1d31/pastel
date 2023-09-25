<template>
  <div class="modal-for-invoice modal-for-quotes prepare-new-quote quote-success-modal">
    <div class="modal fade" id="myModal4">
      <div class="modal-dialog modal-dialog-centered modal-md">
        <div class="modal-content">
          <div class="modal-body">
            <div class="container text-center">
              <img src="../assets/images/orange-tick-stars.png" alt="Check">
              <h2>Quote sent. That was easy!</h2>
            </div>
            <div class="content-wrapper">
              <div class="content-cards">
                <ul class="quote-sent-successfully">
                  <li><strong>Get paid faster + track your jobs in one place</strong></li>
                  <li>
                    <img src="../assets/images/success-tick-green.png" alt="Tick">
                    <p>Quotes automatically convert to invoices for fast payment</p>
                  </li>
                  <li>
                    <img src="../assets/images/success-tick-green.png" alt="Tick">
                    <p>Request, approve and track quotes in one place</p>
                  </li>
                  <li>
                    <img src="../assets/images/success-tick-green.png" alt="Tick">
                    <p>In-built payment options for your customers</p>
                  </li>
                  <li>
                    <img src="../assets/images/success-tick-green.png" alt="Tick">
                    <p>Automatically sync with your accounting software</p>
                  </li>
                </ul>
              </div>
              <div class="create-account">
                <a href="#" class="btn-style">Create a free account</a>
              </div>
              <div class="btn-wrapper">
                <a href="#">No thanks, I want to spend more time creating <br> my own invoices</a>
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
  name: 'QuoteSuccess',
  data(){
    return{
      isMenuActive: false,
    }
  }
}
</script>
