<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
        integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="./copy.css">
</head> 
<style>
    *
{
    margin: 0px;
    padding: 0px;
    
}
.menu
{
    display: flex;
    height: 60px;
    width: 100%;
    /* justify-content: space-around; */
    /* background-color: rgb(41, 131, 101); */

}
.b1 {
    outline: none;
    cursor: pointer;
    border: none;
    padding: 0.9rem 2rem;
    margin: 0;
    font-family: inherit;
    font-size: inherit;
    position: relative;
    display: inline-block;
    letter-spacing: 0.05rem;
    font-weight: 500;
    font-size: 15px;
    border-radius: 500px;
    overflow: hidden;
    background: #386CF0;
    color: #386CF0;
    border: 1px #386CF0 solid;
   }
   .b1 span {
    position: relative;
    z-index: 10;
    transition: color 0.4s;
   }
   .b1:hover span {
    color: rgb(253, 253, 253);
   }
   .b1::before,
   .b1::after {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 0;
   }
   .b1::before {
    content: "";
    background: #ffffff;
    width: 120%;
    left: -10%;
    transform: skew(30deg);
    transition: transform 0.4s cubic-bezier(0.3, 1, 0.8, 1);
   }
   .b1:hover::before {
    transform: translate3d(100%, 0, 0);
   }
 /* ............................1.......................... */
@media (min-width: 320px) and (max-width: 480px) {
    .icon
    {
        width: 62px;
        height: 60px;
    }   
    .menuicon
    {
        margin-top: 10px;
        margin-right: 250px;
        width: 62px;
    }
     .logo
    { 
        width: 100%;
        height: 60px;
        text-align: center;
    }
    .bookimg
    {
        width: 177px;
        height: 40px;
        margin-top: 10px;
        margin-right: 40px;
        text-align: center;

    }
    .other
    {
        display: none;
    }
    .b1
    {
        display: none;
    }
    .bul
    {
        display: none;
    }
    .doci
    {
        width: 100%;
        height: 200px;
    }

}
/* ............................2.......................... */
@media (min-width: 481px) and (max-width: 767px) {
     .icon
    {
        width: 62px;
        height: 60px;
    }   
    .menuicon
    {
        margin-top: 15px;
        margin-left: 10px;
        width: 62px;
    }
     .logo
    { 
        width: 100%;
        height: 60px;   
    }
    .bookimg
    {
        width: 177px;
        height: 40px;
        margin-top: 13px;
        margin-left: 24px;

    }
    .other
    {
        display: none;
    }
    .b1
    {
        display: none;
    }
    .bul
    {
        display: none;
    }
}
/* ............................3.......................... */
@media (min-width: 768px) and (max-width: 1050px) {
    .menu
    {
        height: 80px;
    }
  .icon
    {
        width: 62px;
        height: 60px;
    }   
    .menuicon
    {
        margin-top: 15px;
        margin-left: 10px;
        width: 62px;
    }
    .logo
    { 
        width: 200px;
        height: 60px;   
    }
    .bookimg
    {
        width: 177px;
        height: 40px;
        margin-top: 13px;
        margin-left: 24px;
    }
   .other
   {
    display: none;
   }
   .login
   {
    width: 790px;
    display: flex;
    justify-content: flex-end;
   }
   .b1
   {
    width:220px;
    height: 48px;
    margin-top: 10px;
    margin-right: 17px;
   }
   .bul
    {
        display: none;
    }
}
/* ............................4.......................... */
@media (min-width: 1051px) and (max-width: 1230px)

{
    .icon
    {
        display: none;

    }
  
    .bookimg
    {
        margin-top: 25px;
        width: 160px;
        margin-left: 20px;
        
    }
    .other
    {
        width: 1013px;
        margin-top: 33px; 
        color: #2E3842;
        text-align: end;
        margin-right: 40px;
    }
    .other>:first-child
    {
        color: #027BFF;
    }
    .ss
    {
        font-size: 14px;
        margin-left: 18px;
        font-family: Poppins, sans-serif;
        color: #2E3842;
        font-weight: 580;
        text-decoration: none;
        letter-spacing: 1px;
    }
    .b1
    {
        display: none;
    }
    .bul
    {
        display: none;
    }
}
/* ............................5.......................... */
@media (min-width: 1231px) and (max-width: 1430px) {

    .icon
    {
        display: none;

    }
  
    .bookimg
    {
        margin-top: 25px;
        width: 160px;
        margin-left: 20px;
        
    }
    .other
    {
        width: 930px;
        margin-top: 33px; 
        color: #2E3842;
        text-align: start;
        /* margin-right: 30px; */
        margin-left: 20px;
    }
    .other>:first-child
    {
        color: #027BFF;
    }
    .ss
    {
        font-size: 14px;
        margin-left: 18px;
        font-family: Poppins, sans-serif;
        color: #2E3842;
        font-weight: 580;
        text-decoration: none;
        letter-spacing: 1px;
    }
      .login
   {
    width: 270px;
    display: flex;
    justify-content: flex-end;
    margin-right: 20px;
   }
    .b1
    {
        height: 45px;
        width: 175px;
        padding: 15px;
        text-align: center;
        margin-top: 18px;
        font-size: 15px;
        font-family: Poppins, sans-serif;
        font-weight:500;
    }
    .bul
    {
        display: none;
    }
   
}
/* ............................6.......................... */
@media (min-width: 1431px) {
    .icon
    {
        display: none;

    }
    .bookimg
    {
        margin-top: 25px;
        width: 160px;
        margin-left: 20px;
        
    }
    .other
    {
        width: 980px;
        margin-top: 33px; 
        color: #2E3842;
        text-align: start;
        /* margin-right: 30px; */
        margin-left: 20px;
    }
    .other>:first-child
    {
        color: #027BFF;
    }
    .ss
    {
        font-size: 14px;
        margin-left: 17px;
        font-family: Poppins, sans-serif;
        color: #2E3842;
        font-weight: 580;
        text-decoration: none;
        letter-spacing: 1px;
    }
      .login
   {
    width: 270px;
    display: flex;
    justify-content: flex-end;
    margin-right: 10px;
   }
    .b1
    {
        height: 45px;
        width: 175px;
        padding: 15px;
        text-align: center;
        margin-top: 18px; 
        font-size: 15px;
        font-family: Poppins, sans-serif;
        font-weight:500;
        margin-right: 15px;
    } 
    .bul
    {
        display: flex;
        width: auto;
        /* width: 10px; */
        margin-top: 25px;
        display: flex;
        justify-content: flex-end;
        /* padding-left: 550px; */
        /* margin-right: 20px; */
        margin-left: 40px;
        position: relative;
        left: 10px;
    }
    .hos
    {
        width: 50px;
        height: 27px;
        padding-top: 2px;
        
    }
    .con
    {
        color: #7F7F7F;
        margin-top: -4px;
        color: #7F7F7F;
        font-size: 13px;
        font-family: Poppins, sans-serif;
        font-weight: 400;
    }
    .num
    {   
        margin-top: 20px;
        white-space: pre;
        color: #000000;
        font-size: 14px;
        font-family: Poppins, sans-serif;
        font-weight: 500;
        position: relative;
        right: 42px;
        bottom: 5px;

    }
    #hh
    {
        display: none;
    }
}

</style>
<body>
    <div class="menu">
        <div class="icon">
            <!-- <i class="fa-solid fa-bars" id="menuicon" style="color: #5bcead;" id="logo"></i> -->
            <img src="./img/freepik--20250620084532h9iu.png" class="menuicon" alt="">
        </div>
        <div class="logo">

            <img src="https://www.quickobook.com/assets/img/logo4.png" alt="" class="bookimg">
        </div>
        <div class="other">
            <a href="" class="ss">Home</a>
            <a href="" class="ss">Doctors  <i class="fa-solid fa-chevron-down" style="color: #2e3642;"></i></a>
            <a href="" class="ss">Hospitals</a>
            <a href="" class="ss">Franchisee <i class="fa-solid fa-chevron-down" style="color: #2e3642;"></i></a>
            <a href="" class="ss" id="hh">Health Feed</a>
            <a href="" class="ss">Book Test</a>
            <a href="" class="ss">Surgery</a>
            <a href="" class="ss">Order Medicine</a>
        </div>
        <div class="bul">
            <img src="./img/freepik-untitled-project-20250620140828Xg0p.png" class="hos" alt="">
            <span class="con">Contact</span>
            <span class="num">+91 943 520 0024</span>
        </div>
        <span class="login">
            <button type="submit" class="b1"><span>SIGN IN / SIGNUP</span></button>
        </span>
    </div>
    <div class="main">
        <div class="ih">
            <div class="id1">
                View Doctors, Book an Appointment
            </div>
            <div class="id2">
                Find the best doctors, clinics & hospitals in the city nearest to you.
            </div>
        </div>
        <div class="ii">
            <div class="ii2">
                <div class="imain">
                    <div class="ibox">
                        <i class='fas fa-map-marker-alt'></i>
                        <input class="inn" type="search" placeholder="Search..." name="state" list="state" />
                    </div>
                    <datalist id="state">
                        <option value="Andhra Pradesh">
                        <option value="Arunachal Pradesh">
                        <option value="Assam">
                        <option value="Bihar">
                        <option value="Chhattisgarh">
                        <option value="Goa">
                        <option value="Gujarat">
                        <option value="Haryana">
                        <option value="Himachal Pradesh">
                        <option value="Jharkhand">
                        <option value="Karnataka">
                        <option value="Kerala">
                        <option value="Madhya Pradesh">
                        <option value="Maharashtra">
                        <option value="Manipur">
                        <option value="Meghalaya">
                        <option value="Mizoram">
                        <option value="Nagaland">
                        <option value="Odisha">
                        <option value="Punjab">
                        <option value="Rajasthan">
                        <option value="Sikkim">
                        <option value="Tamil Nadu">
                        <option value="Telangana">
                        <option value="Tripura">
                        <option value="Uttar Pradesh">
                        <option value="Uttarakhand">
                        <option value="West Bengal">
                    </datalist>
                    <span class="is">Select Locatioc</span>
                </div>
            </div>
            <div class="maininput">
                <div class="i2">
                    <div class="i3">
                        <i class="fa-solid fa-magnifying-glass" style="color: #A3A3A3;"></i>
                    </div>
                    <input class="i4" type="search" placeholder="Search Doctors,Clinics,Specialization,Symptom Etc" />
                </div>
                <span class="like">Like : Diabetologist etc</span>
            </div>
            <div class="but">
                <i class="fa-solid fa-magnifying-glass"><span class="se">SEARCH</span></i>
            </div>
        </div>
    </div>

    <div class="ll">
        <p class="l1">Largest Healthcare Network Across East India</p>
        <p class="l2">Find best doctors across specialities or hospitals in your city.</p>
    </div>
    <div class="bap">
        <div class="im1">
            <div class="de1">
                <img src="./img/woman-taking-notes-laboratory.jpg" class="img1" alt="">
                <div class="kai">
                    <p class="bo1">Book Lab Test</p>
                    <p class="co1">It's fast, easy and secure</p>
                    <div class="ct  "><button class="do1">Find Diagnostic Center</button></div>
                    <div class="badhu">
                        <i class="fa-solid fa-tags" style="color: #ff0000;"></i>
                        <p class="eo1"> Get Upto 25% OFF On Lab Test</p>
                    </div>
                </div>
            </div>
            <div class="de2">
                <img src="./img/appointment.jpg" class="img1" alt="">
                <div class="kai">
                    <p class="bo2">Book Appointment</p>
                    <p class="co2">For hospital & clinical admissions.</p>
                    <div class="contener"><button class="do2">Find Doctors Now</button></div>
                </div>
            </div>
        </div>
        <div class="im2">
            <div class="de3">
                <img src="./img/high-angle-medical-desk-composition.jpg " class="img1" alt="">
                <div class="kai">
                    <p class="bo3">Buy Medicine</p>
                    <p class="co3">We got all your health needs covered!</p>
                    <div class="ct"><button class="do3">Buy Now</button></div>
                    <div class="badhu">
                        <i class="fa-solid fa-tags" style="color: #ff0000;"></i>
                        <p class="eo1">Get Upto 25% OFF On Medicines</p>
                    </div>
                </div>
            </div>
            <div class="de4">
                <img src="./img/female-asian-doctor-nurse-ppe-personal-protective-equipment-from-coronavirus-standing-ready-confident-white-background.jpg"
                    class="img1" alt="">
                <div class="kai">
                    <p class="bo4">Surgery Assistance</p>
                    <p class="co4">For best and affordable Surgical Treatment.</p>
                    <div class="ct"><button class="do4">Consult Now</button></div>
                    <div class="badhu">
                        <i class="fa-solid fa-tags" style="color: #ff0000;"></i>
                        <p class="eo1">Get Upto 15% Savings</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="dady">
        <p class="a1">Discover the Online Appointment!</p>
        <p class="a2">A step-by-step guide to build an on-demand appointment for patients</p>
        <div iv class="dady2">
            <div class="box1" id="boxi1">
                <span class="fix">
                </span>
                <span class="kk1">
                    <p class="a3">Find a Doctor</p>
                    <p class="a4" id="aaa">With more than 1000+ doctors and on mission to provide best care Health Care
                        Service
                    </p>
                </span>
            </div>

            <div class="box1" id="boxi2">
                <span class="fix" id="fixed">
                </span>
                <span class="kk1">
                    <p class="a3">View Doctor</p>
                    <p class="a4" id="aa4">Share your health and we shall assign you a top doctor across the North
                        East</p>
                </span>
            </div>

            <div class="box1" id="boxi3">
                <span class="kk1">
                    <p class="a3">Book a visit</p>
                    <p class="a4">Book your time slot with doctor from your comfort zone</p>
                </span>

            </div>

        </div>
        <div id="headingbuttondiv">
            <button id="headingbutton">
                <a href="#">Find Doctor</a>
                <i class="fa-solid fa-arrow-right"></i>
            </button>
        </div>
    </div>


    <!-- ...............................00............................ -->

    <div class="Specialities">
        <div class="Specialitiesi">
            <h2>Clinic and Specialities</h2>
            <p>Find experienced doctors across all specialties</p>
        </div>
        <div class="Specialitiesii">
            <div class="Specialitiesii1">
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-01.png"
                            alt="Urology" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" class="ar" />
                        </svg>
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Urology</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-02.png"
                            alt="Neurology" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Neurology</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-03.png"
                            alt="Orthopedic" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>

                    </div>
                    <p class="Specialitiesdiviipispani2">Orthopedic</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-04.png"
                            alt="Cardiologist" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2" id="Specialitiesdiviipispani21">Cardiologist</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-05.png"
                            alt="Dentist" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2" id="Specialitiesdiviipispani22">Dentist</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-06.png"
                            alt="Consultant Physician" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Consultant Physician</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/general_physician.png"
                            alt="General Physician" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">General Physician</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-01.png"
                            alt="Urology" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Urology</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-02.png"
                            alt="Neurology" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Neurology</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-03.png"
                            alt="Orthopedic" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Orthopedic</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-04.png"
                            alt="Cardiologist" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Cardiologist</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-05.png"
                            alt="Dentist" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Dentist</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/specialities-06.png"
                            alt="Consultant Physician" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">Consultant Physician</p>
                </div>
                <div class="Specialitiesdiviipi">
                    <div class="Specialitiesdiviipispani1">
                        <img src="https://www.quickobook.com/assets/img/specialities/general_physician.png"
                            alt="General Physician" />
                        <svg height="25" width="25" xmlns="http://www.w3.org/2000/svg">
                            <circle r="8" cx="12.5" cy="12.5" fill="#027BFF" />
                        </svg>
                    </div>
                    <p class="Specialitiesdiviipispani2">General Physician</p>
                </div>
            </div>
            <div class="carousel-dots" id="carouselDots">
                <span class="dot active"></span>
                <span class="dot"></span>
                <span class="dot"></span>
                <span class="dot"></span>
                <span class="dot"></span>
                <span class="dot"></span>
                <span class="dot"></span>
            </div>
        </div>
    </div>



    <!-- ...............................video.......................... -->

  <div class="video">
        <div class="videomain">
            <div class="videomaini">
                <div class="videomaini1">
                    <div class="videomaini1row">
                        <div class="videomaini1row2">
                            <img src="https://www.quickobook.com/assets/img/video_prev.jpg" alt="Video Preview" />
                            <a href="#"><i class="fa-solid fa-play"></i></a>
                        </div>
                        <div class="videomaini1row1">
                            <span>Manage your health care</span>
                            <p>Know about <span>Quickobook</span> health services</p>
                            <div id="headingbuttondiv1">
                                <button id="headingbutton1">
                                    <a href="#">See More </a>
                                    <i class="fa-solid fa-arrow-right"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

<!-- ................................. ad ......................................... -->
 <div class="avu">
    <div class="s1">
        <p class="j1" id="jj1">Get all your medicines.</p>
        <p class="j1" id="jj2">Everytime. On time.</p>
        <p class="m1" id="mm1">Guaranteed availability</p>
        <p class="m1" id="mm2">Home delivery in 24hrs</p>
        <button type="submit" class="as">Order Medicins</button>
    </div>
    <div class="s2">
        <img src="https://www.quickobook.com/assets/img/order.svg" class="ss2  bhau ba eoisea bhani i" alt="">
    </div>
 </div>


<!-- ................................. sharp ......................................... -->


<div class="health-banner">
        <div class="banner-container">
            <div class="banner-left">
                <h1>
                    Get <span class="highlight-text">Every Single</span> Updates Here.
                </h1>
            </div>
            <div class="banner-right">
                <p>
                    Online Health Information Library is for general people, patients, their families and friends who seek information on disease, procedure and certain medications.
                </p>
            </div>
        </div>
    </div>
<!-- ................................. Templet ......................................... -->

<div class="footer">
        <div class="footer-container">
            <div class="footer-content">
                <!-- Company Info -->
                <div class="footer-section company-info">
                    <div class="logo">
                        <img src="https://www.quickobook.com/assets/img/logo4.png" class="ka" alt="">

                    </div>
                    <p class="company-description">
                        QuickoBook is a registered start up company empaneled with 10000+ Doctors, 500+ Hospitals, lives touched of more than 2 Million patients.
                    </p>
                    <div class="social-icons">
                        <a href="#" aria-label="Facebook">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" aria-label="Twitter">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" aria-label="LinkedIn">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                        <a href="#" aria-label="Instagram">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" aria-label="YouTube">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>

                <!-- For Information -->
                <div class="footer-section">
                    <h3>For Information</h3>
                    <ul>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Booking Guide</a></li>
                        <li><a href="#">Pharmacy</a></li>
                        <li><a href="#">Careers</a></li>
                        <li><a href="#">Press Release</a></li>
                        <li><a href="#">FAQ's</a></li>
                    </ul>
                </div>

                <!-- Helpful Links -->
                <div class="footer-section">
                    <h3>Helpful Links</h3>
                    <ul>
                        <li><a href="#">Book Appointment</a></li>
                        <li><a href="#">Search for doctors</a></li>
                        <li><a href="#">Search for hospitals</a></li>
                        <li><a href="#">Book Lab/Diagnostics</a></li>
                        <li><a href="#">Franchisee Register</a></li>
                        <li><a href="#">SMS Booking</a></li>
                        <li><a href="#">Services</a></li>
                    </ul>
                </div>

                <!-- Contact Us -->
                <div class="footer-section contact-info">
                    <h3>Contact Us</h3>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div class="contact-text">
                            QWKPRO CONSULTANCY PVT LTD,<br>
                            Silchar, Assam
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div class="contact-text">+91 943 520 0024</div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div class="contact-text">
                            <div class="contact-label">Customer Support :</div>
                            support@quickobook.com
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div class="contact-text">
                            <div class="contact-label">Official Queries :</div>
                            info@quickobook.com
                        </div>
                    </div>
                </div>
            </div>

            <!-- Footer Bottom -->
            <div class="footer-bottom">
                <div class="copyright">
                    © 2024 Quickobook. All rights reserved.
                </div>
                <div class="footer-links">
                    <a href="#">Terms and Conditions</a>
                    <span>|</span>
                    <a href="#">Privacy Policy</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        const carousel = document.querySelector('.Specialitiesii1');
        const dots = document.querySelectorAll('.carousel-dots .dot');

        const scrollToIndex = (index) => {
            const scrollWidth = carousel.scrollWidth - carousel.clientWidth;
            const totalDots = dots.length;
            const scrollLeft = (scrollWidth / (totalDots - 1)) * index;

            carousel.scrollTo({
                left: scrollLeft,
                behavior: 'smooth'
            });
        };
        carousel.addEventListener('scroll', () => {
            const scrollLeft = carousel.scrollLeft;
            const scrollWidth = carousel.scrollWidth - carousel.clientWidth;
            const totalDots = dots.length;

            const index = Math.round((scrollLeft / scrollWidth) * (totalDots - 1));

            dots.forEach((dot, i) => {
                dot.classList.toggle('active', i === index);
            });
        });
        dots.forEach((dot, index) => {
            dot.addEventListener('click', () => {
                scrollToIndex(index);
            });
        });


        document.querySelector('.fa-map-marker-alt').addEventListener('click', function () {
          document.querySelector('.inn').focus();
        });
        const input = document.querySelector('.inn');
        const span = document.querySelector('.is');
      
        input.addEventListener('input', function () {
          span.textContent = input.value ? `Selected: ${input.value}` : 'Select Location';
        });
    </script>
</body>

</html>
