<template>
  <div class="dashboard-page">
    <div class="page-content-wrapper">
      <div class="quotes-page">
        <div class="container-fluid">
          <div class="setting-page">
            <ul class="top-setting-menu">
              <li><a href="#" class="btn-style lightgray">Main settings</a></li>
              <li><a href="#" class="btn-style lightgray">You & Your business</a></li>
              <li><a href="#" class="btn-style lightgray">Your plan & Billing</a></li>
            </ul>
            <div class="account-details">
              <h2>Account settings</h2>
              <div class="form">
                <div class="form-group">
                  <label for="name">Account name</label>
                  <input type="text" class="form-control" placeholder="Your Name here">
                  <label for="email">Email</label>
                  <input type="email" class="form-control" placeholder="Your Email here">
                </div>
              </div>
              <div class="btn-wrapper">
                <a href="#"><img src="../assets/images/setting-key.svg" alt="Key">Change password here</a>
              </div>
            </div>
            <div class="project-settings">
              <h2>Project settings</h2>
              <div class="project-setting-card">
                <label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                </label>
                <p>Mark as ‘Pending approval’ when any quote is received</p>
              </div>
              <div class="project-setting-card">
                <label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                </label>
                <p>Auto mark all as ‘Quote approved’ when receive approval from client</p>
              </div>
              <div class="project-setting-card">
                <label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                </label>
                <p>Auto Pay any job when it’s marked as completed</p>
              </div>

            </div>
            <div class="project-settings project-notification">
              <h2>Notifications</h2>
              <div class="project-setting-card">
                <label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                </label>
                <p>Mark as ‘Pending approval’ when any quote is received</p>
              </div>
              <div class="project-setting-card">
                <label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                </label>
                <p>Auto mark all as ‘Quote approved’ when receive approval from client</p>
              </div>
              <div class="project-setting-card">
                <label class="switch">
                  <input type="checkbox" checked>
                  <span class="slider round"></span>
                </label>
                <p>Auto Pay any job when it’s marked as completed</p>
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
  name: 'GuestView',
  components: {
  },
  data(){
    return{
      isMenuActive: false,
    }
  }
}
</script>
