---
layout: post
tittle: services
--- 
* {
  margin:0;
  padding:0;
}

@import url(http://fonts.googleapis.com/css?family=Droid+Sans:400,700|Droid+Serif:400,700);

html, body {
  height: 100%;
}

body {
  text-align:center;
  background-color: #5d4660;
  @include filter-gradient(#5d4660, #f7eec7, vertical);
  $experimental-support-for-svg: true;
  @include background-image(linear-gradient(top, #5d4660    0%,#f7eec7 100%));
  font-family: 'Droid Sans', sans-serif;
}

.wrap {
  width:800px;
  margin:0 auto;
  text-align:left;
  color:#989A8F;
}

.table {
  background-color:#ffffff; 
  height:325px;
  width:75%;
  margin-top:50px;  
}

ul li {
  float:left;
  width:199px;
  text-align:center;
  border-left:1px solid #DDDCD8;
}

.top {
  background-color:#EAE9E4;
  height:75px;
  h1 {
    padding-top:20px;
  }
}

.circle {
  width:60px;
  height:60px;
  border-radius:60px;
  font-size:20px;
  color:#fff;
  line-height:60px;
  text-align:center;
  background:#989A8F;
  margin-left:70px;
  margin-top:10px;
}

.bottom {
margin-top:50px;
  p {
     font-size:13px;
     font-family: 'Droid Serif', sans-serif;
     padding:5px;
    span {
     font-weight:bold; 
    }
  }
}

.sign {
  margin-top:50px;
    .button {
   border: 1px solid #989A8F;
   padding: 10px 40px;
   -webkit-border-radius: 6px;
   -moz-border-radius: 6px;
   border-radius: 6px;
   color: #989A8F;
   font-size: 14px;
   text-decoration: none;
   vertical-align: middle;
    font-size:17px;
   }
}

.purple {
  background-color:#5D4660;   
}

.white {
 color:#FFFFFF; 
}

.pink {
  background-color:#BC9B94;
}
<div class="wrap">
<div class="table">
<ul>
  
<li>
  <div class="top">
    <h1>Package #1</h1>
    <div class="circle">$750*</div>
  </div>
  <div class="bottom">
    <p><span>*750$ to 1000$</span></p>
    <p><span>1</span> New Logo</p>
    <p><span>10 to 20</span> Hours of work</p>
    <p><span>Premiun:</span> Consultation for the rest of your
company's design area. </p>
    <div class="sign">
    <a href='#' class='button'>BUY NOW</a>
    </div>
  </div>
</li>
  
<li>
  <div class="top">
    <h1>Package #2</h1>
    <div class="circle">$1000*</div>
  </div>
    <div class="bottom">
    <p><span>*$1000 to $1500</span></p>
    <p><span>Remasterize</span> your whole company design area.</p>
    <p><span>30 to 50</span> Hours of work</p>
    <p><span>Premiun:</span> Design consultation and new logo.</p>
    <div class="sign">
    <a href='#' class='button'>BUY NOW</a>
    </div>
  </div>
</li>
  
<li>
  <div class="top">
    <h1>Package #3</h1>
    <div class="circle">$1500*</div>
  </div>
    <div class="bottom">
    <p><span>*$1500 to $2000</span></p>
    <p><span>Start form 0</span> New everything</p>
    <p><span>50 to 70</span> hours of work</p>
    <p><span>Premiun:</span> More than one professional designer will be working for this project.</p>
    <div class="sign">
    <a href='#' class='button'>BUY NOW</a>
    </div>
  </div>
</li>  
</ul>
</div>
</div>
