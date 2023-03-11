---
id: home
blueprint: pages
title: 'Kupferpreise | Kupfer Ankauf | Abholung Service'
template: home
author: c44ed6c5-a8f8-4447-85a2-a86c40027ed0
title_1: Gruezi!
title_2: 'Wir machen die tagesaktuellen Kupferpreise und Offerte f&uuml;r Altkupfer'
button_text: 'Jetzt starten'
small_image:
  - kupfer-millberry_450-1677106222.jpg
  - kupferblech-1677099677.jpg
  - kupferkabel_450-1677106265.jpg
updated_by: c44ed6c5-a8f8-4447-85a2-a86c40027ed0
updated_at: 1678483602
story_heading: Offerte
story_title: 'Holen Sie sich eine unverbindliche Offerte für Altmetall entsorgen ein, indem Sie das nachfolgende Formular ausfüllen und an uns senden.'
my_image:
  - kupfer-1-1677197085.jpg
my_story_text: |-
  <h3><b>So get`s</b></h3>
  <b>Altmetall wählen</b><br>
  Wenn Sie Ihr Altmetall in der Liste nicht finden, wählen sie die Option "nach Beschreibung" und in Feld "Kommentar" schreiben Sie uns noch eine Nachricht. Wir können ein individuelles Angebot für Ihr Schrott erstellen.<br>
  <b>Menge wählen</b>
  Das Menge soll ungefähr in Kilo eingegeben werden. Wenn Sie nicht die richtige Menge angegeben haben, ist kein Problem.
  Vor Ort wird das genaue Gewicht mit unsere Waage ermittelt.<br>
  <b>Transport wählen</b><br>
  Sie können zwischen zwei Transporten für Ihr Altmetall wählen:<br>
  1. Abholung - Paletten mit SBB-Rahmen, Box oder lose Ladung (Fahrzeug ist mit Hebebühne ausgerüstet)<br>
  2. selbst Anlieferung
textarea_field: |-
  <section class="hero d-flex justify-content-center align-items-center" id="section_1">
                  <div class="container">
                      <div class="row">

                          <div class="col-lg-7 col-12">
                              <div class="hero-text">
                                  <div class="hero-title-wrap d-flex align-items-center mb-4">
  	                                
  	                                {{ assets:small_image }}
  									<img src="{{url}}" class="avatar-image avatar-image-large img-fluid" alt="">
  									{{ /assets:small_image }}
  	                                
                                      

                                      <h1 class="hero-title ms-3 mb-0">{{title_1}}</h1>
                                  </div>

                                  <h2 class="mb-4">{{title_2}}</h2>
                                  <p class="mb-4"><a class="custom-btn btn custom-link" href="#section_2">{{button_text}}</a></p>
                              </div>
                          </div>

                          <div class="col-lg-5 col-12 position-relative">
  	                       
                              <div class="hero-image-wrap"></div>
                               {{ assets:big_image }}
                              <img src="{{url}}" class="hero-image img-fluid" alt="">
                              {{ /assets:big_image }}
                          </div>

                      </div>
                  </div>

                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#535da1" fill-opacity="1" d="M0,160L24,160C48,160,96,160,144,138.7C192,117,240,75,288,64C336,53,384,75,432,106.7C480,139,528,181,576,208C624,235,672,245,720,240C768,235,816,213,864,186.7C912,160,960,128,1008,133.3C1056,139,1104,181,1152,202.7C1200,224,1248,224,1296,197.3C1344,171,1392,117,1416,90.7L1440,64L1440,0L1416,0C1392,0,1344,0,1296,0C1248,0,1200,0,1152,0C1104,0,1056,0,1008,0C960,0,912,0,864,0C816,0,768,0,720,0C672,0,624,0,576,0C528,0,480,0,432,0C384,0,336,0,288,0C240,0,192,0,144,0C96,0,48,0,24,0L0,0Z"></path></svg>
              </section>
story_section_antlr: |-
  <section class="about section-padding" id="section_2">
                  <div class="container">
                      <div class="row">

                         <!-- <div class="col-12">
  	                        
  	                        
  	                        {{ assets:story_big_image }}
                              <img src="{{url}}" class="about-image img-fluid" alt="">
                              {{ /assets:story_big_image }}
                          </div> -->

                          <div class="col-12 mx-auto">
                              <div class="section-title-wrap d-flex justify-content-center align-items-center mb-5">
                                      <h2 class="text-white me-4 mb-0">{{story_heading}}</h2>
                                       {{ assets:my_image }}

                                      <img src="{{url}}" class="avatar-image img-fluid" alt="">
                                       {{ /assets:my_image }}
                                  </div>
  </div>
                                  <p class="pt-2 mb-3">{{story_title}}</p>

  <!-- OFFERTEFORMULAR -->
  <div class="col-lg-6 col-12 mt-5 mt-lg-0">
  	<h6>Offerte für Altmetall</h6>                            
  	                         
  	                        
  	                                                   
    <div class="row">
  	                          
  <!--webbot BOT="GeneratedScript" PREVIEW=" " startspan --><script Language="JavaScript" Type="text/javascript"><!--
  function FrontPage_Form1_Validator(theForm)
  {

    if (theForm.metallschrott.selectedIndex < 0)
    {
      alert("Please select one of the \"Bitte Kupferart auewaehlen!\" Option.");
      theForm.metallschrott.focus();
      return (false);
    }

    if (theForm.metallschrott.selectedIndex == 0)
    {
      alert("The first \"Bitte Kupferart auewaehlen!\" Option ist keine gueltige Auswahl. Bitte waehlen Sie eine der anderen Optionen.");
      theForm.metallschrott.focus();
      return (false);
    }
   if (theForm.menge.selectedIndex < 0)
    {
      alert("Please select one of the \"Bitte Menge auewaehlen!\" Option.");
      theForm.menge.focus();
      return (false);
    }

    if (theForm.menge.selectedIndex == 0)
    {
      alert("The first \"Bitte Menge auewaehlen!\" Option ist keine gueltige Auswahl. Bitte waehlen Sie eine der anderen Optionen.");
      theForm.menge.focus();
      return (false);
    }
    return (true);
  }
  //--></script><!--webbot BOT="GeneratedScript" endspan -->
  <form action="https://www.livuss.ch/cgi-bin/offerte-direkt/mailer.cgi" method="post" enctype="multipart/form-data" onreset="return resetit(this)" onsubmit="return FrontPage_Form1_Validator(this)" language="JavaScript" name="FrontPage_Form1">
  <input type="hidden" name="action" value="send">
  <input type="hidden" name="nextsite" value="1">
  <input type="hidden" name="subject" value="Offerte(Slieder)">
  <input type="hidden" name="fertig" value="offerteformular-direkt.html">
  <input type="hidden" name="info" value="livuss.ch/index.php/slieder">
  								                           
                            
  	                    	                            
  <!-- metallschrott -->	                                
  	                                       
  <div class="col-lg-10 col-md-10 col-12">
        <!--webbot bot="Validation" S-Display-Name="Bitte Kupferart auewählen!" B-Value-Required="TRUE" B-Disallow-First-Item="TRUE" -->
      <select size="1" class="form-control" id="" name="metallschrott">
      <option selected value="check">Kupferart ausw&auml;hlen!</option>
      <option value="Millberry">Kupfer, blank I, Millberry</option>
      <option value="Elektrolyt ECU">Elektrilyt, blank (ECU)</option>
      <option value="Kupfer neu">Kupferblech, blank II</option>
      <option value="Oberleitungsdrath">Kupfer-Oberleitungsdraht</option>
      <option value="Kupfer-98%">Kupfer 98%, Berry</option>
      <option value="Sammelkupfer-95%">Sammelkupfer 95%</option>
      <option value="Kupfer-verzinnt/vernickelt">Kupfer Ni/Si/Sn</option>
      <option value="Kupfer-lackiert">Kupferdrath lackiert/Trafo</option>
      <option value="Kupferspaene">Kupfersp&auml;ne sauber</option>
      <option value="Kupfergranulat-1B">Kupfergranulat IB</option>
      <option value="Kupfergranulat-2">Kupfergranulat II</option>
      <option value="Kupfergranulat-3">Kupfergranulat III</option>
      <option value="---">---------------------</option>
      <option value="Kupferkabel-<40%">Kupferkabel < 40%</option>
      <option value="Kupferkabel-40-44%">Kupferkabel 40-44%</option>
      <option value="Kupferkabel-45-49%">Kupferkabel 45-49%</option>
      <option value="Kupferkabel-50-54%">Kupferkabel 50-54%</option>
      <option value="Kupferkabel-55-59%">Kupferkabel 55-59%</option>
      <option value="Kupferkabel-60-64%">Kupferkabel 60-64%0</option>
      <option value="Kupferkabel-65-69%">Kupferkabel 65-69%</option>
      <option value="Kupferkabel-70-74%">Kupferkabel 70-74%</option>
      <option value="Kupferkabel-75-80%">Kupferkabel 75-80%</option>
      <option value="---">---------------------</option>
      <option value="Beschreibung">nach Beschreibung</option>
      </select>
       <label for="floatingInput">Metallart</label>
    </div>
                                          
     <!-- ende metallschrott -->
     <!-- menge -->	                           	                           
  	<div class="col-lg-10 col-md-10 col-12">
         <!--webbot bot="Validation" S-Display-Name="Bitte Menge auewählen!" B-Value-Required="TRUE" B-Disallow-First-Item="TRUE" -->
        <select size="1" class="form-control"  name="menge">
        <option selected value="check">Menge ausw&auml;hlen!</option>
        <option value="50-100kg">50 - 100 kg</option>
        <option value="100-200kg">101 - 200 kg</option>
        <option value="200-300kg">201 - 300 kg</option>
        <option value="300-400kg">301 - 400 kg</option>
        <option value="400-500kg">400 - 500 kg</option>
        <option value="500-1000kg">501 - 1000 kg</option>
        <option value="> 1000kg">mehr als 1000 kg</option>
        <option value="---">---------------</option>
        <option value="Beschreibung">nach Beschreibung</option>
        </select>
        <label for="floatingInput">Menge</label>
      </div>
                                        
   <!-- ende menge-->   
      
      <div class="col-lg-10 col-md-10 col-12">
        <input type="hidden" class="hidden" name="">
        <button type="submit" class="form-control" style="background: #D77924;
        border-radius: var(--border-radius-large);font-size:120%;
        color: var(--white-color);
        font-weight: var(--font-weight-bold);
        transition: all 0.5s;
        margin-bottom: 0;    padding-top: 13px;
        padding-bottom: 13px; ">Weiter</button>
      </div>
                               
                               
  	</form>                           
    </div>
    <!-- ENDE OFFERTEFORMULAR -->



    <div class="col-lg-6 col-12 mt-5 mt-lg-0">
      <p>{{my_story_text}}</p>
    </div>
                      
        </div>
    </div>
</section>
hero_section_antlr: |-
  <section class="hero d-flex justify-content-center align-items-center" id="section_1">
                  <div class="container">
                      <div class="row">

                          <div class="col-lg-7 col-12">
                              <div class="hero-text">
                                  <div class="hero-title-wrap d-flex align-items-center mb-4">
  	                                
  	                                {{ assets:small_image }}
  									<img src="{{url}}" class="avatar-image avatar-image-large img-fluid" alt="">
  									{{ /assets:small_image }}
  	                                
                                      

                                      <h1 class="hero-title ms-3 mb-0">{{title_1}}</h1>
                                  </div>

                                  <h2 class="mb-4">{{title_2}}</h2>
                                  <p class="mb-4"><a class="custom-btn btn custom-link" href="#section_2">{{button_text}}</a></p>
                              </div>
                          </div>

                          <div class="col-lg-5 col-12 position-relative">
  	                       
                              <div class="hero-image-wrap"></div>
                               {{ assets:big_image }}
                              <img src="{{url}}" class="hero-image img-fluid" alt="">
                              {{ /assets:big_image }}
                          </div>

                      </div>
                  </div>

                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#535da1" fill-opacity="1" d="M0,160L24,160C48,160,96,160,144,138.7C192,117,240,75,288,64C336,53,384,75,432,106.7C480,139,528,181,576,208C624,235,672,245,720,240C768,235,816,213,864,186.7C912,160,960,128,1008,133.3C1056,139,1104,181,1152,202.7C1200,224,1248,224,1296,197.3C1344,171,1392,117,1416,90.7L1440,64L1440,0L1416,0C1392,0,1344,0,1296,0C1248,0,1200,0,1152,0C1104,0,1056,0,1008,0C960,0,912,0,864,0C816,0,768,0,720,0C672,0,624,0,576,0C528,0,480,0,432,0C384,0,336,0,288,0C240,0,192,0,144,0C96,0,48,0,24,0L0,0Z"></path></svg>
              </section>
infotitle: Information
name: 'Livuss GmbH'
birth_day: '2001-01-01'
phone: CHE-284.291.761
email: Schweiz
experience: 10+
customers: 1000+
projects: 10+
awards: 10+
information_section_template: |-
  <section class="featured section-padding">
                  <div class="container">
                      <div class="row">
  <h2>{{firmainfo_titel}}</h2>
  <h3>{{firmainfo_text}}</h3>
                          <div class="col-lg-6 col-12">
                              <div class="profile-thumb">
                                  <div class="profile-title">
                                      <h4 class="mb-0">{{infotitle}}</h4>
                                  </div>

                                  <div class="profile-body">
                                      <p>
                                          <span class="profile-small-title">Firma</span> 
                                          <span>{{name}}</span>
                                      </p>

                                      <p>
                                          <span class="profile-small-title">Website</span> 
                                          <span><a href="https:livuss.ch" title="Schrottplatz | Altmetall entsorgen" target="_blank">livuss.ch</a></span>
                                      </p>

                                      <p>
                                          <span class="profile-small-title">MwSt</span> 
                                           <span><a href="tel: {{phone}}">{{phone}}</a></span>
                                      </p>

                                      <p>
                                          <span class="profile-small-title">Markt</span> 
                                          <span><a href="mailto:{{email}}">{{email}}</a></span>
                                      </p>
                                  </div>
                              </div>
                          </div>

                          <div class="col-lg-6 col-12 mt-5 mt-lg-0">
                              <div class="about-thumb">
                                  <div class="row">
                                      <div class="col-lg-6 col-6 featured-border-bottom py-2">
                                          <strong class="featured-numbers">{{experience}}</strong>

                                          <p class="featured-text">Jahre in Metallhandel</p>
                                      </div>

                                      <div class="col-lg-6 col-6 featured-border-start featured-border-bottom ps-5 py-2">
                                          <strong class="featured-numbers">{{customers}}</strong>

                                          <p class="featured-text">Zufriedene Kunden</p>
                                      </div>

                                      <div class="col-lg-6 col-6 pt-4">
                                          <strong class="featured-numbers">{{projects}}</strong>

                                          <p class="featured-text">Projekte</p>
                                      </div>

                                      <div class="col-lg-6 col-6 featured-border-start ps-5 pt-4">
                                          <strong class="featured-numbers">{{awards}}</strong>

                                          <p class="featured-text">Grosskunden</p>
                                      </div>
                                  </div>
                              </div>
                          </div>

                      </div>
                  </div>
              </section>
company_logos:
  -
    id: ZZrVoQCd
    company_logo:
      - kupfer-millberry-1677262642.jpg
    compani_metalle_text: 'Kupfer Millberry'
    company_metalle_text: 'Kupfer Millberry'
  -
    id: leixq1me
    company_logo:
      - millberry-kupfer.jpg
    company_metalle_text: 'Mellberry verzinnt'
  -
    id: MUYT7ihd
    company_logo:
      - kupferblech-1677262796.jpg
    company_metalle_text: 'Kupfer neu'
  -
    id: mGwvz891
    company_logo:
      - kupfer-granulat-1677262889.jpg
    company_metalle_text: Kupfergranulat
  -
    id: DucnXeEH
    company_logo:
      - kupfer-elektrolyt.jpg
    company_metalle_text: Elektrolyt
  -
    id: leiv6prn
    company_logo:
      - altkupfer-entsorgen.jpg
    company_metalle_text: 'Kupfer 98%'
  -
    id: vZBdI6Wg
    company_logo:
      - altkupfer-1677262405.jpg
    company_metalle_text: 'Kupfer 95%'
  -
    id: leivcjoa
    company_logo:
      - kupferkabel-1677267368.jpg
    company_metalle_text: 'Kabel Einleter'
  -
    id: leixyoiq
    company_logo:
      - kupferkabel-klein-1677267910.jpg
    company_metalle_text: 'Kabel 70%'
  -
    id: leixp93j
    company_logo:
      - kupferkabel-mix-1677267411.jpg
    company_metalle_text: 'Kabel 60%'
  -
    id: leixt4nr
    company_logo:
      - kabel-entsorgen.jpg
    company_metalle_text: 'Kabel 50%'
  -
    id: leixueuu
    company_logo:
      - 20191031_105912.jpg
    company_metalle_text: 'Kabel 45%'
companies_worked_section: |-
  <section class="clients section-padding">
                  <div class="container">
                      <div class="row align-items-center">

                          <div class="col-lg-12 col-12">
                              <h3 class="text-center mb-5">{{company_section_title}}</h3>
                          </div>
                          <h5>{{company_metalle_text}}</h5>
                          {{company_logos}}
  						{{assets:company_logo}}
                          <div class="col-lg-2 col-4 ms-auto clients-item-height">
                              <img src="{{url}}" class="clients-image img-fluid" alt="{{company_metalle_text}}">
  <p class="center">{{company_metalle_text}}</p>
                          </div>
                          {{/assets:company_logo}}

                          {{/company_logos}}
                           <div class="col-lg-12 col-12"><p>{{company_text_area}}</p></div>

                      </div>
                  </div>
              </section>
section_title: Metalle
service_template_section: |-
  <!-- METALLE -->
  <section class="services section-padding" id="section_3">
                  <div class="container">
                      <div class="row">

                          <div class="col-12 mx-auto">
                              <div class="section-title-wrap d-flex justify-content-center align-items-center mb-5">
  	                         <h2 class="text-white me-4 mb-0">{{section_title}}</h2>
                               {{assets:section_image}}
                                  <img src="{{url}}" class="avatar-image img-fluid" alt="{{section_title}}">
                                 {{/assets:section_image}}

                                  
                              </div>
  							
                              <div class="row pt-lg-5">
  	                            {{services_offered}}
                                  <div class="col-lg-6 col-12">
                                      <div class="services-thumb">
                                          <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
                                              <h3 class="mb-0" title="{{service_title}}">{{service_title}}</h3>


                                              <!-- <div class="services-price-wrap ms-auto">
                                                  <p class="services-price-text mb-0">{{service_price}}</p>
                                                  <div class="services-price-overlay">
  {{assets:metalle_foto}}
  <img src="{{assets:metalle_foto}}" class="projects-image img-fluid" alt=""></div>
                                              </div> -->
                                          </div>

                                          <p>{{service_text}}</p>

                                          <a href="{{service_link}}" class="custom-btn custom-border-btn btn mt-3" title="{{service_text}}">{{link_text}}</a>

                                          <div class="services-icon-wrap d-flex justify-content-center align-items-center">



                                              <!--<i class="services-icon bi-{{service_icon}}"></i>-->
                                          </div>
                                      </div>
                                  </div>
  								{{/services_offered}}
                                  
                              </div>
                          </div>
                      </div>
   <div class="container">
  <div class="row">
  <p>{{metalle_text}}</p>

  </div>
  </div>
   </section>
  <!-- ENDE METALLE -->
section_image:
  - kupfer-recycling-1677155304.jpg
services_offered:
  -
    id: LygAzrUt
    service_title: 'Kupfer Millberry'
    service_price: '$2,400'
    service_text: 'Kupfer Millberry bezeichnet man saubere Kupferdrähte mit einem Durchmesser von mindestens 1 mm. Der Draht muss frei von Schmutz oder Rückstände sein.'
    service_link: 'https://livuss.ch/kupfer-millberry/'
    link_text: 'Millberry Kupfer'
    service_icon: globe
    metalle_foto:
      - kupfer-millberry-1678479132.jpg
  -
    id: 6rAugZJG
    service_title: 'Kupfer blank'
    service_price: '$1,200'
    service_text: 'Kupfer neu blank bezeichnet man die blanke Bleche, Rohre, Oberleiter, Kerze usw. Kupfer muss frei von Schmutz, Farbe, Fett oder Lack sein.'
    service_link: 'https://livuss.ch/kupfer-ankauf/'
    link_text: 'Kupfer verkaufen'
    service_icon: globe
    metalle_foto:
      - kupferblech-1678479152.jpg
  -
    id: ZD5bttRu
    service_title: Altkupfer
    service_price: '$5,000'
    service_text: 'Der Altkupferpreis orientiert sich am Preis, zu dem Kupfer an den Weltmärkten gehandelt wird. Altkupfer, Raff, Berry oxidiert, Fett, Lack'
    link_text: 'Altkupfer Preise'
    service_icon: globe
    service_link: 'https://livuss.ch/altkupferpreis-schweiz/'
    metalle_foto:
      - altkupfer-1678479176.jpg
  -
    id: bRXcOico
    service_title: Kabel
    service_price: '$1,000'
    service_text: 'Kupferpreise Kabel wird nach Kupfer Anteil berechnet und dazu eine Kabel Preis pro Kilo vereinbart. Kabel muss frei vom Stecker.'
    service_link: 'https://livuss.ch/kabel-entsorgen/'
    link_text: 'Kabel entsorgen'
    service_icon: globe
    metalle_foto:
      - kupferkabel_450-1678479194.jpg
project_section_heading: Service
project_section_image:
  - kupfer-1-1677155361.jpg
completed_projects:
  -
    id: 01TASyNd
    project_category: Abholung
    client_name: 'kostenloses Abholung'
    project_image:
      - abholung-mit-hebebuene-1677140732.jpg
    client_text: 'Wir bieten einen kostenlose Abholservice f&uuml;r Altkupfer, <a href="kupferkabel-recycling.php" title="Kupferkabel, Kabelrecycling, Elektrokabel, Kupferkabel Preis, Alte Kabel">Kupferkabel</a>, etc. f&uuml;r Unternehmen und Privathaushalt.'
  -
    id: H3RHa1t4
    project_category: Waage
    client_name: 'Waage immer dabei'
    project_image:
      - waage-1677141064.jpg
    client_text: 'Wir bringen eine Waage mit, damit wir vor Ort das Schrott wie Altkupfer, Kupferkabel etc. Gewicht bestimmen k&ouml;nnen.'
  -
    id: tTfPJPfD
    project_category: Zahlung
    client_name: 'Barzahlung | Quittung'
    project_image:
      - barzahlung-1677141124.jpg
    client_text: 'Wir bieten Tagespreise für Kupferschrott, Kupferkabel, Altmessing, Rotguss, Zinn etc. Wir zahlen das Altmetall direkt in Bar aus.'
project_section_template: |-
  <!-- SERVICE ABHOLUNG -->
  <section class="projects section-padding" id="section_4">
                  <div class="container">
                      <div class="row">

                          <div class="col-12 ms-auto">
                              <div class="section-title-wrap d-flex justify-content-center align-items-center mb-4">
  	                           <h2 class="text-white me-4 mb-0">{{project_section_heading}}</h2> {{assets:project_section_image}}
                                  <img src="{{url}}" class="avatar-image img-fluid" alt="">
                                  {{/assets:project_section_image}}

                             
                              </div>
                          </div>

                          <div class="clearfix"></div>
  						
  						{{completed_projects}}
                          <div class="col-lg-4 col-md-6 col-12">
                              <div class="projects-thumb">
                                  <div class="projects-info">
                                      <small class="projects-tag">{{project_category}}</small>

                                      <h3 class="projects-title">{{client_name}}</h3>
                                     <h6 class="projects-title">{{client_text}}</h6>
                                  </div>
                                  
                                  {{assets:project_image}}

                                  <a href="{{url}}" class="popup-image"  title="{{alt}}">
                                      <img src="{{url}}" class="projects-image img-fluid" alt="">
                                  </a>
                                 {{/assets:project_image}}
                              </div>
                          </div>
                          
                          {{/completed_projects}}
                      </div>

                  </div>
  <div class="container">
                      <div class="row">
  <p>{{service_text}}</p>
  </div>
  </div>
              </section>
  <!-- ENDE SERVICE ABHOLUNG -->
company_section_title: 'Wir kaufen folgende Altmetalle'
sections: |-
  {{hero_section_antlr}}
  {{information_section_template}}
  {{story_section_antlr}}
  {{companies_worked_section}}
  {{service_template_section}}
  {{project_section_template}}
my_big_image:
  - guitar-center-1677104955.svg
offerte_image:
  - altkupfer-1677104971.jpg
offerte_section_antlr: |-
  <section class="about section-padding" id="section_2">
                  <div class="container">
                      <div class="row">

                          <div class="col-lg-6 col-12">
  	                        
  	                        
  	                        {{ assets:offerte_big_image }}
                              <img src="{{url}}" class="about-image img-fluid" alt="">
                              {{ /assets:offerte_big_image }}
                          </div>

                          <div class="col-lg-6 col-12 mt-5 mt-lg-0">
                              <div class="about-thumb">

                                  <div class="section-title-wrap d-flex justify-content-end align-items-center mb-4">
                                      <h2 class="text-white me-4 mb-0">{{offerte_heading}}</h2>
                                       {{ assets:offerte_image }}

                                      <img src="{{url}}" class="avatar-image img-fluid" alt="">
                                       {{ /assets:offerte_image }}
                                  </div>

                                  <h3 class="pt-2 mb-3">{{offerte_title}}</h3>

                                  {{offerte_story_text}}
                              </div>
                          </div>

                      </div>
                  </div>
              </section>
offerte_text: 'Hier kommt Offertetext'
metalle_text: |-
  Bei uns können <b>Privatpersonen</b> und <b>Gewerbe</b> Altkupfer verkaufen egal ob aus Produktion, Werkstatt oder private Sammlung.<br>
  Wir bieten spezielle <b>Altkupferpreis Schweiz</b> für Elektriker, Dachdecker, Spengler, Sanitäre und andere Handwerker an!<br>
  Dazu benützen Sie vorbereitete Offerte-Formular oder rufen Sie uns einfach an und wir machen Ihnen sofort eine persönliche Offerte! <a href="https://www.livuss.ch/offerte/" target="blank">Weiter mit Offerte ...</a>
service_text: |-
  <b>Metallboxen und Paloxen</b><br>
  Wir stellen Ihnen die Metallboxen (1200x800x800mm) oder Kunsstoff-Paloxe (1200x1000x800mm)direkt zu verf&uuml;gung. Sobald sind die Boxen voll, hohlen wir sie mit Hebebühne ausgerüstete Fahrzeug ab. Die Boxenmiete ist kostenlos.
assets_metalle:
  - altkupfer-1677193600.jpg
company_logos_text: 'Bei uns können <b>Privatpersonen</b> und <b>Firmen</b> Altkupfer verkaufen egal ob aus Produktion, Werkstatt oder private Sammlung. Wir bieten spezielle Altkupferpreis Schweiz für Elektriker, Dachdecker, Spengler, Sanitäre und andere Handwerker an!'
company_text_area: 'Bei uns können <b>Privathaushalte</b> und <b>Firmen</b>Altkupfer verkaufen egal ob aus Produktion, Werkstatt oder private Sammlung. <br>Wir bieten spezielle Altkupferpreis Schweiz für Elektriker, Dachdecker, Spengler, Sanitäre und andere Handwerker an!'
firmainfo_text: |-
  Livuss GmbH ist ein Abnehmer für Buntmetalle wie Altkupfer, Kabel, Messing, etc.<br>
  Livuss GmbH bietet Abholdienst für Altkupfer ab Privathaushalt, Werkstatt, Lager, Produktion und direkt von dem Baustelle an.<br> Wir bieten Altkupferpreis als Tagespreise für Altkupfer, Kabel, Kupferschrott, Elektrokabel, etc.
firmainfo_titel: '<b>Kupferpreise + Entsorgung Service + Abholung Service</b>'
offerte_form_start: |-
  <!-- OFFERTEFORMULAR -->
  <div class="col-lg-6 col-12 mt-5 mt-lg-0">
  	<h6>Offerte starten</h6>                            
  	                            
  	                        
  	                                                   
                              {{ form:offerte_sent class="custom-form contact-form" }}
                              <div class="row">
  	                            
  	                           
  	                            
  	                            {{ fields }}
  	                            
  	                            
  	                           	                           
  	                            
  	                            
  	                         {{if type == "select"}}
  	                         

  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{handle}}" id="{{handle}}" class="form-control" placeholder="Metallart" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
  	                         {{if type == "select"}}
  	                         
  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
      <select size="1" name="metallschrott" id="metallschrott" class="form-control"  required="">
          <option selected value="check">Schrott ausw&auml;hlen!</option>
          <option value="Millberry">Kupfer, blank I, Millberry</option>
  	<option value="Elektrolyt ECU">Elektrilyt, blank (ECU)</option>
  	<option value="Kupfer neu">Kupferblech, blank II</option>
  	<option value="Oberleitungsdrath">Kupfer-Oberleitungsdraht</option>
  	<option value="Kupfer-98%">Kupfer 98%, Berry</option>
  	<option value="Sammelkupfer-95%">Sammelkupfer 95%</option>
  	<option value="Kupfer-verzinnt/vernickelt">Kupfer Ni/Si/Sn</option>
  	<option value="Kupfer-lackiert">Kupferdrath lackiert/Trafo</option>
  	<option value="Kupferspaene">Kupfersp&auml;ne sauber</option>
  	<option value="Kupfergranulat-1B">Kupfergranulat IB</option>
  	<option value="Kupfergranulat-2">Kupfergranulat II</option>
  	<option value="Kupfergranulat-3">Kupfergranulat III</option>
  	<option value="---">---------------------</option>
  	<option value="Kupferkabel-<40%">Kupferkabel < 40%</option>
  	<option value="Kupferkabel-40-44%">Kupferkabel 40-44%</option>
  	<option value="Kupferkabel-45-49%">Kupferkabel 45-49%</option>
  	<option value="Kupferkabel-50-54%">Kupferkabel 50-54%</option>
  	<option value="Kupferkabel-55-59%">Kupferkabel 55-59%</option>
  	<option value="Kupferkabel-60-64%">Kupferkabel 60-64%</option>
  	<option value="Kupferkabel-65-69%">Kupferkabel 65-69%</option>
  	<option value="Kupferkabel-70-74%">Kupferkabel 70-74%</option>
  	<option value="Kupferkabel-75-80%">Kupferkabel 75-80%</option>
  	<option value="---">---------------------</option>
  	<option value="Bronzespaene(CuSn)">Bronzesp&auml;ne (CuSn)0</option>
  	<option value="Bronze(CuSn)">Bronze (CuSn)0</option>
  	<option value="MS-Partonenhuelsen">Patronenh&uuml;lsen, MS-72</option>
  	<option value="Messing-63">Messing 63</option>
  	<option value="Messing-58">Messing 58</option>
  	<option value="Schwermessing">Schwermessing</option>
  	<option value="Messingspaene">Messingsp&auml;ne, 2% Feucht</option>
  	<option value="---">---------------------</option>
  	<option value="Beschreibung">nach Beschreibung</option>
  </select>                                     
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
  	                         {{if type == "select"}}
               <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{handle}}" id="{{handle}}" class="form-control" placeholder="Name" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
       
                                {{ /fields }}
                              </div>
                              
                               <input type="hidden" class="hidden" name="{{ honeypot ?? 'honeypot' }}">
                               <div class="col-lg-3 col-12 ms-auto">
                                              <button type="submit" class="form-control">Weiter</button>
                                          </div>
                              
                              {{ /form:offerte_sent }}
                              
                              </div>
  <!-- ENDE OFFERTEFORMULAR -->
offerte_form_feld: |-
  <div class="col-lg-6 col-12 mt-5 mt-lg-0">
  	<h6>Kontaktieren Sie mit uns</h6>                            
  	                            
  	                        
  	                                                   
                              {{ form:offerte class="custom-form contact-form" }}
                              <div class="row">
  	                            
  	                           
  	                            
  	                            {{ fields }}
  	                            
  	                            
  	                           	                           
  	                            
  	                            
  	                         {{if type == "text"}}
  	                         

  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{handle}}" id="{{handle}}" class="form-control" placeholder="Name" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
  	                         {{if type == "email"}}
  	                         
  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{handle}}" id="{{handle}}" class="form-control" placeholder="Name" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
  	                         {{if type == "textarea"}}
  	                         
  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <textarea class="form-control" id="{{handle}}" name="{{handle}}" placeholder="{{display}}" required></textarea>
                                                  
                                                  <label for="floatingTextarea">{{display}}</label>
                                              </div>
                                          </div>
  	                         {{/if}}
  	                         {{if type == "checkboxes"}}
  	                         
  	 <div class="clearfix"></div>                        
  	                         
  	                          <div class="col-lg-3 col-md-6 col-6">
                                              <div class="form-check form-check-inline">
                                                  <input name="{{handle}}[]" type="checkbox" class="form-check-input" id="inlineCheckbox1" value="Preise">

                                                  <label class="form-check-label" for="inlineCheckbox1">
                                                      <span class="form-check-label-text">Preise</span>
                                                  </label>
                                            </div>
                                          </div>

                                          <div class="col-lg-3 col-md-6 col-6">
                                              <div class="form-check form-check-inline">
                                                  <input name="{{handle}}[]" type="checkbox" class="form-check-input" id="inlineCheckbox2" value="Offerte">

                                                  <label class="form-check-label" for="inlineCheckbox2">
                                                      <span class="form-check-label-text">Offerte</span>
                                                  </label>
                                              </div>
                                          </div>

                                          <div class="col-lg-3 col-md-6 col-6">
                                              <div class="form-check form-check-inline">
                                                  <input name="{{handle}}[]" type="checkbox" class="form-check-input" id="inlineCheckbox3" value="Abholung">

                                                  <label class="form-check-label" for="inlineCheckbox3">
                                                      <span class="form-check-label-text">Abholung</span>
                                                  </label>
                                              </div>
                                          </div>

                                          <div class="col-lg-3 col-md-6 col-6">
                                              <div class="form-check form-check-inline me-0">
                                                  <input name="{{handle}}[]" type="checkbox" class="form-check-input" id="inlineCheckbox4" value="Anderes">

                                                  <label class="form-check-label" for="inlineCheckbox4">
                                                      <span class="form-check-label-text">Anderes</span>
                                                  </label>
                                              </div>
                                          </div>
  	                         {{/if}}
                               
                                {{ /fields }}
                              </div>
                              
                               <input type="hidden" class="hidden" name="{{ honeypot ?? 'honeypot' }}">
                               <div class="col-lg-3 col-12 ms-auto">
                                              <button type="submit" class="form-control">Send</button>
                                          </div>
                              
                              {{ /form:offerte }}
                              
                              </div>
offerteformular_titel: 'Offerter für Altmetall'
offerte_sektion_template: |-
  <!-- OFFERTEFORMULAR <div class="col-lg-6 col-12 mt-5 mt-lg-0">
  	<h6>Offerte für Altmetall</h6>                            
  	                            
  	                        
  	                                                   
                              {{ form:offerte1 class="custom-form contact-form" }}
                              <div class="row">
  	                            
  	                           
  	                            
  	                            {{ fields }}
  	                            
  <!-- SELECT-->	                                
  	                         {{if type == "select"}}                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{handle}}" id="{{handle}}" class="form-control" placeholder="Name" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
  <!-- ende SELECT -->
  <!-- TEXT-->	                           	                           
  	                         {{if type == "text"}}
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{handle}}" id="{{handle}}" class="form-control" placeholder="Name" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
   <!-- ende TEXT-->

  <!-- email --> 
  	                         {{if type == "email"}}
  	                         
  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <input type="text" name="{{metallschrott}}" id="{{metallschrott}}" class="form-control" placeholder="Name" required="">
                                                  
                                                  <label for="floatingInput">{{display}}</label>
                                              </div>
                                          </div>
                                          {{/if}}
  <!-- ende email --> 
  <!-- kommentar--> 
  	                         {{if type == "textarea"}}
  	                         
  	                         
  	                         <div class="col-lg-6 col-md-6 col-12">
                                              <div class="form-floating">
                                                  <textarea class="form-control" id="{{handle}}" name="{{handle}}" placeholder="{{display}}" required></textarea>
                                                  
                                                  <label for="floatingTextarea">{{display}}</label>
                                              </div>
                                          </div>
  	                         {{/if}}

  <!-- ende kommentar--> 
                               
                                {{ /fields }}
                              </div>
                              
                               <input type="hidden" class="hidden" name="{{ honeypot ?? 'honeypot' }}">
                               <div class="col-lg-3 col-12 ms-auto">
                                              <button type="submit" class="form-control">Send</button>
                                          </div>
                              
                              {{ /form:offerte1 }}
                              
                              </div>
  <!-- ENDE OFFERTEFORMULAR -->
assets_offerteformular:
  - kupferschrott-1677616995.jpg
offerte_textarea: |-
  <h3><b>So get`s</b></h3>
  <b>Altmetall wählen</b><br>
  Wenn Sie Ihr Altmetall in der Liste nicht finden, wählen sie die Option "nach Beschreibung" und in Feld "Kommentar" schreiben Sie uns noch eine Nachricht. Wir können ein individuelles Angebot für Ihr Schrott erstellen.<br>
  <b>Menge wählen</b>
  Das Menge soll ungefähr in Kilo eingegeben werden. Wenn Sie nicht die richtige Menge angegeben haben, ist kein Problem.
  Vor Ort wird das genaue Gewicht mit unsere Waage ermittelt.<br>
  <b>Transport wählen</b><br>
  Sie können zwischen zwei Transporten für Ihr Altmetall wählen:<br>
  1. Abholung - Paletten mit SBB-Rahmen, Box oder lose Ladung (Fahrzeug ist mit Hebebühne ausgerüstet)<br>
  2. selbst Anlieferung
---
