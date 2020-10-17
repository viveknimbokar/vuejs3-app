<template>
  <my-sidebar></my-sidebar>
  <my-body></my-body>
</template>

<script>
import SideBar from './components/Sidebar.vue'
import Body from './components/Body.vue'

export default {
  name: 'App',
  components: {
    'my-sidebar':SideBar,
    'my-body': Body
  }
}
</script>
<style>

body{
    background-color: #f4f5f7;
}
.navbar-nav{
    margin-top: 20px;
  }
  .navbar{
    box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15);
  }
  .navbar-nav>li>a {
    padding-top: 12px;
    padding-bottom: 12px;
  }
  .navbar-inverse{
    background-color: #f6f7f9;
    border-color: #f6f7f9;
  }
  .navbar-inverse .navbar-nav>li>a {
    color: #a9aaac;
  }
  .navbar-inverse .navbar-nav>li>a:focus, .navbar-inverse .navbar-nav>li>a:hover {
    color: #695789;
  }
  .navbar-inverse .navbar-nav>.active>a, .navbar-inverse .navbar-nav>.active>a:focus, .navbar-inverse .navbar-nav>.active>a:hover {
    color: #695789;
    background-color: inherit;
    font-weight: 600;
  }
  .nav>li {
    width: 100%;
  }
  .page-title-icon {
    font-size: 2rem;
    display: flex;
    align-items: center;
    align-content: center;
    text-align: center;
    padding: .83333rem;
    margin: 0 15px 0 0;
    background: #f8bf7c;
    box-shadow: 0 0.46875rem 2.1875rem rgba(4,9,20,0.03), 0 0.9375rem 1.40625rem rgba(4,9,20,0.03), 0 0.25rem 0.53125rem rgba(4,9,20,0.05), 0 0.125rem 0.1875rem rgba(4,9,20,0.03);
    border-radius: 8px;
    width: 30px;
    height: 30px;
    float: left;
  }
  .navbar-brand {
    margin-top: 15px;
    margin-left: 12px !important;
  }
  .navbar-brand .brand-name{
    font-weight: 600;
    font-size: 18px;
    line-height: 1.5;
    color: #36353a;
  }
  .navbar-brand span{
    color: #fff;
    font-size: 16px;
  }
  .navbar-nav li a span{
    margin-right: 15px;
  }
  .img-note{
    opacity: 0.2;
    margin-bottom: 10px;
  }
  .img-container {
    text-align: center;
    display: block;
    margin-bottom: 10px;
  }
  .btn-primary{
    border-radius: 15px;
    color: #fff;
    background-color: #6d3abb;
    border-color: #6d3abb;
    width: 150px;
    margin-bottom: 20px;
  }
 
  .page-header {
    padding-bottom: 0;
    margin: 35px 0 0px;
    border-bottom: none;
    color: #36353a;
    font-weight: 600;
}
.text-caption{
    color: #a9aaac;
}
.square-button {
    font-size: 2rem;
    display: flex;
    align-items: center;
    align-content: center;
    text-align: center;
    padding: .83333rem;
    margin: -18px 10px 0 0;
    background: #f1f2f4;
    border: 1px solid #f1f2f4;
    box-shadow: 0 0.46875rem 2.45rem rgba(4,9,20,0.03), 0 0.9375rem 1.40625rem rgba(4,9,20,0.03), 0 0.25rem 0.53125rem rgba(4,9,20,0.05), 0 0.125rem 0.1875rem rgba(4,9,20,0.03);
    border-radius: 5px;
    width: 35px;
    height: 35px;
    float: right;
}
.square-button .glyphicon{
    color:#5d23ad ;
    font-size: 15px;
}
.banner-img{padding: 0;}
.banner-img img{
    border-radius: 10px;
}
.body-section {
    margin: 25px 0 20px 0;
}

.message-container{
  background: #6e36cf;
  height: auto;
  border-radius: 10px;
  padding-bottom: 18px;
}
.message-container .img-container img{
    margin-top: 10px;
}
.message-container h2{
    color: #fff;
    text-align: center;
}
.text-white{
    color: #fff;
}
.card{
    position: relative;
    background-color: #fff;
    margin-bottom: 25px;
    -webkit-box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15);
    box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15);
    border-width: 0;
    border-radius: 3px;
    display: block;
    min-height: 50px;
}
.card .header {
    color: #555;
    padding: 20px;
    position: relative;
}
.card .header .header-dropdown {
    position: absolute;
    top: 20px;
    right: 25px;
    list-style: none;
}
.card .body{
    padding: 10px;
}
.dot{
    width: 7px;
    height: 7px;
    border: 1px solid transparent;
    border-radius: 25px;
    background-color: tomato;
    display: inline-block;
    margin-right: 8px;
}
.graph-info{
    padding-left: 25px;
    padding-top: 33px;
    padding-bottom: 33px;
}
.graph-info span, .line-graph span, .bar-graph{
    color: #a9aaac;
    font-size: 12px;
}
.font-bold{
    font-weight: 600;
    margin-top: 5px;
    font-size: 16px;
}
.dot-color-1{
    
    background: #7d4ebe;
}
.dot-color-2{
    
    background: #eab19a;
}
.sidebar-right{
    bottom: 0;
    /* width: 100%; */
    top: 0;
    height: 100vh;
    /* position: absolute; */
    box-shadow: 0 0 2rem 0 rgba(136, 152, 170, .15);
    border-width: 0;
    border-radius: 3px;
    display: block;
    min-height: 50px;
    background-color: #f9fafc;
    padding-top: 35px;
}
.line-graph ul{
  list-style: none;
  padding: 0;
  margin-bottom: 0;
}
.line-graph-img{height: fit-content;}
.line-graph .text-muted{color: #a9aaac;}
.has-search .form-control {
  padding-left: 2.375rem;
}

.form-control-feedback {
  position: absolute;
  z-index: 2;
  display: block;
  width: 2.375rem;
  height: 2.375rem;
  line-height: 2.375rem;
  text-align: center;
  pointer-events: none;
  color: #aaa;
}
#myInput {
  
  background-image: url('assets/searchicon.png');
  background-position: 10px 7px;
  background-repeat: no-repeat;
  width: 100%;
  font-size: 12px;
  padding: 10px 20px 12px 40px;
  border: 1px solid #ddd;
  /* margin-bottom: 12px; */
  background-size: 15px;
  color: #a9aaac;

}
.filter-section{
  padding: 10px;
}

.progress {
  display: flex;
  height: 8px;
  overflow: hidden;
  font-size: 1.75rem;
  background-color: #e9ecef;
  border-radius: 25px;
  margin-top: 5px;
  margin-bottom: 5px;
}
.font-extra-bold{
  font-size: 20px;
  font-weight: 600;
}
.progress-bar-warning {
  background-color: #f8bd7b;
}
.bar-icon-right{
  float: right;
  right: 5px;
  color: #a9aaac;
  font-size: 12px;
}
.bar-graph-container{
  margin-top: 10px;
  margin-bottom: 10px;
}
.input-group-btn {
  border: 1px solid #ddd;
  border-left: none;
}
.form-control:focus{
  box-shadow: none;
}
.message-container .header-dropdown {
  list-style: none;
  margin: 0;
  padding: 0;
  text-align: center;
}
.input-group-btn .btn-default{border-color:#ddd;border: none;padding: 5px 12px;}
.btn-default:active:focus, .btn-default:active:hover{
  background-color:none;
  border-color: none;
}
.person-detail{
  padding: 15px 0 0px 0;
}
.carousel-indicators li{
  background-color: gray;
  border: 1px solid gray;
  width: 8px;
  height: 8px;
}
.carousel-indicators .active{
  background-color:#9C27B0;
  width: 15px;
  height: 8px;
  
}
.bottom-card{
  background: #6b39be;
  /* background: linear-gradient(90deg, #6b39be 0%, #895dd0 35%, #a481dd 100%); */
  background: linear-gradient(90deg, #7341c8 0%, #8e67d1 35%, #916ad4 100%);
  position: absolute;
  right: 0;
  width: 100%;
  top: 50px;
  border-radius: 25px 0px;
  padding-bottom: 15px
}
.bottom-card label{
  font-size: 25px;
  letter-spacing: 2px;
  font-weight: 500;
}
/* .sidebar{
  padding: 0;
} */
.left-sidebar-card{
  width: 100%;
  padding: 0;
  margin: 0;
  position: absolute;
  left: 0;
  right: 0;
  background: #fff;
  margin-top: 0px;
  padding: 15px 25px;
  z-index: 9;
}
.left-sidebar-card img{
  float: left;
  width: 38px;
  margin-right: 10px;
}
.left-sidebar-card .glyphicon{
  line-height: 1px;
  opacity: .4;
}
.horizontal-line-graph{width: 100%;}
.main-body-section{padding: 0;}
select{    
  border: none;
  font-weight: bold;
}
select:focus{    
  border: none;
  outline: none;
}
.fb-icon{
  width: 12px;
  margin: 0 4px;
}
.social-media-link a{font-size: 12px;}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #5d23ad;
}
.navbar-inverse .navbar-toggle {
  border-color: #5d23ad;
}

@media (min-width: 768px)
{
  .navbar {
    border-radius: 4px;
    width: 250px;

    transition: all 0.5s;
    font-family: "Roboto", sans-serif;
    overflow: hidden;
    display: inline-block;
    height: calc(100vh - 70px);
    position: fixed;
    top: 0;
    left: 0;
  }
  .carousel-indicators {
    bottom: -36px;
  }
  .message-container {
    margin-top: 0px;
  }
  .left-sidebar-card {
    width: 250px;
    margin: 0;
    left: 0;
    right: 0;
    background: #fff;
    margin-top: 0px;
    padding: 15px 25px;
    z-index: 9;
    position: fixed;
    bottom: 0;
}

}
@media (max-width: 768px)
{
  .message-container {
    margin-top: 20px;
  }
  .sidebar{ padding: 0;}
  .navbar-brand{    
    margin-top: 0;
    padding: 10px 15px;
  }
}

</style>
