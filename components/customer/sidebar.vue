<template>
  <div>
    <div
      class="main-menu menu-fixed menu-light menu-accordion"
      data-scroll-to-active="true"
    >
      <div class="navbar-header">
        <ul class="nav navbar-nav flex-row">
          <li class="nav-item mr-auto">
            <a class="navbar-brand" href="#">
              <div class="brand-logo"></div>
              <h2 class="brand-text mb-0">Drcallaway</h2>
            </a>
          </li>
          <li class="nav-item nav-toggle">
            <a class="nav-link modern-nav-toggle pr-0" data-toggle="collapse"
              ><i
                class="feather icon-x d-block d-xl-none font-medium-4 primary toggle-icon"
              ></i
              ><i
                class="toggle-icon feather icon-disc font-medium-4 d-none d-xl-block primary"
                data-ticon="icon-disc"
              ></i
            ></a>
          </li>
        </ul>
      </div>
      <div class="shadow-bottom"></div>
      <div class="main-menu-content">
        <ul
          class="navigation navigation-main"
          id="main-menu-navigation"
          data-menu="menu-navigation"
        >
          <li class="nav-item active">
            <a href="dashboard.html"
              ><i class="feather icon-home"></i
              ><span class="menu-title" data-i18n="Dashboard">Dashboard</span
              ><span class="badge badge badge-warning badge-pill float-right"
                >2</span
              ></a
            >
          </li>
          <hr />
          <li class=" nav-item">
            <a href="waiting.html"
              ><i class="feather icon-phone"></i>
              <span class="menu-title">Call a Doctor</span>
            </a>
          </li>

          <li class=" nav-item">
            <a href="profile.html"
              ><i class="feather icon-user"></i>
              <span class="menu-title">Profile</span>
            </a>
          </li>
          <li class=" nav-item ">
            <a href="medicalhistory.html"
              ><i class="feather icon-book"></i>
              <span class="menu-title">Medical History</span>
            </a>
          </li>

          <li class=" nav-item">
            <a href="consult.html"
              ><i class="feather icon-users"></i>
              <span class="menu-title">Consultation Room</span>
            </a>
          </li>
          <li class=" nav-item">
            <a href="referal.html"
              ><i class="feather icon-user-plus"></i>
              <span class="menu-title">Referral</span>
            </a>
          </li>
          <li class=" nav-item">
            <a href="subscriptionplan.html"
              ><i class="feather icon-credit-card"></i>
              <span class="menu-title">Subscription Plan</span>
            </a>
          </li>
          <li class=" nav-item">
            <a href="emergency.html"
              ><i class="fa fa-ambulance"></i>
              <span class="menu-title">Ambulance</span>
            </a>
          </li>
        </ul>
        <hr />
        <ul
          class="navigation other-link navigation-main"
          id="main-menu-navigation"
          data-menu="menu-navigation"
        >
          <li class=" nav-item">
            <a href="help.html"
              ><i class="feather icon-alert-circle"></i
              ><span class="menu-title">Help Desk</span></a
            >
          </li>
          <li class=" nav-item">
            <a href="changepassword.html"
              ><i class="feather icon-settings"></i
              ><span class="menu-title">Change Password</span></a
            >
          </li>
          <li class=" nav-item">
            <a href="#"
              ><i class="feather icon-arrow-left-circle"></i
              ><span class="menu-title" data-i18n="Raise Support"
                >Logout</span
              ></a
            >
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
