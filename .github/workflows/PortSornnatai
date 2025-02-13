<!DOCTYPE html>
<html lang="en">
<head>
<style>
    *{
        margin: 0;
        padding: 0;
        font-family: 'Poppins' , sans-serif;
        box-sizing: border-box;
    }
    html{
        scroll-behavior: smooth;
    }
    body{
        background: #a7a7a7;
        color: #636363;
    }
    #header{
        width: 100%;
        height: 100vh;
        background-image: url('images/pho.jpg');
        background-size: cover;
        background-position: center;
    }
    .container{
        padding: 10px 10%;
    }
    .nav{
        display: flex;
        align-items: center;
        justify-content: space-between;
        flex-wrap: wrap;
    }
    
    .pho{
        width: 140px;
    }
    
    .nav ul li{
        display: inline-block;
        list-style: none;
        margin: 10px 20px;
    }
    
    .nav ul li a{
        color: #393939;
        text-decoration: none;
        font-size: 18px;
        position: relative;
    }
    .nav ul li a::after{
        content: '';
        width: 0%;
        height: 3px;
        background-color: #545454;
        position: absolute;
        left: 0;
        bottom: -6px;
        transition: 0.5s;
    }
    .nav ul li a:hover::after{
        width: 100%;
    }
    .header-text{
        margin-top: 15%;
        font-size: 30px;
    }
    .header-text h1{
        font-size: 60px;
        margin-top: 20px;
    }
    .header-text h1 span{
        color: #000000;
    }
    /*---------------about-----------------------*/
    #about{
        padding:  80px 0;
        color: #000000;
    }
    .row{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }
    .about-col-1{
        flex-basis: 35%;
    }
    .about-col-1 img{
        width: 100%;
        border-radius: 15px;
    }
    .about-col-2{
        flex-basis: 60%;
    }
    .sub-title{
        font-size: 60px;
        font-weight: 600;
        color: #000000;
    }
    .tab-titles{
        display: flex;
        margin: 20px 0 40px;
    }
    .tab-links{
        margin-right: 50px;
        font-size: 18px;
        font-weight: 500;
        cursor: pointer;
        position: relative;
    }
    .tab-links::after{
        content: '';
        width: 0;
        height: 3px;
        background: #c10808cf;
        position: absolute;
        left: 0;
        bottom: -8px;
        transition: 0.5s;
    }
    .tab-links.active-link::after{
        width: 50%;
    }
    .tab-contents ul li{
        list-style: none;
        margin: 10px 0;
    }
    .tab-contents ul li span{
        color: #000000;
        font-size: 14px;
    }
    .tab-contents{
        display: none;
    }
    .tab-contents.active-tab{
        display: block;
    }
    /* ------------activities---------- */
    #activities{
        padding: 50px 0;
    }
    .work-list{
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        grid-gap: 40px;
        margin-top: 50px;
    }
    .work{
        border-radius: 10px;
        position: relative;
        overflow: hidden;
    }
    .work img{
        width: 100%;
        border-radius: 10px;
        display: block;
        transition: transform 0.5s;
    }
    .work:hover img{
        transform: scale(1.1);
    }
    /*--------contact----------*/
    .contact-{
        flex-basis: 35%;
    }
    .contact p{
        margin-top: 50px;
    }
    .contact p i{
        color: #000000;
        margin-right: 15px;
        font-size: 25px;
    }
    .social-icons{
        margin-top: 30px;
    }
    .social-icons a{
        text-decoration: none;
        font-size: 30px;
        margin-right: 15px;
        color: #585858;
        display: inline-block;
        transition: transform 0.5s;
    }
    .social-icons a:hover{
        color: #000000;
        transform: center;
    }
    .copyright{
        width: 100%;
        text-align: center;
        padding: 25px 0;
        background: hwb(0 27% 0% / 0.788);
        font-weight: 300;
        margin-top: 20px;
    }
    /*-------------css for small screen--------------------*/
    .nav .fas{
        display: none;
    }
    @media only screen and (max-width: 600px){
        #header{
            background-image: url(images/mm.jpg);
        }
        .header-text{
            margin-top: 100%;
            font-size: 16px;
        }
        .header-text h1{
            font-size: 30px;
        }
        .nav .fas{
            display: block;
            font-size: 25px;
        }
        .nav ul{
            background: #4b4b4b;
            position: fixed;
            top: 0;
            right: -200px;
            width: 200px;
            height: 100vh;
            padding-top: 50px;
            z-index: 2;
            transition: right 0.5s;
        }
        .nav ul li{
            display: block;
            margin: 25px;
        }
        .nav ul .fas{
            position: absolute;
            top: 25px;
            left: 25px;
            cursor: pointer;
        }
        .sub-title{
            font-size: 40px;
        }
        .about-col-1, .about-col-2{
            flex-basis: 100%;
        }
        .about-col-1{
            margin-bottom: 30px;
        }
        .about-col-2{
            font-size: 14px;
        }
        .tab-links{
            font-size: 16px;
            margin-right: 20px;
        }
        .contact-left, .contact-right{
            flex-basis: 100%;
        }
       
    }
</style>
 <!-- Header -->
<header>
    <h1>portfolio</h1>
    </header>
    
    <!-- Navigation -->
    <div class="nav">
    
        <li><a href="#personal record">ประวัติส่วนตัว</a></li>
        <li><a href="#performance/activity">ผลงาน และ กิจกรรม</a></li>
        <li><a href="#certificate">เกียรติบัตร</a></li>
        <li><a href="#Contact">ช่องทางการติดต่อ</a></li>
    </div>
</div>
</div>
<!---------------personal record----------------------->
<div id="personal record">
   <div class="container">
       <div class="row">
        <div class="about-col-1">
            <img src="ppp.jpg">
        </div>
        <div class="about-col-2">
               <h1 class="sub-title">แนะนำตัว</h1>
               <p>ชื่อ สรณฑัยห์ นามสกุล เลี่ยวตระกูล</p>
               <p>ชื่อเล่น พะแพง อายุ 16 ปี</p>
               <p>เกิดวันอังคาร ที่ 26 เดือน กุมภาพันธ์ ปี 2551</p>
               <p>หมู่เลือด บี เชื้อชาติ ไทย สัญชาติ ไทย ศาสนา พุทธ</p>
               <p>งานอดิเรก หยุดโรงเรียนเพื่อนอน ความสามารถพิเศษ วาดรูป</p>
               <div class="tab-titles">
                   <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                   <p class="tab-links" onclick="opentab('experience')">Experience</p>
                   <p class="tab-links"onclick="opentab('education')">Education</p>
                   <p class="tab-links"onclick="opentab('Code')">Code</p>
               </div>
               <div class="tab-contents active-tab" id="skills">
                   <ul>
                       <li><span>Python</span><br>40%</li>
                       <li><span>Html</span><br>70%</li>
                       <li><span>Css</span><br>40%</li>
                       <li><span>C</span><br>80%</li>
                       <li><span>javascript</span><br>40%</li>
                   </ul>
               </div>
               <div class="tab-contents" id="experience">
                   <ul>
                       <li><span>29 เมษายน 2567</span><br>ได้เข้าร่วมกิจกรรมการแข่งวาดภาพในหัวข้อ"กำแพงแห่งความหวัง" ที่ บ้านคามิลเลียนเพื่อเด็กพิการ</li>
                       <li><span>29 เมษายน 2567</span><br>ได้เข้าร่วม WORKSHOP ที่ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี</li>
                       <li><span>25-29 ธันวาคม 2567</span><br>ได้เข้าร่วมค่าย"เพราะครู เพาะคน"ครั้งที่15 ที่ มหาวิทยาลัยศรีนครินทรวิโรฒ</li>
                       <li><span>17 มกราคม 2567</span><br>ได้เข้าร่วมการแข่งขันออกแบบด้วยโปรแกรมคอมพิวเตอร์ ที่ โรงเรียนอัสสัมชัญ (ได้รางวัลรองชนะเลิศอันดับที่2)</li>
                       <li><span>19 มกราคม 2567</span><br>ได้เข้าร่วมเป็น 10 ทีมสุดท้ายของการแข่งขันประกวดแนวคิดนวัตกรรม ที่ มหาวิทยาลัยศรีนครินทรวิโรฒ</li>
                   </ul>
               </div>
               <div class="tab-contents" id="education">
                   <ul>
                       <li><span>2013-2015</span><br>ศึกษาที่โรงเรียนอนุบาลปาณยา</li>
                       <li><span>2016 - 2025</span><br>ศึกษาที่โรงเรียนพระหฤทัยคอนแวนต์</li>
                   </ul>
               </div>
            </div>
            <div class="tab-contents" id="Code">
            <ul>
                    <li><span>code ที่เคยเขียน</span><br><a href="shop.html"This is link..</a></li>
                    <li><span>code ขายของ</span><br><a href="login.html"This is link..</a></li>
                    <li><span>code login</span><br><a href="login.html"This is link..</a></li>
                    <a href="page.html" onclick=" return false ;">ไปยังหน้าอื่น</a>    
                </ul>
            </div>
           </div>
       </div>
   </div>
</div>

<!---------------performance/activity--------------------->

<div id="performance/activity">
   <div class="container">
       <h1 class="sub-title">ผลงาน และ กิจกรรม</h1>
       <div class="work-list">
           <div class="work">
               <img src="2.jpg">
               <div class="layer">
                   <h3>ได้เข้าร่วมกิจกรรมการแข่งวาดภาพในหัวข้อ"กำแพงแห่งความหวัง" ที่ บ้านคามิลเลียนเพื่อเด็กพิการ</h3>
               </div>
           </div>
           <div class="work">
               <img src="4.jpg">
               <h3>ได้เข้าร่วม WORKSHOP ที่ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี</h3>
           </div>
           <div class="work">
               <img src="7.jpg">
               <h3>ได้เข้าร่วม OPEN HOUSE ที่ มหาวิทยาลัยจุฬาลงกรณ์(ภาคอินเตอร์)</h3>
           </div>
           <div class="work">
               <img src="5.jpg">
               <h3>ได้เข้าร่วม OPEN HOUSE ที่ มหาวิทยาลัยศรีนครินทรวิโรฒ</h3>
           </div>
           <div class="work">
               <img src="3.JPG">
               <h3>ได้เข้าร่วมการทำจิตอาสาปลูกป่า หาดทรายเม็ดแรก ของ โรงเรียนพระหฤทัยคอนแวนต์</h3>
           </div>
           <div class="work">
               <img src="8.jpg">
               <h3>ได้เข้าร่วมการทำจิตอาสาทำสื่อการเรียนรู้พวงกุญแจสูตรคูณ</h3>
           </div>
           <div class="work">
               <img src="10.jpg">
               <h3>กิจกรรมกีฬาสี</h3>
           </div>
           <div class="work">
               <img src="11.jpg">
               <h3>ได้เข้าร่วมการทำจิตอาสาดูแลน้องๆที่บ้านพักคามิลเลียน</h3>
           </div>
           <div class="work">
               <img src="12.jpg">
               <h3>ได้เข้าร่วมมหกรรมการศึกษาวิชาการ พัฒนาทักษาวิชาการและกิจกรรมเชิงปฏิบัติการ</h3>
           </div>
           <div class="work">
               <img src="6.jpg">
               <h3>ได้เข้าร่วมค่าย"เพราะครู เพาะคน"ครั้งที่15 ที่ มหาวิทยาลัยศรีนครินทรวิโรฒ</h3>
           </div>
           <div class="work">
               <img src="13.jpg">
               <h3>ได้เข้าร่วมการคิดนวัตกรรมและสิ่งประดิษฐ์ ของ ราชวิทยาลัยจุฬาภรณ์</h3>
           </div>
           <div class="work">
               <img src="1.png">
               <h3>ได้เข้าร่วมการประกวดความคิดสร้างสรรค์ในโครงการ"คิดใหญ่ไปให้สุดราง" ของ สถาบันวิจัยและพัฒนาเทคโนโลยีระบบราง</h3>
           </div>
           <div class="work">
               <img src="14.jpg">
               <h3>ได้เข้าร่วมการแข่งขันออกแบบด้วยโปรแกรมคอมพิวเตอร์ ที่ โรงเรียนอัสสัมชัญ (ได้รางวัลรองชนะเลิศอันดับที่2)</h3>
           </div>
           <div class="work">
               <img src="9.jpg">
               <h3>ได้เข้าร่วมเป็น 10 ทีมสุดท้ายของการแข่งขันประกวดแนวคิดนวัตกรรม ที่ มหาวิทยาลัยศรีนครินทรวิโรฒ</h3>
           </div>
       </div>
   </div>
</div>
</body>
<!---------------certificate-------------------->

<div id="certificate">
   <div class="container">
       <h1 class="sub-title">My Certificates</h1>
       <div class="work-list">
           <div class="work">
               <img src="20.jpg">
           </div>
           <div class="work">
               <img src="21.jpg">
           </div>
           <div class="work">
               <img src="22.jpg">
           </div>
           <div class="work">
               <img src="23.jpg">
           </div>
           <div class="work">
               <img src="24.jpg">
           </div>
           <div class="work">
               <img src="25.jpg">
           </div>
           <div class="work">
               <img src="26.jpg">
           </div>
           <div class="work">
               <img src="27.jpg">
           </div>
           <div class="work">
               <img src="28.jpg">
           </div>
           <div class="work">
               <img src="29.jpg">
           </div>
           <div class="work">
               <img src="30.jpg">
           </div>
           <div class="work">
               <img src="31.jpg">
           </div>
           <div class="work">
               <img src="32.jpg">
           </div>
       </div>
   </div>
</div>

<!---------------contact---------------------->

<div id="Contact">
   <div class="container">
       <div class="row">
           <div class="contact">
               <h1 class="sub-title">ช่องทางการติดต่อ</h1>
               <h3><i class="fas fa-paper-plane"></i>Gmail : sornnataileawtakoon@gmail.com</h3>
               <h3><i class="fas fa-phone-square-alt"></i>เบอร์โทร : 090-5637926</h3>
               <div class="social-icons">
                   <a href="https://www.facebook.com/share/1KjRRyrDTr/?mibextid=wwXIfr" title="facebook icons">Facebook : Sornnatai leawtakoon</a>
                   <a href="https://www.instagram.com/zxer0ai/" title="instagram logo icons">instagram : zxer0ai</a>
                   <a href="https://line.me/ti/p/zjl9Cgbt4n" title="line icons">ID Line : p26022551</a>
               </div>                                             
           </div>
       </div>
   </div>
   <div class="copyright">
       <h3>ขอบคุณค่ะ thank you หวังว่าจะรับรักนะคะ</h3>
   </div>
</div>

<script>

    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
    function opentab(tabname){
       for(tablink of tablinks){
           tablink.classList.remove("active-link");
       }
       for(tabcontent of tabcontents){
           tabcontent.classList.remove("active-tab");
       }
       event.currentTarget.classList.add("active-link");
       document.getElementById(tabname).classList.add("active-tab")
    }

</script>

<script>

   var sidemenu = document.getElementById("sidemenu");

   function openmenu(){
       sidemenu.style.right = "0";
   }
   function closemenu(){
       sidemenu.style.right = "-200px";
   }
</script>
</body>
</html>
