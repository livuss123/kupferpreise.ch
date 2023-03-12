---
id: home
blueprint: pages
title: Home
template: home
author: e412c360-631e-4193-875a-5151f082ee98
title_1: 'Hello friend!'
title_2: 'I’m available for freelance work.'
button_text: "Let's Begin"
small_image:
  - youngman.jpg
big_image:
  - youngmansitting.png
updated_by: e412c360-631e-4193-875a-5151f082ee98
updated_at: 1660106687
story_big_image:
  - couple-sofa.jpg
story_heading: 'My Story'
story_title: 'a little bit about Joshua'
my_image:
  - youngman.jpg
my_story_text: |-
  This one-page HTML portfolio is provided by Revolve 314 Digital. This layout is based on Bootstrap v5.1.3 CSS and JS libraries. Image credits go to Unsplash and FreePik for images used in this page.</p>

  <p>You are allowed to use this template for your websites. You are not allowed to redistribute the template ZIP file on any other website. Please contact us for more info.</p>
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

                          <div class="col-lg-6 col-12">
  	                        
  	                        
  	                        {{ assets:story_big_image }}
                              <img src="{{url}}" class="about-image img-fluid" alt="">
                              {{ /assets:story_big_image }}
                          </div>

                          <div class="col-lg-6 col-12 mt-5 mt-lg-0">
                              <div class="about-thumb">

                                  <div class="section-title-wrap d-flex justify-content-end align-items-center mb-4">
                                      <h2 class="text-white me-4 mb-0">{{story_heading}}</h2>
                                       {{ assets:my_image }}

                                      <img src="{{url}}" class="avatar-image img-fluid" alt="">
                                       {{ /assets:my_image }}
                                  </div>

                                  <h3 class="pt-2 mb-3">{{story_title}}</h3>

                                  {{my_story_text}}
                              </div>
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
name: 'Manup Rav'
birth_day: '1982-11-08'
phone: '918907289865'
email: info@revolve314.com
experience: 15+
customers: '20'
projects: '1000'
awards: 10+
information_section_template: |-
  <section class="featured section-padding">
                  <div class="container">
                      <div class="row">

                          <div class="col-lg-6 col-12">
                              <div class="profile-thumb">
                                  <div class="profile-title">
                                      <h4 class="mb-0">{{infotitle}}</h4>
                                  </div>

                                  <div class="profile-body">
                                      <p>
                                          <span class="profile-small-title">Name</span> 
                                          <span>{{name}}</span>
                                      </p>

                                      <p>
                                          <span class="profile-small-title">Birthday</span> 
                                          <span>{{birth_day}}</span>
                                      </p>

                                      <p>
                                          <span class="profile-small-title">Phone</span> 
                                           <span><a href="tel: {{phone}}">{{phone}}</a></span>
                                      </p>

                                      <p>
                                          <span class="profile-small-title">Email</span> 
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

                                          <p class="featured-text">Years of Experiences</p>
                                      </div>

                                      <div class="col-lg-6 col-6 featured-border-start featured-border-bottom ps-5 py-2">
                                          <strong class="featured-numbers">{{customers}}</strong>

                                          <p class="featured-text">Happy Customers</p>
                                      </div>

                                      <div class="col-lg-6 col-6 pt-4">
                                          <strong class="featured-numbers">{{projects}}</strong>

                                          <p class="featured-text">Project Finished</p>
                                      </div>

                                      <div class="col-lg-6 col-6 featured-border-start ps-5 pt-4">
                                          <strong class="featured-numbers">{{awards}}</strong>

                                          <p class="featured-text">Digital Awards</p>
                                      </div>
                                  </div>
                              </div>
                          </div>

                      </div>
                  </div>
              </section>
company_logos:
  -
    company_logo:
      - tokico.svg
  -
    company_logo:
      - cachet.svg
  -
    company_logo:
      - guitar-center.svg
  -
    company_logo:
      - tokico.svg
  -
    company_logo:
      - shopify.svg
companies_worked_section: |-
  <section class="clients section-padding">
                  <div class="container">
                      <div class="row align-items-center">

                          <div class="col-lg-12 col-12">
                              <h3 class="text-center mb-5">{{company_section_title}}</h3>
                          </div>
                          
                          {{company_logos}}
  						{{assets:company_logo}}
                          <div class="col-lg-2 col-4 ms-auto clients-item-height">
                              <img src="{{url}}" class="clients-image img-fluid" alt="">
                          </div>
                          {{/assets:company_logo}}

                          {{/company_logos}}

                      </div>
                  </div>
              </section>
section_title: Services
service_template_section: |-
  <section class="services section-padding" id="section_3">
                  <div class="container">
                      <div class="row">

                          <div class="col-lg-10 col-12 mx-auto">
                              <div class="section-title-wrap d-flex justify-content-center align-items-center mb-5">
  	                            {{assets:section_image}}
                                  <img src="{{url}}" class="avatar-image img-fluid" alt="{{section_title}}">
                                 {{/assets:section_image}}

                                  <h2 class="text-white ms-4 mb-0">{{section_title}}</h2>
                              </div>
  							
                              <div class="row pt-lg-5">
  	                            {{services_offered}}
                                  <div class="col-lg-6 col-12">
                                      <div class="services-thumb">
                                          <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
                                              <h3 class="mb-0">{{service_title}}</h3>

                                              <div class="services-price-wrap ms-auto">
                                                  <p class="services-price-text mb-0">{{service_price}}</p>
                                                  <div class="services-price-overlay"></div>
                                              </div>
                                          </div>

                                          <p>{{service_text}}</p>

                                          <a href="{{service_link}}" class="custom-btn custom-border-btn btn mt-3">{{link_text}}</a>

                                          <div class="services-icon-wrap d-flex justify-content-center align-items-center">
                                              <i class="services-icon bi-{{service_icon}}"></i>
                                          </div>
                                      </div>
                                  </div>
  								{{/services_offered}}
                                  
                              </div>
                          </div>
                      </div>
                  </div>
              </section>
section_image:
  - handshake-man-woman-after-signing-business-contract-closeup.jpg
services_offered:
  -
    service_title: Websites
    service_price: '$2,400'
    service_text: 'You may want to explore Too CSS for great collection of free HTML CSS templates.'
    service_link: 'http://www.revolve314.com'
    link_text: 'Discover More'
    service_icon: globe
  -
    service_title: Branding
    service_price: '$1,200'
    service_text: 'You can explore more CSS templates on TemplateMo website by browsing through different tags.'
    service_link: 'http://www.revolve314.com'
    link_text: 'Find Out'
    service_icon: phone
  -
    service_title: Ecommerce
    service_price: '$5,000'
    service_text: 'If you need a customized ecommerce website for your business, feel free to discuss with me.'
    link_text: 'http://www.revolve314.com'
    service_icon: lightbulb
  -
    service_title: SEO
    service_price: '$1,000'
    service_text: 'To list your website first on any search engine, we will work together. First Portfolio is one-page CSS Template for free download.'
    service_link: 'http://www.revolve314.com'
    link_text: 'Get Now'
    service_icon: google
project_section_heading: Projects
project_section_image:
  - white-desk-work-study-aesthetics.jpg
completed_projects:
  -
    project_category: Branding
    client_name: 'Zoik agency'
    project_image:
      - nikhil-ko4io-ecaxa-unsplash.jpg
  -
    project_category: PHOTOGRAPHY
    client_name: 'The Watch'
    project_image:
      - the-5th-iqyr7n67dhm-unsplash.jpg
  -
    project_category: Website
    client_name: Polo
    project_image:
      - true-agency-9bjog5fz-oc-unsplash.jpg
project_section_template: |-
  <section class="projects section-padding" id="section_4">
                  <div class="container">
                      <div class="row">

                          <div class="col-lg-8 col-md-8 col-12 ms-auto">
                              <div class="section-title-wrap d-flex justify-content-center align-items-center mb-4">
  	                            {{assets:project_section_image}}
                                  <img src="{{url}}" class="avatar-image img-fluid" alt="">
                                  {{/assets:project_section_image}}

                                  <h2 class="text-white ms-4 mb-0">{{project_section_heading}}</h2>
                              </div>
                          </div>

                          <div class="clearfix"></div>
  						
  						{{completed_projects}}
                          <div class="col-lg-4 col-md-6 col-12">
                              <div class="projects-thumb">
                                  <div class="projects-info">
                                      <small class="projects-tag">{{project_category}}</small>

                                      <h3 class="projects-title">{{client_name}}</h3>
                                  </div>
                                  
                                  {{assets:project_image}}

                                  <a href="{{url}}" class="popup-image">
                                      <img src="{{url}}" class="projects-image img-fluid" alt="">
                                  </a>
                                 {{/assets:project_image}}
                              </div>
                          </div>
                          
                          {{/completed_projects}}

                         

                      </div>
                  </div>
              </section>
company_section_title: "Companies I've had worked"
sections: |-
  {{hero_section_antlr}}
  {{information_section_template}}
  {{story_section_antlr}}
  {{companies_worked_section}}
  {{service_template_section}}
  {{project_section_template}}
published: true
---
