<template>
  <div>
    <div
      class="main-menu menu-fixed menu-light menu-accordion"
      data-scroll-to-active="true"
    >
      <div class="navbar-header">
        <ul class="nav navbar-nav flex-row">
          <li class="nav-item mr-auto">
            <nuxt-link class="navbar-brand" to="#">
              <div class="brand-logo"></div>
              <h2 class="brand-text mb-0">Drcallaway</h2>
            </nuxt-link>
          </li>
          <li class="nav-item nav-toggle">
            <nuxt-link
              to="#"
              class="nav-link modern-nav-toggle pr-0"
              data-toggle="collapse"
              ><i
                class="feather icon-x d-block d-xl-none font-medium-4 primary toggle-icon"
              ></i
              ><i
                class="toggle-icon feather icon-disc font-medium-4 d-none d-xl-block primary"
                data-ticon="icon-disc"
              ></i
            ></nuxt-link>
          </li>
        </ul>
      </div>
      <div class="shadow-bottom"></div>
      <div class="main-menu-content">
        <ul
          id="main-menu-navigation"
          class="navigation navigation-main"
          data-menu="menu-navigation"
        >
          <li class="nav-item active">
            <nuxt-link to="dashboard"
              ><i class="feather icon-home"></i
              ><span class="menu-title" data-i18n="Dashboard">Dashboard</span
              ><span class="badge badge badge-warning badge-pill float-right"
                >2</span
              ></nuxt-link
            >
          </li>
          <hr />
          <li class=" nav-item">
            <nuxt-link to="waiting"
              ><i class="feather icon-phone"></i>
              <span class="menu-title">Call a Doctor</span>
            </nuxt-link>
          </li>

          <li class=" nav-item">
            <nuxt-link to="profile"
              ><i class="feather icon-user"></i>
              <span class="menu-title">Profile</span>
            </nuxt-link>
          </li>
          <li class=" nav-item ">
            <nuxt-link to="medical-history"
              ><i class="feather icon-book"></i>
              <span class="menu-title">Medical History</span>
            </nuxt-link>
          </li>

          <li class=" nav-item">
            <nuxt-link to="consultation"
              ><i class="feather icon-users"></i>
              <span class="menu-title">Consultation Room</span>
            </nuxt-link>
          </li>
          <li class=" nav-item">
            <nuxt-link to="referal"
              ><i class="feather icon-user-plus"></i>
              <span class="menu-title">Referral</span>
            </nuxt-link>
          </li>
          <li class=" nav-item">
            <nuxt-link to="subscription-plan"
              ><i class="feather icon-credit-card"></i>
              <span class="menu-title">Subscription Plan</span>
            </nuxt-link>
          </li>
          <li class=" nav-item">
            <nuxt-link to="emergency"
              ><i class="fa fa-ambulance"></i>
              <span class="menu-title">Ambulance</span>
            </nuxt-link>
          </li>
        </ul>
        <hr />
        <ul
          id="main-menu-navigation"
          class="navigation other-link navigation-main"
          data-menu="menu-navigation"
        >
          <li class=" nav-item">
            <nuxt-link to="help"
              ><i class="feather icon-alert-circle"></i
              ><span class="menu-title">Help Desk</span>
            </nuxt-link>
          </li>
          <li class=" nav-item">
            <nuxt-link to="change-password"
              ><i class="feather icon-settings"></i
              ><span class="menu-title">Change Password</span>
            </nuxt-link>
          </li>
          <li class=" nav-item">
            <nuxt-link to="../logout"
              ><i class="feather icon-arrow-left-circle"></i
              ><span class="menu-title" data-i18n="Raise Support"
                >Logout</span
              ></nuxt-link
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
