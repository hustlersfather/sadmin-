 

 
 
            <!-- Header Search -->
            <div id="page-header-search" class="overlay-header bg-body-extra-light">
                <div class="content-header">
                    <form class="w-100" action="bd_search.html" method="POST">
                        <div class="input-group">
                            <!-- Layout API, functionality initialized in Template._uiApiLayout() -->
                            <button type="button" class="btn btn-alt-danger" data-toggle="layout" data-action="header_search_off">
                                <i class="fa fa-fw fa-times-circle"></i>
                            </button>
                            <input type="text" class="form-control" placeholder="Search or hit ESC.." id="page-header-search-input" name="page-header-search-input" />
                        </div>
                    </form>
                </div>
            </div>
            <!-- END Header Search -->
 
            <!-- Header Loader -->
            <!-- Please check out the Loaders page under Components category to see examples of showing/hiding it -->
            <div id="page-header-loader" class="overlay-header bg-primary-lighter">
                <div class="content-header">
                    <div class="w-100 text-center">
                        <i class="fa fa-fw fa-circle-notch fa-spin text-primary"></i>
                    </div>
                </div>
            </div>
            <!-- END Header Loader -->
        </header>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-notify/0.2.0/js/bootstrap-notify.js"></script>
        <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-notify/0.2.0/css/bootstrap-notify.css">
        <div class='notifications top-right'></div>
        <script>
        </script>
        <main id="main-container">
            <div class="bg-primary-darker">
                <div class="bg-black-10">
                    <div class="content py-3">
                        <!-- Toggle Main Navigation -->
                        <div class="d-lg-none">
                            <button type="button" class="btn w-100 btn-alt-secondary d-flex justify-content-between align-items-center" data-toggle="class-toggle" data-target="#main-navigation" data-class="d-none">
                                Menu
                                <i class="fa fa-bars"></i>
                            </button>
                        </div>
                        <!-- END Toggle Main Navigation -->
 
                        <!-- Main Navigation -->
                        <div id="main-navigation" class="d-none d-lg-block mt-2 mt-lg-0">
                            <ul class="nav-main nav-main-dark nav-main-horizontal nav-main-hover">
                                <ul class="nav-main nav-main-horizontal nav-main-hover nav-main-dark">
                                    <li class="nav-main-item">
                                        <a class="nav-main-link active" href="https://waxa.pw/main">
                                            <i class="nav-main-link-icon fa fa-home"></i>
                                            <span class="nav-main-link-name">Home</span>
                                        </a>
                                    </li>
                                    <li class="nav-main-heading">Manage</li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="#">
                                            <i class="nav-main-link-icon fa fa-briefcase"></i>
                                            <span class="nav-main-link-name">Products</span>
                                        </a>
                                        <ul class="nav-main-submenu">
                                            <li class="nav-main-item">
                                                <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="#">
                                                    <i class="nav-main-link-icon fa fa-server"></i>
                                                    <span class="nav-main-link-name">Hosts</span>
                                                </a>
                                                <ul class="nav-main-submenu">
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/rdp">
                                                            <i class="nav-main-link-icon fa fa-desktop"></i>
                                                            <span class="nav-main-link-name">Remote Desktop</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">2</span>
 
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/shells">
                                                            <i class="nav-main-link-icon fab fa-php"></i>
                                                            <span class="nav-main-link-name">Shells</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">25</span>
 
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/cpanels">
                                                            <i class="nav-main-link-icon fab fa-cpanel"></i>
                                                            <span class="nav-main-link-name">cPanels</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">173</span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/ssh">
                                                            <i class="nav-main-link-icon fab fa-linux"></i>
                                                            <span class="nav-main-link-name">SSHs</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">1</span>
                                                        </a>
                                                    </li>
 
 
                                                </ul>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="#">
                                                    <i class="nav-main-link-icon fa fa-paper-plane"></i>
                                                    <span class="nav-main-link-name">Senders</span>
                                                </a>
                                                <ul class="nav-main-submenu">
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/mailer">
                                                            <i class="nav-main-link-icon fa fa-leaf"></i>
                                                            <span class="nav-main-link-name">Mailers</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">5</span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/smtp">
                                                            <i class="nav-main-link-icon fab fa-mailchimp"></i>
                                                            <span class="nav-main-link-name">SMTPs</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">2</span>
                                                        </a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="#">
                                                    <i class="nav-main-link-icon si si-envelope-letter"></i>
                                                    <span class="nav-main-link-name">WebMails</span>
                                                </a>
                                                <ul class="nav-main-submenu">
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/webmail/cpanel">
                                                            <i class="nav-main-link-icon fab fa-cpanel fa-2x"></i>
                                                            <span class="nav-main-link-name">cPanel</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">
                                                                1
                                                            </span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/webmail/office365">
                                                            <i class="nav-main-link-icon fab fa-microsoft"></i>
                                                            <span class="nav-main-link-name">Office365</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">
                                                                0
                                                            </span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/webmail/godaddy">
                                                            <i class="nav-main-link-icon fab fa-golang"></i>
                                                            <span class="nav-main-link-name">GoDaddy</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">
                                                                0
                                                            </span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/webmail/sfr">
                                                            <i class="nav-main-link-icon fab fa-1x fa-s"></i>
                                                            <span class="nav-main-link-name">SFR</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">
                                                                0
                                                            </span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/webmail/hostinger">
                                                            <i class="nav-main-link-icon fab fa-1x fa-hire-a-helper"></i>
                                                            <span class="nav-main-link-name">Hostinger</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">
                                                                0
                                                            </span>
                                                        </a>
                                                    </li>
                                                    <li class="nav-main-item">
                                                        <a class="nav-main-link" href="https://waxa.pw/webmail/aruba">
                                                            <i class="nav-main-link-icon fa fa-1x fa-a"></i>
                                                            <span class="nav-main-link-name">Aruba</span>
                                                            <span class="nav-main-link-badge badge rounded-pill bg-primary">
                                                                0
                                                            </span>
                                                        </a>
                                                    </li>
                                                </ul>
                                            </li>
 
                                        </ul>
                                    </li>
                                    <li class="nav-main-heading">Accounts</li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="https://waxa.pw/account">
                                            <i class="nav-main-link-icon fa fa-universal-access"></i>
                                            <span class="nav-main-link-name">Accounts</span>
                                        </a>
                                        <ul class="nav-main-submenu">
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account">
                                                    <i class="nav-main-link-icon fa fa-people-group"></i>
                                                    <span class="nav-main-link-name">Main Sections</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=3">
                                                    <i class="nav-main-link-icon fab fa-facebook"></i>
                                                    <span class="nav-main-link-name">Social Media</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=9">
                                                    <i class="nav-main-link-icon fab fa-magento"></i>
                                                    <span class="nav-main-link-name">Marketing</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=1">
                                                    <i class="nav-main-link-icon fa fa-gamepad"></i>
                                                    <span class="nav-main-link-name">Games</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=15">
                                                    <i class="nav-main-link-icon fa fa-mobile-button"></i>
                                                    <span class="nav-main-link-name">Mobile Games</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=11">
                                                    <i class="nav-main-link-icon fab fa-twitch"></i>
                                                    <span class="nav-main-link-name">Streaming</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=12">
                                                    <i class="nav-main-link-icon fa fa-restroom"></i>
                                                    <span class="nav-main-link-name">Dating</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=10">
                                                    <i class="nav-main-link-icon fab fa-btc"></i>
                                                    <span class="nav-main-link-name">Cryptocurrency</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=13">
                                                    <i class="nav-main-link-icon fab fa-youtube"></i>
                                                    <span class="nav-main-link-name">Entertainment</span>
                                                </a>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=14">
                                                    <i class="nav-main-link-icon fa fa-robot"></i>
                                                    <span class="nav-main-link-name">Artificial intelligence</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=36">
                                                    <i class="nav-main-link-icon si si-envelope-letter"></i>
                                                    <span class="nav-main-link-name">Emails</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=37">
                                                    <i class="nav-main-link-icon fab fa-medapps"></i>
                                                    <span class="nav-main-link-name">VPN</span>
                                                </a>
                                            </li>
                                            <li class="nav-main-item">
                                                <a class="nav-main-link" href="https://waxa.pw/account?parent_id=38">
                                                    <i class="nav-main-link-icon fab fa-app-store"></i>
                                                    <span class="nav-main-link-name">Applications</span>
                                                </a>
                                            </li>
                                    </li>
                                </ul>
                                </li>
                                <li class="nav-main-heading">Services</li>
                                <li class="nav-main-item">
                                    <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="#">
                                        <i class="nav-main-link-icon fab fa-searchengin"></i>
                                        <span class="nav-main-link-name">Services</span>
                                    </a>
                                    <ul class="nav-main-submenu">
                                        <li class="nav-main-item">
                                            <a class="nav-main-link" href="https://waxa.pw/requests">
                                                <i class="nav-main-link-icon si si-magnifier-add"></i>
                                                <span class="nav-main-link-name">Special Requests</span>
                                            </a>
                                        </li>
                                        <li class="nav-main-item">
                                            <a class="nav-main-link" href="javascript:void(0)">
                                                <i class="nav-main-link-icon fab fa-telegram"></i>
                                                <span class="nav-main-link-name">Telegram Services</span>
                                            </a>
                                        </li>
                                        <li class="nav-main-item">
                                            <a class="nav-main-link" href="javascript:void(0)">
                                                <i class="nav-main-link-icon si si-social-facebook"></i>
                                                <span class="nav-main-link-name">Social Media Services</span>
                                            </a>
                                        </li>
                                        <li class="nav-main-item">
                                            <a class="nav-main-link" href="javascript:void(0)">
                                                <i class="nav-main-link-icon si si-link"></i>
                                                <span class="nav-main-link-name">Backlinks Services</span>
                                                <span class="nav-main-link-badge badge rounded-pill bg-primary">920</span>
                                            </a>
                                        </li>
                                        <li class="nav-main-item">
                                            <a class="nav-main-link" href="javascript:void(0)">
                                                <i class="nav-main-link-icon si si-users"></i>
                                                <span class="nav-main-link-name">Traffic Services</span>
                                                <span class="nav-main-link-badge badge rounded-pill bg-primary">7</span>
                                            </a>
                                        </li>
                                    </ul>
                                </li>
                            </ul>
                            </li>
                            <li class="nav-main-heading">Themes</li>
                            <li class="nav-main-item ms-lg-auto">
                                <a class="nav-main-link nav-main-link-submenu" data-toggle="submenu" aria-haspopup="true" aria-expanded="false" href="#">
                                    <i class="nav-main-link-icon fa fa-brush"></i>
                                    <span class="nav-main-link-name d-lg-none">Themes</span>
                                </a>
                                <ul class="nav-main-submenu nav-main-submenu-right">
                                    <li class="nav-main-item">
                                        <a class="nav-main-link" data-toggle="theme" data-theme="default" href="#">
                                            <i class="nav-main-link-icon fa fa-square text-default"></i>
                                            <span class="nav-main-link-name">Default</span>
                                        </a>
                                    </li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link" data-toggle="theme" data-theme="assets/css/themes/amethyst.min.css" href="#">
                                            <i class="nav-main-link-icon fa fa-square text-amethyst"></i>
                                            <span class="nav-main-link-name">Amethyst</span>
                                        </a>
                                    </li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link" data-toggle="theme" data-theme="assets/css/themes/city.min.css" href="#">
                                            <i class="nav-main-link-icon fa fa-square text-city"></i>
                                            <span class="nav-main-link-name">City</span>
                                        </a>
                                    </li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link" data-toggle="theme" data-theme="assets/css/themes/flat.min.css" href="#">
                                            <i class="nav-main-link-icon fa fa-square text-flat"></i>
                                            <span class="nav-main-link-name">Flat</span>
                                        </a>
                                    </li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link" data-toggle="theme" data-theme="assets/css/themes/modern.min.css" href="#">
                                            <i class="nav-main-link-icon fa fa-square text-modern"></i>
                                            <span class="nav-main-link-name">Modern</span>
                                        </a>
                                    </li>
                                    <li class="nav-main-item">
                                        <a class="nav-main-link" data-toggle="theme" data-theme="assets/css/themes/smooth.min.css" href="#">
                                            <i class="nav-main-link-icon fa fa-square text-smooth"></i>
                                            <span class="nav-main-link-name">Smooth</span>
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            </ul>
                        </div>
                        <!-- END Main Navigation -->
                    </div>
                </div>
            </div>
            <main id="main-container">
                <!-- Page Content -->
                <meta name="csrf-token" content="mOlCavC3E6VXQhSwZNOQWef0WpTPVO0b7nV9j9EY">
                <!-- Hero -->
                <div class="bg-body-light">
                    <div class="content content-full">
                        <div class="d-flex flex-column flex-sm-row justify-content-sm-between align-items-sm-center py-2">
                            <div class="flex-grow-1">
                                <h1 class="h3 fw-bold mb-1">
                                    Tickets Manager
                                </h1>
                                <h2 class="fs-base lh-base fw-medium text-muted mb-0">
                                    That feeling of money when you start adding your Tickets.
 
                                </h2>
                            </div>
                            <nav class="flex-shrink-0 mt-3 mt-sm-0 ms-sm-3" aria-label="breadcrumb">
                                <ol class="breadcrumb breadcrumb-alt">
                                    <li class="breadcrumb-item">
                                        <a class="link-fx" href="https://waxa.pw/main">Dashboard</a>
                                    </li>
                                    <li class="breadcrumb-item" aria-current="page">
                                        Tickets
                                    </li>
                                </ol>
                            </nav>
                        </div>
                    </div>
                </div>
                <!-- END Hero -->
 
                <div class="content">
                    <!-- Quick Overview -->
                    <div class="row g-3 mb-4 mt-3">
                        <!-- Submit New Ticket -->
                        <div class="col-6 col-lg-3">
                            <a class="block block-rounded block-link-pop bg-body-extra-light h-100 mb-2 text-center" href="#" onclick="openTicketForm()" data-bs-toggle="tooltip" data-bs-placement="top" title="Create new support ticket">
                                <div class="block-content block-content-full p-3">
                                    <div class="fs-2 fw-bold text-success">
                                        <i class="fas fa-plus-circle fa-2x animate-bounce"></i>
                                    </div>
                                </div>
                                <div class="block-content py-2 bg-body-light">
                                    <p class="fw-medium fs-sm text-success mb-0">
                                        <i class="fas fa-arrow-up me-1 animate-pulse"></i> Submit New Ticket
                                    </p>
                                </div>
                            </a>
                        </div>
 
                        <!-- Open Tickets -->
                        <div class="col-6 col-lg-3">
                            <div class="block block-rounded block-link-pop bg-body-extra-light h-100 mb-2" data-bs-toggle="tooltip" data-bs-placement="top" title="Currently active open tickets">
                                <div class="block-content block-content-full p-3">
                                    <div class="d-flex align-items-center justify-content-between">
                                        <div>
                                            <div class="fs-sm fw-semibold text-uppercase text-muted mb-2">
                                                <i class="fas fa-inbox me-1 animate-slide"></i> Open
                                            </div>
                                            <div class="fs-2 fw-bold text-primary">
                                                <span class="count-up">0</span>
                                            </div>
                                        </div>
                                        <i class="fas fa-envelope-open fa-2x text-primary opacity-25 animate-float"></i>
                                    </div>
                                </div>
                                <div class="block-content py-2 bg-body-light">
                                    <p class="fw-medium fs-sm text-primary mb-0">
                                        <i class="fas fa-arrow-up me-1"></i> Active Tickets
                                    </p>
                                </div>
                            </div>
                        </div>
 
                        <!-- Pending Tickets -->
                        <div class="col-6 col-lg-3">
                            <div class="block block-rounded block-link-pop bg-body-extra-light h-100 mb-2" data-bs-toggle="tooltip" data-bs-placement="top" title="Tickets awaiting response">
                                <div class="block-content block-content-full p-3">
                                    <div class="d-flex align-items-center justify-content-between">
                                        <div>
                                            <div class="fs-sm fw-semibold text-uppercase text-muted mb-2">
                                                <i class="fas fa-clock me-1 animate-spin"></i> Pending
                                            </div>
                                            <div class="fs-2 fw-bold text-warning">
                                                <span class="count-up">1</span>
                                            </div>
                                        </div>
                                        <i class="fas fa-hourglass-half fa-2x text-warning opacity-25 animate-float"></i>
                                    </div>
                                </div>
                                <div class="block-content py-2 bg-body-light">
                                    <p class="fw-medium fs-sm text-warning mb-0">
                                        <i class="fas fa-arrow-up me-1"></i> Awaiting Response
                                    </p>
                                </div>
                            </div>
                        </div>
 
                        <!-- Closed Tickets -->
                        <div class="col-6 col-lg-3">
                            <div class="block block-rounded block-link-pop bg-body-extra-light h-100 mb-2" data-bs-toggle="tooltip" data-bs-placement="top" title="Resolved and closed tickets">
                                <div class="block-content block-content-full p-3">
                                    <div class="d-flex align-items-center justify-content-between">
                                        <div>
                                            <div class="fs-sm fw-semibold text-uppercase text-muted mb-2">
                                                <i class="fas fa-check-circle me-1 animate-bounce"></i> Closed
                                            </div>
                                            <div class="fs-2 fw-bold text-danger">
                                                <span class="count-up">0</span>
                                            </div>
                                        </div>
                                        <i class="fas fa-archive fa-2x text-danger opacity-25 animate-float"></i>
                                    </div>
                                </div>
                                <div class="block-content py-2 bg-body-light">
                                    <p class="fw-medium fs-sm text-danger mb-0">
                                        <i class="fas fa-arrow-up me-1"></i> Resolved Tickets
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
 
                    <style>
                        /* Animation Keyframes */
                        @keyframes float {
 
                            0%,
                            100% {
                                transform: translateY(0);
                            }
 
                            50% {
                                transform: translateY(-8px);
                            }
                        }
 
                        @keyframes slide {
 
                            0%,
                            100% {
                                transform: translateX(0);
                            }
 
                            50% {
                                transform: translateX(5px);
                            }
                        }
 
                        @keyframes bounce {
 
                            0%,
                            100% {
                                transform: translateY(0);
                            }
 
                            50% {
                                transform: translateY(-5px);
                            }
                        }
 
                        @keyframes pulse {
 
                            0%,
                            100% {
                                transform: scale(1);
                            }
 
                            50% {
                                transform: scale(1.2);
                            }
                        }
 
                        @keyframes spin {
                            0% {
                                transform: rotate(0deg);
                            }
 
                            100% {
                                transform: rotate(360deg);
                            }
                        }
 
                        @keyframes tilt {
                            0% {
                                transform: perspective(1000px) rotateX(0deg) rotateY(0deg);
                            }
 
                            100% {
                                transform: perspective(1000px) rotateX(2deg) rotateY(2deg);
                            }
                        }
 
                        /* Animation Classes */
                        .animate-float {
                            animation: float 3s ease-in-out infinite;
                        }
 
                        .animate-slide {
                            animation: slide 2s ease-in-out infinite;
                        }
 
                        .animate-bounce {
                            animation: bounce 1.5s ease-in-out infinite;
                        }
 
                        .animate-pulse {
                            animation: pulse 1.5s infinite linear;
                        }
 
                        .animate-spin {
                            animation: spin 2s linear infinite;
                        }
 
                        /* Block Styles */
                        .block-link-pop {
                            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
                            transform-style: preserve-3d;
                            position: relative;
                            overflow: hidden;
                            border: 1px solid rgba(0, 0, 0, 0.075);
                            cursor: pointer;
                        }
 
                        .block-link-pop:hover {
                            transform: perspective(1000px) rotateX(2deg) rotateY(2deg) scale(1.02);
                            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
                        }
 
                        .block-link-pop::before {
                            content: '';
                            position: absolute;
                            top: 0;
                            left: 0;
                            right: 0;
                            bottom: 0;
                            background: linear-gradient(45deg,
                                    rgba(255, 255, 255, 0.1) 0%,
                                    rgba(255, 255, 255, 0.2) 50%,
                                    rgba(255, 255, 255, 0.1) 100%);
                            opacity: 0;
                            transition: opacity 0.3s ease;
                            pointer-events: none;
                        }
 
                        .block-link-pop:hover::before {
                            opacity: 1;
                        }
 
                        /* General Styles */
                        .bg-body-extra-light {
                            background-color: rgba(248, 249, 250, 0.8);
                            backdrop-filter: blur(10px);
                        }
 
                        .count-up {
                            display: inline-block;
                            font-variant-numeric: tabular-nums;
                            min-width: 60px;
                        }
 
                        .row.mb-4 {
                            margin-bottom: 1.5rem !important;
                        }
 
                        .row.mt-3 {
                            margin-top: 1rem !important;
                        }
 
                        .mb-2 {
                            margin-bottom: 0.5rem !important;
                        }
                    </style>
 
                    <!-- END Quick Overview -->
 
                    <!-- All Tickets -->
                    <div class="block block-rounded">
                        <div class="block-header block-header-default">
                            <h3 class="block-title">All Tickets</h3>
                            <div class="block-options">
                                <div class="dropdown">
                                    <button type="button" class="btn-block-option" id="dropdown-ecom-filters" data-bs-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                        Filters <i class="fa fa-angle-down ms-1"></i>
                                    </button>
                                    <div class="dropdown-menu dropdown-menu-end" aria-labelledby="dropdown-ecom-filters">
                                        <a class="dropdown-item d-flex align-items-center justify-content-between" href="javascript:void(0)">
                                            Active Tickets
                                            <span class="badge bg-success rounded-pill">0</span>
                                        </a>
                                        <a class="dropdown-item d-flex align-items-center justify-content-between" href="javascript:void(0)">
                                            Pending Tickets
                                            <span class="badge bg-warning rounded-pill">1</span>
                                        </a>
                                        <a class="dropdown-item d-flex align-items-center justify-content-between" href="javascript:void(0)">
                                            Closed Tickets
                                            <span class="badge bg-danger rounded-pill">0</span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="block-content">
                            <!-- All Tickets Table -->
                            <div class="table-responsive">
                                <table class="table table-bordered table-striped table-vcenter js-dataTable-full" id="usertickets-table">
                                    <thead>
                                        <tr>
                                            <th title="Id">Id</th>
                                            <th title="Title">Title</th>
                                            <th title="Status" width="18%">Status</th>
                                            <th title="Last Replay" width="15%">Last Replay</th>
                                            <th title="Created At" width="20%">Created At</th>
                                            <th title="View" width="100">View</th>
                                        </tr>
                                    </thead>
                                </table>
                            </div>
                            <!-- END All Tickets Table -->
                        </div>
                    </div>
                    <!-- END All Tickets -->
                </div>
                <!-- END Page Content -->
            </main>
        </main>
        <!-- Footer -->
        <footer id="page-footer" class="bg-body-extra-light">
            <div class="content py-3">
                <div class="row fs-sm">
                    <div class="col-sm-6 order-sm-2 py-1 text-center text-sm-end">
                        Page Loaded in 0.937 Seconds
                    </div>
                    <div class="col-sm-6 order-sm-1 py-1 text-center text-sm-start">
                        <a class="fw-semibold" href="https://waxa.pw/main" target="_blank">WaXa V1.0</a> © <span data-toggle="year-copy"></span>
                    </div>
                </div>
            </div>
        </footer>
        <!-- END Footer -->
    </div>
 
    <!-- Include jQuery first -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Then include Bootstrap Notify -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-notify/0.2.0/js/bootstrap-notify.js"></script>
 
    <!-- OneUI JS -->
    <script src="https://waxa.pw/assets/js/oneui.app.min.js"></script>
    <!-- Page JS Plugins -->
    <script src="https://waxa.pw/assets/js/plugins/chart.js/chart.umd.js"></script>
    <script src="https://waxa.pw/assets/js/lib/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11/dist/sweetalert2.all.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/choices.js/public/assets/scripts/choices.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables/jquery.dataTables.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-bs5/js/dataTables.bootstrap5.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-responsive/js/dataTables.responsive.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-responsive-bs5/js/responsive.bootstrap5.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons/dataTables.buttons.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons-bs5/js/buttons.bootstrap5.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons-jszip/jszip.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons-pdfmake/pdfmake.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons-pdfmake/vfs_fonts.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons/buttons.print.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/datatables-buttons/buttons.html5.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/flatpickr/flatpickr.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/bootstrap-datepicker/js/bootstrap-datepicker.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/bootstrap-maxlength/bootstrap-maxlength.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/select2/js/select2.full.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/jquery.maskedinput/jquery.maskedinput.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/ion-rangeslider/js/ion.rangeSlider.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/dropzone/min/dropzone.min.js"></script>
    <script src="https://waxa.pw/assets/js/pages/be_pages_dashboard_v1.min.js"></script>
    <script src="https://waxa.pw/assets/js/plugins/slick-carousel/slick.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        One.helpersOnLoad(['js-flatpickr', 'jq-datepicker', 'jq-maxlength', 'jq-select2', 'jq-masked-inputs', 'jq-rangeslider', 'jq-slick']);
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Initialize animations
            AOS.init({
                duration: 800,
                once: true
            });
 
            // Number counting animation
            gsap.utils.toArray('.countup').forEach(el => {
                gsap.to(el, {
                    innerText: el.dataset.count,
                    duration: 1.5,
                    snap: {
                        innerText: 1
                    },
                    scrollTrigger: {
                        trigger: el,
                        start: 'top 85%'
                    }
                });
            });
 
            // Hover effects
            document.querySelectorAll('.block-link-pop').forEach(block => {
                block.addEventListener('mouseenter', () => {
                    gsap.to(block.querySelector('i'), {
                        duration: 0.3,
                        scale: 1.2,
                        ease: "power2.out"
                    });
                });
                block.addEventListener('mouseleave', () => {
                    gsap.to(block.querySelector('i'), {
                        duration: 0.3,
                        scale: 1,
                        ease: "power2.out"
                    });
                });
            });
        });
 
        function openTicketForm() {
            Swal.fire({
                title: 'Submit New Ticket',
                html: `<form id="ticketForm" class="text-start">
                <div class="mb-3">
                    <label class="form-label">Ticket Type</label>
                    <select name="title" class="form-select" required>
                        <option value="Payment Related">Payment Related</option>
                        <option value="Support">Support</option>
                        <option value="Become Seller Request">Become Seller Request</option>
                        <option value="Report a Problem">Report a Problem</option>
                        <option value="Other">Other</option>
                    </select>
                </div>
                <div class="mb-3">
                    <label class="form-label">Description</label>
                    <textarea name="description" class="form-control" rows="5" 
                              placeholder="Describe your issue in detail..." required></textarea>
                </div>
            </form>`,
                showCancelButton: true,
                confirmButtonText: 'Submit Ticket',
                customClass: {
                    popup: 'animated zoomIn',
                    confirmButton: 'btn btn-success',
                    cancelButton: 'btn btn-secondary'
                },
                preConfirm: () => {
                    const form = document.getElementById('ticketForm');
                    if (!form.checkValidity()) {
                        form.classList.add('was-validated');
                        return false;
                    }
                    return {
                        title: form.title.value,
                        description: form.description.value
                    }
                }
            }).then((result) => {
                if (result.isConfirmed) {
                    submitTicket(result.value);
                }
            });
        }
 
        function submitTicket(data) {
            const csrfToken = document.querySelector('meta[name="csrf-token"]').content;
            fetch('https://waxa.pw/tickets', {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                        'X-CSRF-TOKEN': csrfToken
                    },
                    body: JSON.stringify(data)
                })
                .then(response => response.json())
                .then(data => {
                    if (data.success) {
                        Swal.fire({
                            icon: 'success',
                            title: 'Ticket Submitted!',
                            html: `<div class="alert alert-success">
                        <p>Your ticket (#${data.ticketId}) has been created successfully!</p>
                        <a href="/tickets/${data.ticketId}" class="btn btn-sm btn-primary mt-2">
                            View Ticket
                        </a>
                       </div>`,
                            showConfirmButton: false,
                            timer: 3000
                        }).then(() => {
                            window.LaravelDataTables['usertickets-table'].ajax.reload();
                        });
                    } else {
                        Swal.fire('Error!', data.message || 'Submission failed', 'error');
                    }
                })
                .catch(error => {
                    console.error('Error:', error);
                    Swal.fire('Error!', 'An error occurred while submitting your ticket', 'error');
                });
        }
    </script>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Initialize Bootstrap tooltips
            const tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'));
            tooltipTriggerList.map(tooltipTriggerEl => {
                return new bootstrap.Tooltip(tooltipTriggerEl, {
                    boundary: 'window',
                    trigger: 'hover'
                });
            });
 
            // 3D Hover Effect
            document.querySelectorAll('.block-link-pop').forEach(block => {
                block.addEventListener('mousemove', (e) => {
                    const rect = block.getBoundingClientRect();
                    const x = e.clientX - rect.left;
                    const y = e.clientY - rect.top;
                    const centerX = block.offsetWidth / 2;
                    const centerY = block.offsetHeight / 2;
 
                    const rotateX = (centerY - y) / 15;
                    const rotateY = (x - centerX) / 15;
 
                    block.style.transform = `
                perspective(1000px)
                rotateX(${rotateX}deg)
                rotateY(${rotateY}deg)
                scale(1.02)
            `;
                });
 
                block.addEventListener('mouseleave', () => {
                    block.style.transform = 'perspective(1000px) rotateX(0deg) rotateY(0deg) scale(1)';
                });
            });
 
            // Animated Counters
            const counters = document.querySelectorAll('.count-up');
 
            const animateCounter = (element, start, end, duration) => {
                let startTime = null;
                const easeOutQuad = (t) => t * (2 - t);
 
                const updateCounter = (timestamp) => {
                    if (!startTime) startTime = timestamp;
                    const progress = Math.min((timestamp - startTime) / duration, 1);
                    const current = Math.floor(easeOutQuad(progress) * (end - start) + start);
                    element.textContent = current.toLocaleString();
 
                    if (progress < 1) {
                        requestAnimationFrame(updateCounter);
                    }
                };
 
                requestAnimationFrame(updateCounter);
            };
 
            counters.forEach(counter => {
                const target = parseInt(counter.textContent.replace(/,/g, ''), 10);
                counter.textContent = '0';
                animateCounter(counter, 0, target, 1500);
            });
        });
    </script>
    <script type="module">
        $(function() {
            window.LaravelDataTables = window.LaravelDataTables || {};
            window.LaravelDataTables["usertickets-table"] = $("#usertickets-table").DataTable({
                "serverSide": true,
                "processing": true,
                "ajax": {
                    "url": "https:\/\/waxa.pw\/tickets",
                    "type": "GET",
                    "data": function(data) {
                        for (var i = 0, len = data.columns.length; i < len; i++) {
                            if (!data.columns[i].search.value) delete data.columns[i].search;
                            if (data.columns[i].searchable === true) delete data.columns[i].searchable;
                            if (data.columns[i].orderable === true) delete data.columns[i].orderable;
                            if (data.columns[i].data === data.columns[i].name) delete data.columns[i].name;
                        }
                        delete data.search.regex;
                    }
                },
                "columns": [{
                    "data": "id",
                    "name": "id",
                    "title": "Id",
                    "orderable": true,
                    "searchable": true,
                    "className": "text-center"
                }, {
                    "data": "title",
                    "name": "title",
                    "title": "Title",
                    "orderable": true,
                    "searchable": true,
                    "className": "text-center"
                }, {
                    "data": "status",
                    "name": "status",
                    "title": "Status",
                    "orderable": false,
                    "searchable": false,
                    "width": "18%",
                    "className": "text-center"
                }, {
                    "data": "last_reply_by",
                    "name": "last_reply_by",
                    "title": "Last Replay",
                    "orderable": false,
                    "searchable": false,
                    "width": "15%",
                    "className": "text-center"
                }, {
                    "data": "created_at",
                    "name": "created_at",
                    "title": "Created At",
                    "orderable": false,
                    "searchable": false,
                    "width": "20%",
                    "className": "text-center"
                }, {
                    "data": "view",
                    "name": "view",
                    "title": "View",
                    "orderable": false,
                    "searchable": false,
                    "width": 100,
                    "className": "text-center"
                }],
                "order": [0, "desc"],
                "select": {
                    "style": "single"
                },
                "responsive": true,
                "autoWidth": false,
                "autoHeight": true,
                "buttons": []
            });
        });
    </script>
</body>
 
</html>