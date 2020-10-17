<template>
  <div class="container-fluid">
    <div class="row">
     
      <!-- body section -->
      <div class="col-md-9 col-sm-8 main-body-section">

      <div class="col-md-8 col-sm-12 main">
        <h3 class="page-header">Analytics</h3>
        <span class="text-caption">Hello chris, Welcome Back!</span>
        <button class="btn btn-default square-button">
          <span class="glyphicon glyphicon-bell"></span>
        </button>
        <button class="btn btn-default square-button">
          <span class="glyphicon glyphicon-comment"></span>
        </button>

        <div class=" row body-section">
          <div class="col-md-9 banner-img">
            <img src="../assets/banner.jpeg" class="img-responsive" alt="">
          </div>
          <div class="col-md-3 message-container">
            <span class="img-container"><img src="../assets/msg-button.jpeg" alt=""></span>
            <h2> 20.k</h2>
            <div class="text-center text-white"> Pending Messages</div>
              <ul class="header-dropdown">
                <li class="dropdown">
                  <a href="#" class="dropdown-toggle text-white" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                    <i class="glyphicon glyphicon-option-horizontal text-white"></i>
                  </a>
                  <ul class="dropdown-menu pull-right">
                    <li><a href="#">Action</a></li>
                    <li><a href="#">Another action</a></li>
                  </ul>
                </li>
              </ul>
          </div>
        </div>

        <div class="row">
          <div class="col-md-6">
            <div class="card">
              <div class="header">
                <label>Followers on page</label>
                <ul class="header-dropdown">
                  <li class="dropdown">
                    <a href="#" class="dropdown-toggle text-muted" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                      <i class="glyphicon glyphicon-option-horizontal"></i>
                    </a>
                    <ul class="dropdown-menu pull-right">
                      <li><a href="#">Action</a></li>
                      <li><a href="#">Another action</a></li>
                    </ul>
                  </li>
                </ul>
              </div>
              <div class="body">
                <span class="img-container"><img src="../assets/graph1.jpeg"  class="img-responsive" alt=""></span>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="graph-two card">
              <div class="card">
                <div class="header">
                  <label>Follower gender</label>
                  <ul class="header-dropdown">
                    <li class="dropdown">
                      <a href="#" class="dropdown-toggle text-muted" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                        <i class="glyphicon glyphicon-option-horizontal"></i>
                      </a>
                      <ul class="dropdown-menu pull-right">
                        <li><a href="#">Action</a></li>
                        <li><a href="#">Another action</a></li>
                      </ul>
                    </li>
                  </ul>
                </div>
                <div class="row body">
                  <div class="col-md-4 graph-info">
                    <div class="dot dot-color-1"> </div><span>Female</span>
                    <div class="font-bold"> 80%</div>

                    <div class="dot dot-color-2"></div><span>Male</span>
                    <div class="font-bold"> 20%</div>
                  </div>
                  <div class="col-md-8 graph-img">
                    <span class="img-container"><img src="../assets/graph2.jpeg"  class="img-responsive" alt=""></span>
                  </div>
                </div>
              </div>
            </div>
          
            <div class="row">
              <div class="col-md-6 col-sm-6 graph-img">
                <div class="card">
                  <div class="row body">
                    <img src="../assets/line-graph1.jpeg" class="col-md-6 col-sm-6 line-graph-img img-responsive" alt="">
                    <div class="col-md-6 col-sm-6 line-graph"><span>Photo Clicks</span><div class="font-bold"> 70%</div>
                      <div class="text-center">
                        <ul class="header-dropdown">
                          <li class="dropdown">
                            <a href="#" class="dropdown-toggle text-muted" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                              <i class="glyphicon glyphicon-option-horizontal"></i>
                            </a>
                            <ul class="dropdown-menu pull-right">
                              <li><a href="#">Action</a></li>
                              <li><a href="#">Another action</a></li>
                            </ul>
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="col-md-6 col-sm-6 graph-img">
                <div class="card">
                  <div class="row body">
                    <img src="../assets/line-graph2.jpeg" class="col-md-6 col-sm-6 line-graph-img img-responsive" alt="">
                    <div class="col-md-6 col-sm-6 line-graph">
                      <span>Link Clicks</span><div class="font-bold"> 30%</div>
                      <div class="text-center">
                        <ul class="header-dropdown">
                          <li class="dropdown">
                            <a href="#" class="dropdown-toggle text-muted" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                              <i class="glyphicon glyphicon-option-horizontal"></i>
                            </a>
                            <ul class="dropdown-menu pull-right">
                              <li><a href="#">Action</a></li>
                              <li><a href="#">Another action</a></li>
                            </ul>
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-4 col-sm-12 ">
        <div class="sidebar-right">
          <div class="container-fluid">
            <div class="filter-section">
              <div class="row">
                <div class="col-md-12">
                  <div class="input-group">
                    <!-- <span class="glyphicon glyphicon-search form-control-feedback"></span> -->
                    <input type="text" class="form-control" id="myInput" placeholder="Search Dashboard">
                    <span class="input-group-btn">
                      <button class="btn btn-default" type="button">
                        <svg width="32" height="16" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                          <rect class="fltr-line1" x="7" y="10" width="18" height="1" fill="black"/>
                          <rect class="fltr-line2" x="7" y="20" width="18" height="1" fill="black"/>
                          <circle class="fltr-crcl1" cx="13" cy="20.5" r="2.5" fill="white" stroke="black"/>
                          <circle class="fltr-crcl2" cx="19" cy="10.5" r="2.5" fill="white" stroke="black"/>
                        </svg>
                        </button>
                    </span>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="person-detail">
              <div class="row">
                <div class="col-md-3">  <img src="../assets/smiley1.jpeg" alt=""> </div>
                <div class="col-md-9">
                  <form action="">
                    <select name="profile" id="">
                      <option value="facebook" selected>Company Name</option>
                      <option value="facebook">Facebook</option>
                      <option value="instagram">Instagram</option>
                    </select>
                  </form>
                  <div class="social-media-link">
                    <img src="../assets/fb.svg"  class="fb-icon" alt=""> <a href="https://www.facebook.com/" class="text-muted"> facebook.com/companyname</a>
                  </div>
                </div>
              </div>
            </div> <hr>

            <!-- carousel -->
            <div class="row"> 
              <div class="col-md-12">
                <div id="" class="carousel xssszzz" data-ride="carousel">
                  <!-- Wrapper for slides -->
                  <div class="carousel-inner" role="listbox">
                    <div class="item active">
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">3.k</div>
                          <div class="bar-graph text-center">Average Likes</div>
                        </div>
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="30" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">22.k</div>
                          <div class="bar-graph text-center">Average Comments</div>
                        </div>
          
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">3.k</div>
                          <div class="bar-graph text-center">Average Share</div>
                        </div>
          
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                    </div>
                    
                    <div class="item">
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">4.k</div>
                          <div class="bar-graph text-center">Average Likes</div>
                        </div>
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="30" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">28.k</div>
                          <div class="bar-graph text-center">Average Comments</div>
                        </div>
          
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">6.k</div>
                          <div class="bar-graph text-center">Average Share</div>
                        </div>
          
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-danger" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      
                    </div>
                    <div class="item">
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">3.k</div>
                          <div class="bar-graph text-center">Average Likes</div>
                        </div>
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="30" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">22.k</div>
                          <div class="bar-graph text-center">Average Comments</div>
                        </div>
          
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-success" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 80%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      <div class="row bar-graph-container">
                        <div class="col-md-3">
                          <div class="font-extra-bold text-center">3.k</div>
                          <div class="bar-graph text-center">Average Share</div>
                        </div>
          
                        <div class="col-md-9">
                          <div class="text-right bar-graph"> date here</div>
                          <div class="progress">
                            <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="40" aria-valuemin="0" aria-valuemax="100" style="width: 40%;">
                            </div>
                          </div>
                          <span class="glyphicon glyphicon-thumbs-up bar-icon-right"></span>
                        </div>
                      </div>
                      
                    </div>
                  </div>
                  <!-- Indicators -->
                  <ol class="carousel-indicators">
                    <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
                    <li data-target="#carousel-example-generic" data-slide-to="1"></li>
                    <li data-target="#carousel-example-generic" data-slide-to="2"></li>
                  </ol>
                
                </div>
              </div>
            </div>

            <!-- bottom card -->
            <div class="row">
              <div class="col-md-12">
                <div class="bottom-card card">
                  <div class="header">
                    <label class="text-white">234.000.k</label> 
                    <div class="text-white"> Total followers</div>
                      <ul class="header-dropdown">
                        <li class="dropdown">
                          <a href="#" class="dropdown-toggle text-white" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                            <i class="glyphicon glyphicon-option-horizontal text-white"></i>
                          </a>
                          <ul class="dropdown-menu pull-right">
                            <li><a href="#">Action</a></li>
                            <li><a href="#">Another action</a></li>
                          </ul>
                        </li>
                      </ul>
                  </div>
                  <div>
                    <img src="../assets/line-graph-3.jpeg" class="img-responsive horizontal-line-graph" alt="">
                  </div>
                </div>
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
export default {
}
</script>
<style scoped>

</style>
