<template>
  <div class="container-fluid">
  <div class="row">
    <nav id="sidebar" class="col-md-3 col-lg-2 d-md-block" style=" background-color: #F6F6F6;
" >
      
  <a class="nav-link"  href="home.vue">
    <img src="@/assets/logo.svg" alt="El" class="me-1 " />
  </a>

  <ul class="nav flex-column">
    <li class="nav-item">
      <a class="nav-link active text-warning" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/side.svg" alt="El" class="me-1 " /><img src="@/assets/hom.svg" alt="El" class="me-1 " /> Home
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/rev.svg" alt="El" class="me-1 " /> Orders
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/ord.svg" alt="El" class="me-1 " /> Reviews
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/cli.svg" alt="El" class="me-1 " />  Clients
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/pan.svg" alt="El" class="me-1 " />  Companies
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/tru.svg" alt="El" class="me-1 " /> Trucks
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/rand.svg" alt="El" class="me-1 " /> Brands
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/cit.svg" alt="El" class="me-1 " /> Cities
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/mana.svg" alt="El" class="me-1 " /> Content Management
      </a>
    </li>
    <li class="nav-item">
      <div class="dropdown2">
<button class="btn btn-sm dropdown-toggle" type="button" data-bs-toggle="dropdown">
  <img src="@/assets/syst.svg" alt="El" class="me-1 " style="font-size: 12px;"/> Permissions
</button>
      </div>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/perm.svg" alt="El" class="me-1 " /> System Management
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/tran.svg" alt="El" class="me-1 " /> Translation
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/tact.svg" alt="El" class="me-1 " /> Contact
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link text-dark" href="#" style="font-size: 12px; text-align: left; padding: 10px ;">
        <img src="@/assets/ent.svg" alt="El" class="me-1 " /> Client Review
      </a>
    </li>
  </ul>
</nav>

    
<main class="col-md-9 col-lg-10 px-4">
  <div class="col-md-12">
    <div class="d-flex flex-column align-items-start">
        <h4 class="mt-3" style="margin-top: 80px;">Dashboard Overview</h4>
        <p class="text-mt1" style="font-size: 14px; margin-bottom: 70px">26 Sep 2023</p>
    </div>
</div>

<div class="icons-container" style="margin-top: -100px;"> 
    <img src="@/assets/noti.svg" alt="El" class="me-1" />
    <img src="@/assets/line.svg" alt="El" class="me-1" />
    <img src="@/assets/rw.svg" alt="El" class="me-1" />
    <div class="dropdown">
        <button class="btn dropdown-toggle" style="background-color:white;" type="button" data-bs-toggle="dropdown">
            INGOUDE COMPANY
        </button>
    </div>
</div>


      
   
<div class="d-flex align-items-center justify-content-start">
<div class="form-check form-check-inline me-3">
  <input class="form-check-input" type="radio" id="all" name="filter" checked />
  <label class="form-check-label" for="all">All</label>
</div>

<div class="form-check form-check-inline me-3">
  <input class="form-check-input" type="radio" id="Ha" name="filter" checked />
</div>

<div class="input-group mx-2" style="width: 150px;">
  <span class="input-group-text" id="fromLabel" style="font-size: 12px;">From</span>
  <input class="form-control" type="date"  style="font-size: 12px;" value="2023-09-26" />
</div>

<div class="input-group mx-2" style="width: 150px;">
  <span class="input-group-text" id="toLabel" style="font-size: 12px;">To</span>
  <input class="form-control" type="date"  style="font-size: 12px;" value="2023-09-26" />
</div>
<button class="btn btn-warning ms-2" style="height: 30px; font-size: 12px;">Find</button>
</div>




<div class="row mb-3">
<div class="col-md-3">
<div class="card custom-card text-center">
<div class="card-body">
<h5 class="card-title text-secondary text-left" style="font-size: 16px; ">
<img src="@/assets/kh.svg" alt="El" class="me-1 " />Order Number
</h5>
<p class="card-text" style="font-size: 24px;">1000 <sub style="font-size: 10px;color: gray;">Orders</sub></p>
</div>
</div>
</div>


<div class="col-md-3">
<div class="card custom-card text-center">
<div class="card-body">
<h6 class="card-title text-secondary" style="font-size: 16px;">
<img src="@/assets/nou.svg" alt="El" class="me-1 " />Company Number
</h6>
<p class="card-text" style="font-size: 24px;">1000000 <sub style="font-size: 10px;color: gray;">SR</sub></p>
</div>
</div>
</div>


<div class="col-md-3">
<div class="card custom-card text-center">
<div class="card-body">
<h6 class="card-title text-secondary" style="font-size: 16px;">
<img src="@/assets/men.svg" alt="El" class="me-1 " />Drivers Number
</h6>
<p class="card-text" style="font-size: 24px;">500 <sub style="font-size: 10px; color: gray;">Driver</sub></p>
</div>
</div>
</div>


<div class="col-md-3">
<div class="card custom-card text-left">
<div class="card-body">
<h6 class="card-title text-secondary" style="font-size: 16px;">
<img src="@/assets/nero.svg" alt="El" class="me-1 " />Total Sales
</h6>
<p class="card-text" style="font-size: 24px;">500 <sub style="font-size: 10px; color:gray;">Driver</sub></p>
</div>
</div>
</div>
</div>


  
      <div class="row mb-4">

<div class="col-md-3">
<div class="card custom-card2 text-center">
<div class="card-body">
<h5 class="card-title" style="font-size: 14px; text-align:center;">Waiting For Loading</h5>
<div class="d-flex justify-content-center align-items-center">
<div class="position-relative">
<img src="@/assets/loa.svg" alt="El" class="me-3 n" style="text-align: center;" />
<div class="Ad2" style="width: 80px; height: 80px;"></div>
<div class="position-absolute top-50 start-50 translate-middle"></div>
</div>
</div>
</div>
</div>
</div>


<div class="col-md-3">
<div class="card custom-card2 text-center">
<div class="card-body">
<h5 class="card-title" style="font-size: 14px; text-align: center;">Waiting For Arrive</h5>
<div class="d-flex justify-content-center align-items-center">
<div class="position-relative">
<img src="@/assets/arr.svg" alt="El" class="me-3 n" style="text-align: center;"/>
<div class="Ad3" style="width: 80px; height: 80px;"></div>
<div class="position-absolute top-50 start-50 translate-middle"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="col-md-3">
  <div class="card custom-card2 text-center">
    <div class="card-body">
      <h5 class="card-title" style="font-size: 14px; text-align: center;">Completed</h5>
      <div class="d-flex justify-content-center align-items-center">
        <div class="position-relative">
          <img src="@/assets/com.svg" alt="El" class="me-3 n" style="text-align: center;"/>
          <div class=" Ad" style="width: 80px; height: 80px;"></div>
          <div class="position-absolute top-50 start-50 translate-middle"></div>
        </div>
      </div>
    </div>
  </div>
</div>


<div class="col-md-3">
  <div class="card custom-card2 text-center">
    <div class="card-body">
      <h5 class="card-title text-center" style="font-size: 14px;">Canceled</h5>
      <div class="d-flex justify-content-center align-items-center">
        <div class="position-relative">
          <img src="@/assets/can.svg" alt="El" class="me-3 n" style="text-align: center;"/>
          <div class="Ad4" style="width: 80px; height: 80px;"></div>
          <div class="position-absolute top-50 start-50 translate-middle">
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>


<div class="row d-flex">
<div class="col-6">
  <div class="card">
    <div class="card-body">
      <h5 class="card-title text-left" style="font-size: 14px;">TOP 5 Companies</h5>
      <table class="table table-borderless table-md" >
        <thead>
          <tr  >
            <td style="color: gray; font-size: 12px;">Company Name</td>
            <td style="color: gray; font-size: 12px;">Order Qty</td>
            <td style="color: gray; font-size: 12px;">Amount</td>
          </tr>
        </thead>
        <tbody>
          <tr  style="font-size: 12px;">
            <td>Gillette</td>
            <td>5000</td>
            <td>50000 SR</td>
          </tr>
          <tr  style="font-size: 12px;">
            <td>Louis Vuitton</td>
            <td>3000</td>
            <td>50000 SR</td>
          </tr>
          <tr  style="font-size: 12px;">
            <td>Johnson & Johnson</td>
            <td>2000</td>
            <td>50000 SR</td>
          </tr>
          <tr  style="font-size: 12px;">
            <td>Nintendo</td>
            <td>1000</td>
            <td>50000 SR</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="col-md-3">
  <div class="card custom-card2 mb-4">
    <div class="card-body text-center">
      <h5 class="card-title" style="font-size: 14px; text-align: center;">Order Repeated</h5>
      <div class="d-flex justify-content-center align-items-center">
        <div class="position-relative">
          <img src="@/assets/can.svg" alt="El" class="me-3 n" />
          <div class="Ad5" style="width: 80px; height: 80px;"></div>
          <div class="position-absolute top-50 start-50 translate-middle"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="col-md-3">
  <div class="card custom-card2">
    <div class="card-body text-center">
      <h5 class="card-title" style="font-size: 14px; text-align: center;">Commission</h5>
      <div class="d-flex justify-content-center align-items-center">
        <div class="position-relative">
          <img src="@/assets/gun.svg" alt="El" class="me-3 n" />
          <div class="Ad6" style="width: 80px; height: 80px;">
            <div class="position-absolute top-50 start-50 translate-middle"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</div>
    </main>
  </div>
  </div>
</template>
<script>
export default {
name: 'HomeView',
};


</script>

<style scoped>
body {
background-color:aliceblue;
}
.sidebar {
position: fixed;
top: 0;
bottom: 0;
z-index: 100;
height: 100%;
background-color: #F6F6F6;

}

.card-title{
text-align: left;
}
.card-body{
text-align: left;
}
.dropdown2{
background-color: #F6F6F6;
;
font-size: 12px;
 text-align:left;

}
.custom-card {
width: 250px;
height: 120px;
border-radius: 5px 5px 5px 5px;
border-top: 1px solid #ccc; 
border-left: 1px solid #ccc; 
margin: 10px;
padding: 5px;
}
S
.custom-card .card-body {
padding: 1; 
}

.custom-card .card-title {
margin-bottom: 10px; 
}

.row {
gap: 0px; 
}
.form-check-input:checked
 {
  border-color:  #FBA81A;
  background-color:  #FBA81A;
}
.custom-card2 {
width: 250px;
height: 220px;
border-radius: 5px 5px 5px 5px;
border-top: 1px solid #ccc; 
margin: 10px;
padding: 5px;

}

.custom-card2 .card-body {
padding: 0;
}

.custom-card2 .card-title {
margin-bottom: 10px; 
}

.row {
gap: 0px; 
}

.table-container {
width: 564px;
height: 220px;
position: absolute;
top: 546px;
left: 248px;
gap: 0px;
border-radius: 5px;
border: 1px solid black;
opacity: 1; 
margin: 10px;
padding-left: 20px; 
}

.table {
margin-bottom: 0;
}

.icons-container {
display: flex; 
justify-content: flex-end; 
align-items: center; 
}

.me-1 {
margin-left: 8px; 
}

</style>
