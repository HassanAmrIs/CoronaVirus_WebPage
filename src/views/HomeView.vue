<template>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/all.min.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg bg-white fixed-top">
      <div class="container item mx-auto">
        <a class="logo" href="#">C<img src="imgs/TitleIcon.png" style="height: 2vh;">VID<span>19</span></a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item me-2">
              <a class="nav-link" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item me-2">
              <a class="nav-link" href="#about">About Corona</a>
            </li>
            <li class="nav-item me-2">
              <a class="nav-link" href="#symptoms">Symptoms</a>
            </li>
            <li class="nav-item me-2">
              <a class="nav-link" href="#prevention">Prevention</a>
            </li>
            <li class="nav-item me-2">
              <a class="nav-link" href="#treatment">Treatment</a>
            </li>
            <li class="nav-item me-2">
              <a class="nav-link" href="#faq">FAQ</a>
            </li>
            <li class="nav-item me-2">
              <a class="nav-link" href="#news">News</a>
            </li>
            <li class="nav-item">
              <button>
                <a class="nav-link" href="#do&don't">Do & Don't</a>
              </button>
            </li>
          </ul>
        </div>
      </div>
  </nav>
    
    <!-- Header -->
    <header id="home" class="w-100">
      <div class="padding w-75 mx-auto">
      <div class="row ">
        <!-- content -->
        <div class="col-lg-6 col-sm-12  ">
          <!-- header -->
          <div class="box mb-3">
            <div><h1><span>CORONA</span></h1></div>
            <div class="line_height ">
              <p>COVID-19</p>
              <p><span>VIRUS</span></p>
            </div>
          </div>
          <!-- paragraph -->
          <div>
            <p>The Coronavirus (COVID-19) was first reported in Wuhen, Hubei China in December 2019, the outbreak was later recognized as a pandemic by the World Health Organization (WHO) on 1 March 2020</p>
          </div>
          <!-- buttons -->
          <div>
            <div class="row mt-5 mb-3 pt-3">
              <div class="col-6">
                <button><a href="#prevention" style="text-decoration: none; color: white;">How To Protect 
                  <i class="fa-solid fa-shield-halved"></i>
                </a>
                </button>
              </div>
              <div class="col-6">
                <a href="#about">About COVID-19
                  <i class="fa-solid fa-arrow-right"></i>
                </a>
              </div>
            </div>
          </div>
          <!-- num -->
          <div class="row mt-4">
            <div class="col-lg-5 col-sm-5">
              <p class="desc">WORLDWIDE CASE</p>
              <span class="num">8,949,671</span>
            </div>
            <div class="col-lg-3 col-sm-5">
              <p class="desc">DEATHS</p>
              <span class="num">467,432</span>
            </div>
            <div class="col-lg-4 col-sm-12">
              <p class="desc">RECOVERD</p>
              <span class="num">4,556,091</span>
            </div>
          </div>
        </div>
        <!-- photo -->
        <div class="col-lg-6 col-sm-12 mx-auto">
          <img src="imgs/header-a.png" alt="">
        </div>
        <div class="pt-5">
          <p class="desc"> Last updated jan 21, 2020, 09:24 AM America Chicago</p>
        </div>
      </div>
      </div>
    </header>

    <!-- section1 -->
    <section class="section1 w-100 pb-5" id="about">
      <div class="row w-75 mx-auto">
        <div class="col-lg-7 col-sm-12 ps-0 ">
          <h4 class="head">ABOUT THE DISEASE</h4>
          <h1 class="mb-3 topic">CORONAVIRUS (COVID-19)</h1>
          <p><span id="embededPara">COVID-19 is a new illness that can affect your lungs and airways.</span>
            It's caused by a virus called coronavirus. It was discovered in December 2019 in Wuhan, Hubei, China.
          </p>
          <p class="pd-2 pt-2">Common sign of infection include respiratory symptoms, fever, cough, shortness of breath
            and breathing difficulties In more severe case, infection can cause pneumonia, Severe acute respiratory
            syndrome, kidney failure and even death.
          </p>
          <p>
            Standard recommendations to prevent infection spread include regular hand washing,
            covering mouth and nose when coughing and sneezing, thoroughly cooking meat and eggs.
            Avoid cplse contact with anyone showing symptoms of respiratory illness such as coughing and sneezing.
          </p>

        </div>
        <div class="col-lg-4 col-sm-12 mx-auto">
          <table>
            <tr>
              <td><p>What you need to Know</p></td>
            </tr>
            <tr>
              <td>
                <a href="#spread">How coronavirus is spread <i class="fa-solid fa-arrow-right"></i></a>
                
              </td>
            </tr>
            <tr>
              <td>
                <a href="#symptoms">Symptoms of coronavirus <i class="fa-solid fa-arrow-right"></i></a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="#protect">How to protect yourself <i class="fa-solid fa-arrow-right"></i></a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="#treatment">Treatment for coronavirus <i class="fa-solid fa-arrow-right"></i></a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="#news">Myth-Busters of coronavirus <i class="fa-solid fa-arrow-right"></i></a>
              </td>
            </tr>
            <tr>
              <td>
                <a href="#faq">Questins & answers <i class="fa-solid fa-arrow-right "></i></a>
              </td>
            </tr>
          </table>
        </div>
      </div>
    </section>

    <!-- section2 -->
    <section class="section2 w-100" id="spread">
      <div class="w-75 mx-auto">
        <div class="mt-5 mb-5 w-75 mx-auto text-center">
          <h4 class="head">HOW CORONAVIRUS IS SPREAD</h4>
          <h4 class="topic">TRANSMISSION OF COVID-19</h4>
          <p>Because it's a new illness, we do not know exactly how coronavirus spreads from person to person, Similar viruses are spread in caugh droplets.</p>
        </div>
        <div class="row w mx-auto">
          <div class="col-lg-4 col-sm-12">
            <div class="box">
              <img src="imgs/spread-a.png" alt="">
              <div class="pt-2">
                <h4 class="head">Person-to-person spread as close contact with infectd</h4>
                <p class="pb-2">The coronavirus is though to spread mainly from person to person. This can happen between people who are in close contact with one another</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-12">
            <div class="box">
              <img src="imgs/spread-b.png" alt="">
              <div class="pt-2">
                <h4 class="head">Touching or contact with infected surfaces or objects</h4>
                <p class="pb-2">A person can get COVID-19 by touching a suface or object that has the virus on it and then touching their own mouth, nose, or possibly their eyes.</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-sm-12">
            <div class="box">
              <img src="imgs/spread-c.png" alt="">
              <div class="pt-2">
                <h4 class="head">Droplets that from infected person coughs or sneezes</h4>
                <p class="pb-2">The coronavirus is though to spread mainly from person to person. This can happen between people who are in close contact with one another.</p>
              </div>
            </div>
          </div>
         </div>
        <div class="mx-auto box_emb">
          <button class="button"><i class="fa-solid fa-circle-question pe-2"></i><a href="#faq" style="color: white; text-decoration:none">Have question about spreading?</a></button>
        </div>
      </div>
    </section>
   
    <!-- section3 -->
    <section class="section3 w-100 pt-5 pb-5" id="symptoms">
      <div class="w-75 mx-auto text-center pt-5">
        <h4 class="head">WHAT ARE THE SYMPTOMS OF COVID-19</h4>
        <h1 class="topic">SYMPTOMS OF CORONAVIRUS</h1>
        <div class="w-75 mx-auto text-center">
          <p>The most common symptoms of COVID-19 are fever, tiredness, and dry cough. Some patients may have aches and pains, nasal congestion, runny nose, sore throat or diarhea, These symptoms are 
            usually mild and begin gradually, Also the symptoms may appear 2-14 days after exposure.
          </p>
      </div>
      </div>

      <div class="w-75 row mx-auto mt-5 mb-5">
        <div class="col-lg-4 col-sm-12">
          <div class="image">
            <img src="imgs/symptom-a.png" alt="" class="me-0">
          </div>
          <div class="box">
            <h4 class="head">Fever</h4>
            <p><b>High Fever</b> - this means you feel hot to touch on your
            chest or back (you do not need to measure your temperature). It's a 
            common sign and also appear in 2-10 days if you affected
            </p>
          </div>
        </div>

        <div class="col-lg-4 col-sm-12">
          <div class="image">
            <img src="imgs/symptom-b.png" alt="" class="me-0">
          </div>
          <div class="box">
            <h4 class="head">Cough</h4>
            <p><b>Continuous cough</b> - this means coughing a lot for more than an
              hour, or 3 or more coughing episodes in 24 hours (if you usually have a cough, it may be worse than usual).
            </p>
          </div>
        </div>

        <div class="col-lg-4 col-sm-12">
          <div class="image">
            <img src="imgs/symptom-c.png" alt="" class="me-0">
          </div>
          <div class="box">
            <h4 class="head">Shortness of breath</h4>
            <p><b>Difficulty breathing</b> - Around 1 out of every 6 people who gets COVID-19 
              becomes seriously ill and develops difficulty breathing or shortness of breath.
            </p>
          </div>
        </div>
      </div>

      <div class="w-75 row mx-auto pt-5">
        <div class="col-lg-8 col-sm-12">
        
          <div class="d-flex boxnote">
            <i class="fa-solid fa-triangle-exclamation icon"></i>
            <div> 
              <h4 class="head d-inline">Stay at home and call your doctor: </h4> 
              <i> if you think you have been exposed to COVID-19 and 
              develop a fever and any symptoms, such as cough or difficulity breathing, call your healthcare provider as soon 
              possible for medical advice.</i>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-sm-12">
          <button class="button mt-4"><a href="#faq">Have question? Find answer</a></button>
        </div>
      </div>

    </section>

    <!-- section4 -->
    <section class="section4 w-100 pb-3" id="prevention">
      <div class="w-75 mx-auto text-center">
        <h4 class="head">HOW TO PROTECT YOURSELF?</h4>
        <h1 class="topic">PREVENTION & ADVICE</h1>
        <p>There is currently no vaccine to prevent coronavirus disease 2019(COVID-19). <b>The best way
          to prevent illness is to avoid being exposed to this virus.</b>
        Stay aware of the latest information on the COVID-19 outbreak. available on the WHO website and 
        through your national and local public health authority
        </p>
      </div>
      <div class="row w-75 mx-auto pt-5">
        <div class="col-lg-3 col-sm-6">
          <img src="imgs/advice-a.png" class="d-block mx-auto" alt="">
          <b>Wash your hands frequently</b>
          <p>Regularly and thoroughly clean your hands with an
            alcohol-based hand rub or wash them with soap and 
            water for at least 20 seconds.
          </p>
        </div>

        <div class="col-lg-3 col-sm-6">
          <img src="imgs/advice-b.png" class="d-block mx-auto" alt="">
          <b>Maintain social distancing</b>
          <p>Maintain at least 1 metre (3feet) distance between 
            yourself 7 anyone who is coughing or sneezing. if you are
            too close, get chance to infected.
          </p>
        </div>

        <div class="col-lg-3 col-sm-6">
          <img src="imgs/advice-c.png" class="d-block mx-auto" alt="">
          <b>Avoid touching face</b>
          <p>Hands touch many surfaces and can pick up viruses. So,
            hands can transfer the virus to your eyes, nose or mouth 
            and can make you sick.
          </p>
        </div>
        <div class="col-lg-3 col-sm-6">
          <img src="imgs/advice-d.png" class="d-block mx-auto" alt="">
          <b>Practice respiratory hygiene</b>
          <p>Maintain good respiratory hygiene as covering your mouth & nose
            with your bent elbow or tissue when cough or sneeze.
          </p>
        </div>

      </div>

      <div class="row mx-auto wash">
        <div class="col-lg-6 col-sm-12 pb-5">
          <button class="button"><a href="#wash">Check how you wash hand</a></button>
        </div>
        <div class="col-lg-6 col-sm-12">
          <a href="#faq" class="head">Q&A on Coronavirus <i class="fa-solid fa-arrow-right ps-2"></i></a>
        </div>
      </div>
    </section>

    <!-- section5 -->
    <section class="section5 w-100" id="protect">
      <div class="w-75 mx-auto">
        <div class="row box">
          <div class="col-lg-8 col-sm-12">
            <h1 class="topic">Take steps to protect others</h1>
            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Stay home if you're sick </b>
              - Stay home if you are sick, except to get medical care.
            </p>

            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Cover your mouth and nose </b>
              - with a tissue when you cough or sneeze (throw used tissues in the trash) or 
              use the inside of your elbow.
            </p>

            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Wear a facemask if you are </b>
              - You should wear a facemask when you are around other people (e.g. sharing a room or vehicle)
              and before you enter a healthcare provider's
            </p>

            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Clean AND disinfect frequently touched surfaces daily</b>
              - This includes phones, tables, light switches, doorknobs, countertops, handles, desks, toilets,
              faucets, and sinks.
            </p>

            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Clean the dirty surfaces </b>
              - Use detergent or soap and water prior to disinfection.
            </p>

            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Stay informed about the local COVID-19 situation </b>
              - Get up-to-date information about local COVID-19 activity form 
              <a style="color: rgb(75, 170, 253)"> public health officials</a>
            </p>

            <p>
              <i class="fa-solid fa-circle-check pe-2" style="color: rgb(11, 209, 11);"></i>
              <b class="topic fs-6"> Dedicated, lined trash can</b>
              - If possible, dedicate a lined trash can for the ill person. Use gloves when removing
              garbage bags, and handling & disposing of trash.
            </p>
            
          </div>
          <div class="col-lg-4 col-sm-12">
            <img src="imgs/steps.png" alt="">
          </div>
        </div>
      </div>
    </section>

    <!-- section6 -->
    <section class="section6 w-100 pt-5" id="wash">
      <div class="text-center pt-5">
        <h1 class="topic">Follow steps to wash hands</h1>
        <h4>
        <a href="#prevention" style="text-decoration: none" class="head">Why do I need to wash hand 
          <i class="fa-solid fa-arrow-right pe-3" ></i>
        </a>
        </h4>
      </div>

      <div class="row mx-auto p_box">
        <div class=" col-lg-2 col-sm-6 box mx-auto text-center">
          <img src="imgs/hand-a.png" alt="">
          <b>Soap on Hand</b>
        </div>

        <div class="col-lg-2 col-sm-6 box  mx-auto text-center">
          <img src="imgs/hand-b.png" alt="">
          <b>Plam on Plam</b>
        </div>

        <div class="col-lg-2 col-sm-6 box mx-auto text-center">
          <img src="imgs/hand-c.png" alt="">
          <b>Between Fingers</b>
        </div>

        <div class="col-lg-2 col-sm-6 box mx-auto text-center">
          <img src="imgs/hand-d.png" alt="">
          <b>Back to Hands</b>
        </div>

        <div class="col-lg-2 col-sm-4 box mx-auto text-center">
          <img src="imgs/hand-e.png" alt="">
          <b>Celaln with Water</b>
        </div>

        <div class="col-lg-2 col-sm-6 box mx-auto text-center">
          <img src="imgs/hand-f.png" alt="">
          <b>Focus on Wrist</b>
        </div>
      </div>


    </section>

    <!-- section7 -->
    <section class="section7 w-100 pt-5 pb-5" id="treatment">
      <div class="row w-75 mx-auto">
        <div class="col-lg-7 col-sm-12">
          <h4 class="head">BE CAREFULL & STAY SAFE</h4>
          <h1> TREATMENT FOR CORONAVIRUS</h1>
          <b>To date, there is no vaccine and no specific antiviral medicine to prevent or treat COVID-19.</b>
          <p>However, those affected should receive care to relieve symptoms. People with serious illness should be hospitalized. Most patients recover thanks to supportive care.</p>
          <p>Antibiotics do not help, as they do not work against viruses. Treatment aims to relieve the symptoms while your 
            body fights the illness. You'll need to stay in isolation, away form other people, until you have recovered.
          </p>
        </div>
        <div class="col-lg-5 col-sm-12">
          <div class="box">
            <b>Self Care</b>
            <p>If you have mid symptoms, stay at home until you've recovered. You can 
              retrive your symptoms if you:
              <p> <i class="fa-solid fa-arrow-right pe-2"></i> Rest and sleep</p>
              <p> <i class="fa-solid fa-arrow-right pe-2"></i> Keep warm</p>
              <p> <i class="fa-solid fa-arrow-right pe-2"></i> Drink plenty of liquids</p>
              <p> <i class="fa-solid fa-arrow-right pe-2"></i> Use a room humidifer or take a hot shower to help ease a sora throat and cough</p>
            </p>
            <b>Medical Treatments</b>
            <p>If you develop a fever, cough, and hvae difficulty breathing, prompltly seek medical care. Call in advance and tell your health
              provider of any recent travel or recent contact with travelers.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- section8 -->
    <section class="section8 w-100  mb-5" id="faq">
      <div class="text-center">
        <h4 class="head">FREQUENTLY ASKED QUESTIONS</h4>
        <h1 class="topic">COMMON QUESTION & ANSWER</h1>
      </div>
      <div class="mt-5 faq mx-auto">
        <div class="nav flex-column nav-pills me-3 fb" id="v-pills-tab" role="tablist" aria-orientation="vertical">
          <button class="nav-link active mx-auto" id="v-pills-one-tab" data-bs-toggle="pill" data-bs-target="#v-pills-one" type="button" role="tab" aria-controls="v-pills-one" aria-selected="true">Coronavirus Disease 2019 Basic</button>
          <button class="nav-link mx-auto" id="v-pills-two-tab" data-bs-toggle="pill" data-bs-target="#v-pills-two" type="button" role="tab" aria-controls="v-pills-two" aria-selected="false">How It Spreads</button>
          <button class="nav-link mx-auto" id="v-pills-three-tab" data-bs-toggle="pill" data-bs-target="#v-pills-three" type="button" role="tab" aria-controls="v-pills-three" aria-selected="false">How to Protect Yourself</button>
          <button class="nav-link mx-auto" id="v-pills-four-tab" data-bs-toggle="pill" data-bs-target="#v-pills-four" type="button" role="tab" aria-controls="v-pills-four" aria-selected="false">Symptoms & Testing</button>
          <button class="nav-link mx-auto" id="v-pills-five-tab" data-bs-toggle="pill" data-bs-target="#v-pills-five" type="button" role="tab" aria-controls="v-pills-five" aria-selected="false">Outbreak in Your Community</button>
          <button class="nav-link mx-auto" id="v-pills-six-tab" data-bs-toggle="pill" data-bs-target="#v-pills-six" type="button" role="tab" aria-controls="v-pills-six" aria-selected="false">Myth-Busters of coronavirus</button>
        </div>
        <div class="tab-content " id="v-pills-tabContent">
          <div class="tab-pane show active" id="v-pills-one" role="tabpanel" aria-labelledby="v-pills-one-tab">
            <table>
              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">What is a novel coronavirus? <span v-if="readMore"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore" class="pt-0 pb-0">
                      <p class="d-block">
                      On February 11, 2020 the World Health Organization announced an official name for the disease that is causing 
                      the 2019 novel coronavirus outbreak, first identified in Wuhan China. The new name of this disease is coronavirus disease 2019, 
                      abbreviated as COVID-19. in COVID-19, 'CO' stands for 'corona', 'VI' for 'virus' and 'D' for disease. Formely, this diseases was referred to as '2019 novel 
                      coronavirus' or "2019-nCov".
                      </p>
                      <p class="pt-0">
                        A novel coronavirus is a new coronavirus that has not been previously identified. The virus causing coronavirus 
                        disease 2019 (COVID-19), is not the same as the coronaviruses that commonly circulate among humans
                        and cause mild illness, like the common cold.
                      </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore =! readMore">
                    <span v-if="readMore">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Why is the disease being called coronavirus disesase 2019, COVID-19? <span v-if="readMore1"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore1" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore1 =! readMore1">
                    <span v-if="readMore1">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">How can people help stop stigma related to COVID-19 <span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore2" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore2 =! readMore2">
                    <span v-if="readMore2">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Why might someone blame or avoid individuals and groups? <span v-if="readMore3"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore3" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore3 =! readMore3">
                    <span v-if="readMore3">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              
             
            </table>
          </div>

          <div class="tab-pane " id="v-pills-two" role="tabpanel" aria-labelledby="v-pills-two-tab">
            <table>
              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">What is the source of the virus? <span v-if="readMore"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio incidunt obcaecati eveniet laboriosam, fugiat maiores aperiam quod neque est veritatis minima provident ut enim voluptatibus possimus dolorem mollitia nam! Harum blanditiis voluptatibus impedit nisi placeat aliquid, eos delectus facere accusantium possimus maxime itaque? Tenetur nemo error exercitationem similique quo, ipsum omnis, quos optio beatae sequi commodi quasi expedita unde doloremque?
                      </p>
                      <p class="pt-0">
                      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod temporibus ab commodi itaque, harum consequatur!
                      </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore =! readMore">
                    <span v-if="readMore">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">How does the virus spread? <span v-if="readMore1"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore1" class="pt-0 pb-0">
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    </p>
                
                  </div>

                  <button class="show" @click="readMore1 =! readMore1">
                    <span v-if="readMore1">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Can someone who has had COVID-19 spread the illness to others? <span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore2" class="pt-0 pb-0">
                      <p class="d-block">
                        <ul>
                          <li>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</li>
                          <li>Lorem ipsum dolor sit amet consectetur.</li>
                          <li>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Enim cumque quis libero id voluptatum consequuntur, eaque ut sapiente dolorum? Repellendus ipsum ullam labore eum excepturi alias harum nulla praesentium aliquid.</li>
                        </ul>
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore2 =! readMore2">
                    <span v-if="readMore2">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Will warm weather stop the outbreak of COVID-19<span v-if="readMore4"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore4" class="pt-0 pb-0">
                    
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                  </div>

                  <button class="show" @click="readMore4 =! readMore4">
                    <span v-if="readMore4">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Can the virus that causes COVID-19 be spread through food including refrigerated or frozen food?<span v-if="readMore3"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore3" class="pt-0 pb-0">
                    
                      Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium animi nemo expedita id vitae, earum natus. Placeat inventore eius magnam. Rem minus veniam similique voluptas recusandae id voluptatibus inventore excepturi.
                    </p>
                  </div>

                  <button class="show" @click="readMore3 =! readMore3">
                    <span v-if="readMore3">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">What is community spread?<span v-if="readMore5"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore5" class="pt-0 pb-0">
                      Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    </p>
                  </div>

                  <button class="show" @click="readMore5 =! readMore5">
                    <span v-if="readMore5">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>
              
             
            </table>
          </div>

          <div class="tab-pane " id="v-pills-three" role="tabpanel" aria-labelledby="v-pills-three-tab">
            <div class="tab-pane show active" id="v-pills-one" role="tabpanel" aria-labelledby="v-pills-one-tab">
              <table>
                <tr>
                  <div class="d-flex justify-content-between">
                    <div class="pb-3">
                      <p class="head pb-0 mb-0">
                        what can i do to protect myself and prevent the spread of disease? <span v-if="readMore"></span>
                        <span v-else>...</span>
                      </p>
  
                      <p v-show="readMore" class="pt-0 pb-0">
                       <ul>
                        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, deleniti. Magni, dolor possimus quis perspiciatis aliquid ipsam iure cumque suscipit.</li>
                        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia beatae mollitia iusto esse? Ad dolores quae repellat sit!</li>
                        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab sed nesciunt cupiditate unde! Mollitia vel recusandae non dignissimos.</li>
                        <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Optio tempore, ratione corporis laboriosam debitis molestiae corrupti aspernatur odit ex voluptatem.</li>
                       </ul>
                    
                      </p>
                    </div>
  
                    <button class="show" @click="readMore =! readMore">
                      <span v-if="readMore">
                        <i class="fa-solid fa-minus fs-4"></i>
                      </span>
                      <span v-else>
                        <i class="fa-regular fa-plus fs-4"></i>
                      </span>
                    </button>
                </div>
  
                </tr>
  
                <tr>
                  <div class="d-flex justify-content-between">
                    <div class="pb-3">
                      <p class="head pb-0 mb-0">What should i do if i had close contact with someone who has COVID-19?<span v-if="readMore1"></span>
                        <span v-else>...</span>
                      </p>
  
                      <p v-show="readMore1" class="pt-0 pb-0">
                        <p class="d-block">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                      </p>
                      <p class="pt-0">
                        <ul>
                          <li>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</li>
                          <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, quaerat!</li>
                          <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde, necessitatibus?</li>
                        </ul>
                      </p>
                      </p>
                    </div>
  
                    <button class="show" @click="readMore1 =! readMore1">
                      <span v-if="readMore1">
                        <i class="fa-solid fa-minus fs-4"></i>
                      </span>
                      <span v-else>
                        <i class="fa-regular fa-plus fs-4"></i>
                      </span>
                    </button>
                </div>
  
                </tr>
  
                <tr>
                  <div class="d-flex justify-content-between">
                    <div class="pb-3">
                      <p class="head pb-0 mb-0">Who is at higher risk for serious illness from COVID-19?<span v-if="readMore2"></span>
                        <span v-else>...</span>
                      </p>
  
                      <p v-show="readMore2" class="pt-0 pb-0">
                        <p class="d-block">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                      </p>
                      <p class="pt-0">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                      </p>
                      </p>
                    </div>
  
                    <button class="show" @click="readMore2 =! readMore2">
                      <span v-if="readMore2">
                        <i class="fa-solid fa-minus fs-4"></i>
                      </span>
                      <span v-else>
                        <i class="fa-regular fa-plus fs-4"></i>
                      </span>
                    </button>
                </div>
  
                </tr>
  
                <tr>
                  <div class="d-flex justify-content-between">
                    <div class="pb-3">
                      <p class="head pb-0 mb-0">What should people at higher risk of serious illness with COVID-19 do?<span v-if="readMore3"></span>
                        <span v-else>...</span>
                      </p>
  
                      <p v-show="readMore3" class="pt-0 pb-0">
                        <p class="d-block">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                      </p>
                      <p class="pt-0">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                      </p>
                      </p>
                    </div>
  
                    <button class="show" @click="readMore3 =! readMore3">
                      <span v-if="readMore3">
                        <i class="fa-solid fa-minus fs-4"></i>
                      </span>
                      <span v-else>
                        <i class="fa-regular fa-plus fs-4"></i>
                      </span>
                    </button>
                </div>
  
                </tr>
  
                <tr>
                  <div class="d-flex justify-content-between">
                    <div class="pb-3">
                      <p class="head pb-0 mb-0">Should i wear a mask to protect myself?<span v-if="readMore2"></span>
                        <span v-else>...</span>
                      </p>
  
                      <p v-show="readMore4" class="pt-0 pb-0">
                        <p class="d-block">
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                      </p>
                      <p class="pt-0">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                      </p>
                      </p>
                    </div>
  
                    <button class="show" @click="readMore4 =! readMore4">
                      <span v-if="readMore4">
                        <i class="fa-solid fa-minus fs-4"></i>
                      </span>
                      <span v-else>
                        <i class="fa-regular fa-plus fs-4"></i>
                      </span>
                    </button>
                </div>
  
                </tr>
               
              </table>
            </div>
          </div>

          <div class="tab-pane " id="v-pills-four" role="tabpanel" aria-labelledby="v-pills-four-tab">
            <table>
              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">
                      What are the symptoms of COVID-19? <span v-if="readMore"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore" class="pt-0 pb-0">
                     <ul>
                      <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, deleniti. Magni, dolor possimus quis perspiciatis aliquid ipsam iure cumque suscipit.</li>
                      <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia beatae mollitia iusto esse? Ad dolores quae repellat sit!</li>
                      <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab sed nesciunt cupiditate unde! Mollitia vel recusandae non dignissimos.</li>
                      <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Optio tempore, ratione corporis laboriosam debitis molestiae corrupti aspernatur odit ex voluptatem.</li>
                     </ul>
                  
                    </p>
                  </div>

                  <button class="show" @click="readMore =! readMore">
                    <span v-if="readMore">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Should i be tested for COVID-19?<span v-if="readMore1"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore1" class="pt-0 pb-0">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
              
                  </div>

                  <button class="show" @click="readMore1 =! readMore1">
                    <span v-if="readMore1">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Where can i get tested for COVID-19?<span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore2" class="pt-0 pb-0">
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quisquam corporis consequatur ad sapiente, iste molestias sint praesentium, similique, a eius mollitia facilis ut necessitatibus voluptates amet delectus numquam. Consequuntur, dolore.
                      
                    </p>
                   
                   
                  </div>

                  <button class="show" @click="readMore2 =! readMore2">
                    <span v-if="readMore2">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Can a person test negative and later test positive for COVID-19?<span v-if="readMore3"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore3" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore3 =! readMore3">
                    <span v-if="readMore3">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Should i wear a mask to protect myself?<span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore4" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore4 =! readMore4">
                    <span v-if="readMore4">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>
             
            </table>
          </div>

          <div class="tab-pane " id="v-pills-five" role="tabpanel" aria-labelledby="v-pills-five-tab">
            <table>
              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">
                      What should id so if there is an outbreak in my community? <span v-if="readMore"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore" class="pt-0 pb-0">
                      <p class="d-block">
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit.

                    </p>
                    <p class="head">Protect yourself and others.</p>
                    <p>
                      <ul>
                        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
                        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
                        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
                        <li>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</li>
                      </ul>
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore =! readMore">
                    <span v-if="readMore">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">How do i prepare my children in case of COVID-19 outbreak in our community?<span v-if="readMore1"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore1" class="pt-0 pb-0">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
              
                  </div>

                  <button class="show" @click="readMore1 =! readMore1">
                    <span v-if="readMore1">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">what steps should parents take to protect children during a community outbreak?<span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore2" class="pt-0 pb-0">
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quisquam corporis consequatur ad sapiente, iste molestias sint praesentium, similique, a eius mollitia facilis ut necessitatibus voluptates amet delectus numquam. Consequuntur, dolore.
                      
                    </p>
                   
                   
                  </div>

                  <button class="show" @click="readMore2 =! readMore2">
                    <span v-if="readMore2">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Will schools be dismissed if there is an outbreak in my community?<span v-if="readMore3"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore3" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore3 =! readMore3">
                    <span v-if="readMore3">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Can virus that cause COVID-19 be spread through food, including refrigerated or frozen food?<span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore4" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore4 =! readMore4">
                    <span v-if="readMore4">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Should i go to work if there is an outbreak in my community? <span v-if="readMore5"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore5" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore5 =! readMore5">
                    <span v-if="readMore5">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>
             
            </table>
          </div>

          <div class="tab-pane " id="v-pills-six" role="tabpanel" aria-labelledby="v-pills-six-tab">
            <table>
              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">
                      COVID-19 virus can be transmitted in areas with hot and humid climates? <span v-if="readMore"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore" class="pt-0 pb-0">
                      
                      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore, facilis? Tempore dignissimos facilis voluptates fugit! Enim maxime totam suscipit molestiae et. Libero, sit amet autem consequatur fugit eius at fuga!

                    </p>
                    
                  </div>

                  <button class="show" @click="readMore =! readMore">
                    <span v-if="readMore">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Cold weather and snow CANNOT kill the new coronavirus<span v-if="readMore1"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore1" class="pt-0 pb-0">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
              
                  </div>

                  <button class="show" @click="readMore1 =! readMore1">
                    <span v-if="readMore1">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Taking a hot bath does not prevent the new coronavirus disease<span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore2" class="pt-0 pb-0">
                     Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quisquam corporis consequatur ad sapiente, iste molestias sint praesentium, similique, a eius mollitia facilis ut necessitatibus voluptates amet delectus numquam. Consequuntur, dolore.
                      
                    </p>
                   
                   
                  </div>

                  <button class="show" @click="readMore2 =! readMore2">
                    <span v-if="readMore2">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">The new coronavirus CANNOT be transmitted through mosquito bities.<span v-if="readMore3"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore3" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore3 =! readMore3">
                    <span v-if="readMore3">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>

              <tr>
                <div class="d-flex justify-content-between">
                  <div class="pb-3">
                    <p class="head pb-0 mb-0">Are hand dryers effective in killing the new coronavirus?<span v-if="readMore2"></span>
                      <span v-else>...</span>
                    </p>

                    <p v-show="readMore4" class="pt-0 pb-0">
                      <p class="d-block">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nulla veniam magnam aut numquam quaerat quae obcaecati ratione qui? Nam similique veritatis fugiat tempore ducimus odit reprehenderit deserunt quaerat deleniti accusamus.
                    </p>
                    <p class="pt-0">
                      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis nulla delectus repudiandae quod iusto eligendi velit, facere amet corrupti, atque, aperiam quam reprehenderit necessitatibus fugiat? Asperiores reiciendis libero vero modi.
                    </p>
                    </p>
                  </div>

                  <button class="show" @click="readMore4 =! readMore4">
                    <span v-if="readMore4">
                      <i class="fa-solid fa-minus fs-4"></i>
                    </span>
                    <span v-else>
                      <i class="fa-regular fa-plus fs-4"></i>
                    </span>
                  </button>
              </div>

              </tr>
             
            </table>
          </div>
        </div>
      </div>
    </section>

    <!-- section9 -->
    <section class="section9 w-100" id="do&don't">
      <div class="w-75 mx-auto">
        <div class="text-center pb-5">
          <h4 class="head">DO'S & DON'TS</h4>
          <h1 class="topic">PROTECT YOURELF</h1>
          <p>The best thing you can do now is plan for how you can adapt your daily routine. Take few steps to protect yourself as Clean your hands
            often, Avoid close contact, Cover coughs and sneezes, clean daily used surfaces etc. The best way to avoid being exposed to this virus.
          </p>
        </div>
      </div>
        <div class="row pt-5 w-75 mx-auto">
          <div class="col-lg-3 col-sm-12 box pb-5">
            <div class="emb_box">
              <p class="head">Avoid close conact</p>
              <img src="imgs/donts-a.png" alt="">
            </div>
            <div class="emb_box">
              <p class="head">Don't Touch Face</p>
              <img src="imgs/donts-b.png" alt="">
            </div>
            <div class="emb_box">
              <p class="head">Social Distancing</p>
              <img src="imgs/donts-c.png" alt="">
            </div>
          </div>

          <div class="col-lg-6 pb-5 col-sm-12 box2">
            <img src="imgs/protect.png" alt="">
          </div>

          <div class="col-lg-3  col-sm-12 box3  pb-5">
            <div class="emb_box">
              <img src="imgs/dos-a.png" alt="">
              <p class="head">Wash Your Hands</p>
            </div>
            <div class="emb_box">
              <img src="imgs/dos-b.png" alt="">
              <p class="head">Drink Much Water</p>
            </div>
            <div class="emb_box">
              <img src="imgs/dos-c.png" alt="">
              <p class="head">Use Face Mask</p>
            </div>
          </div>
      </div>
    </section>

    <!-- section10 -->
    <section class="section10 " id="news">
      <div class="text-center pb-5 ">
        <h4 class="head">RECENT FROM BLOG</h4>
        <h1 class="topic">LATEST UPDATE</h1>
      </div>
      <div class="row  mx-auto pb-5 mainbox">
        <div class="col-lg-3 col-sm-12 mt-3 mb-3 box">
          <img src="imgs/blog-a.jpg" class="pb-2" alt="">
          <h6 class="topic fs-5"> Caring for someone at home</h6>
          <p>Most people get sick with COVID-19 will have only mid illness
            and should recover at home. Care at home can help stop the spread of 
            COVID-19
          </p>
        </div>

        <div class="col-lg-3 col-sm-12 box">
          <img src="imgs/blog-b.jpg" class="pb-2" alt="">
          <h6 class="topic fs-5"> 15 ways to keep safe and healthy</h6>
          <p>Most people get sick with COVID-19 will have only mid illness
            and should recover at home. Care at home can help stop the spread of 
            COVID-19
          </p>
        </div>

        <div class="col-lg-3 col-sm-12 mt-3 mb-3 box">
          <img src="imgs/blog-c.jpg" class="pb-2" alt="">
          <h6 class="topic fs-5"> If You Think You Are Sick</h6>
          <p> If you are sick with COVID-19 or think you might have it. follow the steps below
            to help protect other people in your home and community
          </p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="w-75 mx-auto">
        <div class="pt-5">
          <a class="logo2" href="#home">C<i class="fa-solid fa-virus" style="color: rgb(207, 13, 13);"></i>VID<span>19</span></a>
          <div class="line_height">
          <p>This website is for health information and advice about Coronavirus (COVID-19), how to prevent and protect yourself from disease.</p>
          <p>Learn about the government response to coronavirus on GOV.UK</p>
          </div>
        </div>

        <div class="row pt-3 w-60 mx-auto">
          <div class="col-lg-4 col-sm-12 pt-2">
            <button class="find facebook">Find US on Facebook</button>
            </div>

          <div class="w col-lg-4 col-sm-12 pt-2">
            <button class="find twitter">Find Us on Twitter</button>
          </div>
          <div class="col-lg-4 col-sm-12 pt-2">
          <button class="find insta">Find Us on Instagram</button>
        </div>
        </div>
        <div class="row pt-5 pb-5">
          <div class="col-lg-4 col-sm-12">
            <h4>QUICK LINK</h4>
            <a href="#about">About Corona</a><br>
            <a href="#symptoms">Symptoms</a><br>
            <a href="#prevention">Prevention</a><br>
            <a href="#protect">Protect Yourself</a><br>
            <a href="#faqs">FAQs</a><br>

          </div>
          <div class="col-lg-4 col-sm-12">
            <h4>HELPFULL LINK</h4>
            <a href="#">Healthcare Professionals</a><br>
            <a href="#">Healthcare Facilities</a><br>
            <a href="#">Older Adults & Medical Conditions</a><br>
            <a href="#">Repare your Family</a><br>
          </div>
          <div class="col-lg-4 col-sm-12">
            <h4>IMPORTANT LINK</h4>
            <a href="#">WHO Website</a><br>
            <a href="#">CDC Website</a><br>
            <a href="#">NHS Website</a><br>
            <a href="#">Harvard Health</a><br>
          </div>
        </div>

        <hr>
        <div class="copyrights ">
          <div class="d-flex justify-content-between">
            <div><p>2021 COVID-19 Teplate Made by Amany Abdelfatah</p></div>
            <div>
              <p>Privacy Policy</p>
            </div>
          </div>
          <div class="pb-5">
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolore nemo, qui iste error harum porro? Quasi molestiae dignissimos odit facilis est porro enim voluptate eaque eius, atque consectetur provident tempora?</p>
          </div>
        </div>
      </div>
    </footer>

    <!-- Scrollup -->
    
      
      <div id="pagetop" class="fixed scrollup" v-show="scY > 300" @click="toTop">
        <i class="fa-solid fa-arrow-up scrollup"></i>
      </div>
    

</template>

<script>
  export default{
    data() {
      return {
        scTimer: 0,
        scY: 0,
        readMore: false,
        readMore1: false,
        readMore2: false,
        readMore3: false,
        readMore4: false,
        readMore5: false,
        readMore6: false,
      }
    },
    mounted() {
      window.addEventListener('scroll', this.handleScroll);
    },
    methods: {
      handleScroll: function () {
        if (this.scTimer) return;
        this.scTimer = setTimeout(() => {
          this.scY = window.scrollY;
          clearTimeout(this.scTimer);
          this.scTimer = 0;
        }, 100);
      },
      toTop: function () {
        window.scrollTo({
          top: 0,
          behavior: "smooth"
        });
      },
    },
  }
</script>