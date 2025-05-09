<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Shimiyana Jkaroda</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .active-link {
      background-color: #bfdbfe;
      color: #1d4ed8;
      font-weight: 600;
      border-radius: 0.375rem;
      padding: 0.25rem 0.5rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 0.5rem;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
  
</head>
<body class="bg-gray-100 font-sans"   >


  <div class="flex">
    <!-- Sidebar -->
    <div class="w-59 h-screen sticky top-0 bg-white shadow-lg p-6" style="background-image: url('gara/MAIN.jpg'); background-size: cover; background-repeat: no-repeat; background-position: center;">
        <img src="gara/port.jpg" alt="Profile Photo" class="w-32 h-32 rounded-full object-cover" />
      <h1 class="text-1xl font-bold mb-4">Shimiyana Jakroda</h1>
      <ul class="space-y-4">
        <li><button onclick="scrollToSection('home')" id="btn-home" class="sidebar-link text-blue-600 hover:underline">Home</button></li>
        <li><button onclick="scrollToSection('publications')" id="btn-publications" class="sidebar-link text-blue-600 hover:underline">Publications</button></li>
        <li><button onclick="scrollToSection('gallery')" id="btn-gallery" class="sidebar-link text-blue-600 hover:underline">Gallery</button></li>
        <li><button onclick="scrollToSection('cv')" id="btn-cv" class="sidebar-link text-blue-600 hover:underline">CV</button></li>
      </ul>
    </div>

    <!-- Scrollable Content -->
    <div class="flex-1 overflow-y-auto h-screen scroll-smooth" id="scrollContainer">
      <section id="home" class="min-h-screen p-8 bg-gray-50">
        <div class="slider-text animated fadeInUp" style="height: 607px;"  >
            <div class="slider-text-inner" style="display: flex; align-items: center; gap: 40px; height: 607px;"   >
              
              <div class="container" >

                <div style="display: flex; align-items: flex-start; gap: 20px;">
                    <!-- Text Content -->
                    <div class="desc" style="flex: 1;">
                        <h1 style="font-family: 'Arial Black', sans-serif; font-weight: bold; font-size: 2.5em; margin-top: 0;">
                            Hi! <br>I'm Shimiyana
                        </h1>
                        <h2 style="margin-top: 0;">
                            I am an Assistant Professor at Mississippi State University specializing in robotics, computer vision, and artificial intelligence.
                        </h2>
                    </div>
                    
                    <!-- GIFs Column -->
                    <div style="flex: 1; display: flex; flex-direction: column; gap: 20px;">
                        <!-- First gif -->
                        <div class="gif-section" align="left">
                            <img src="Gif/ROBOTICS.gif" alt="Robot GIF" style="width: 100%; max-width: 400px; border-radius: 8px;">
                            <p text align="left"  style="font-family: 'garamond'; font-weight: italic; font-size: 1.0em; margin-top: 0;">My Tearm and I developed ClownBoat prototype using Python <br>and Java, incorporating remote control functionality and <br> programmable instruction sets for autonomous and manual navigation.</p>
                        </div>
                        
                        <!-- Second gif -->
                        <div class="gif-section" align="left">
                            <img src="gara/Show.png" alt="Second GIF" style="width: 100%; max-width: 400px; border-radius: 8px;">
                            <p  align="left"   style="font-family: 'garamond'; font-weight: italic; font-size: 1.0em; margin-top: 0;">(Co-represented the Cavendish University Zambia on 26th <br> August 2023 In Capture the Flag CTF Hosted by Digital Safe at UNICAF University in Lusaka, Zambia) – Cyber Security Hacking Competition</p>
                        </div>
                    </div>
                </div>
            </div>
            
    </section>

      <!-- Publications Section -->
      <section id="publications" class="min-h-screen p-8 bg-white">
        <h2 class="text-xl font-semibold mb-5" align="center"><em>Publication</em></h2>
          <!-- Book publication -->
           <br>
        <div>
          
            <div class="container" >
              <div style="display: flex; align-items: flex-start; gap: 20px;">
                <h1 class="text-xl font-semibold mb-4">Brain Winners</h1><br>
                <p><em>Shimiyana Jakroda & Kenneth Chitambo, <br>
                  Brain Winners. First published 26th January 2020.<br>
                  Publisher: Self, Lusaka. 2020.</em><br><br>
                  This book empowers readers to develop a positive mindset<br> for personal and professional success.  
                  It offers practical strategies,<br> inspiring stories, and tools for overcoming challenges.  
                  Each chapter <br>guides you to build resilience, stay motivated, and pursue<br> big dreams.  
                  By embracing optimism, you'll unlock your potential<br> and transform your life.
                
                </p>

                  <!-- publications -->
                  <div style="flex: 1; display: flex; flex-direction: column; gap: 20px;">
                      <!-- book-->
                      <div class="gif-section" align="center">
                          <img src="gara/book.png" alt="Robot GIF" style="width: 100%; max-width: 400px; border-radius: 8px;">
                          <p><em><b>ISBN: 978-9982-70-822-7</b></em></p>
                    </div>
                    
                  </div>
              </div>
          </div>

<!--Career-->

          <div class="container" >
            <div style="display: flex; align-items: flex-start; gap: 20px;">
              <h1 class="text-xl font-semibold mb-4">Career Paths<br> for Refugee<br> Students</h1><br>
              <p><em>This magazine was authored by DAFI Zambia students.<br> As the DAFI President, I took the lead in planning 
                and organizing<br> the event in collaboration with the executive team.</em><br><br>

                Conference Summary<br>
                The conference aimed to highlight career pathways for people <br>
                on the move, focusing on scholarships, talent development,<br> and job opportunities.<br>
                
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                <em><b><u>Speakers included</u></b>:</em><br>
                <b>Dr. Nicolas Maple</b> – Lecturer in Migration Studies, Universityof London.<br>
                <br>
                <b>Mainga Simoonga</b> – International Law Master’s Student,<br>
                University of Glasgow; African Excellence Scholar; Lawyer and Author.<br>
                <br>
                <b>Marie Françoise</b> – Pharmacist; President of the Zambia Union of Pharmacy <br>
                Professionals; Founder of Life Lessons for a Girl Child.
                <br><br>
                <b>Esther Chongo Zulu</b>– Executive Director, YMCA Zambia; MBA student <br>
                at Heriot-Watt University; Advocate for youth and women empowerment.
                <br> <br>

                <b>Dr. Murishi Onesphore</b> – Master's student in Project Management, University of London.

              
               
              
              </p>

                <!-- publications -->
                <div style="flex: 1; display: flex; flex-direction: column; gap: 20px;" >
                    <!-- book-->
                    <div class="gif-section" align="center">
                        <img src="gara/DAFI.jpg" alt="Robot GIF" style="width: 100%; max-width: 400px; border-radius: 8px;">
                        <p>
                          <a href="https://drive.google.com/file/d/1UYihoydbYyWIo_L_a7KRVDp724Jjo6Nz/view?usp=sharing" 
                             target="_blank" 
                             style="text-decoration: none; color: black;" 
                             onmouseover="this.style.color='blue'" 
                             onmouseout="this.style.color='black'">
                            <b>Click here to access the Magazine</b>
                          </a>
                        </p>
                      
                  </div>
                  
                </div>
            </div>
        </div>

        <!--Add more publications -->

        <!--end here-->

        </div>
      </section>

   
      <!-- Gallery Section -->
<section id="gallery" class="min-h-screen p-8 bg-gray-50"  >
    <h2 class="text-2xl font-bold mb-6 text-gray-800" align="center"><em>Gallery</em></h2>

    <div class="flex gap-4"> <!-- Adjust gap (spacing) as needed -->
      <img 
          src="gara/me.png" 
          alt="Project 1"  
          class="w-[700px] h-[500px] object-cover rounded-lg transition-all duration-300 group-hover:scale-105">
      
      <img 
          src="gara/Brainv.jpg" 
          alt="Project 2"  
          class="w-[700px] h-[500px] object-cover rounded-lg transition-all duration-300 group-hover:scale-105">
  </div>

<br>
  <div class="flex gap-4"> <!-- Adjust gap (spacing) as needed -->
    <img 
        src="gara/frame.jpg" 
        alt="Project 1"  
        class="w-[400px] h-[500px] object-cover rounded-lg ">
        
    
    <img 
        src="gara/ALRO.png" 
        alt="Project 2"  
        class="w-[700px] h-[500px] object-cover rounded-lg transition-all duration-300 group-hover:scale-105">
</div>
<br>
<div class="flex gap-4"> <!-- Adjust gap (spacing) as needed -->
  <img 
      src="gara/german.png" 
      alt="Project 1"  
      class="w-[700px] h-[500px] object-cover rounded-lg ">
      
  
  <img 
      src="gara/power.png" 
      alt="Project 2"  
      class="w-[700px] h-[500px] object-cover rounded-lg transition-all duration-300 group-hover:scale-105">
</div>


    <div>
      
      <!-- Add more images as needed -->
    </div>
  </section>
  
  <style>
    /* Base Gallery Styles */
    .gallery-grid {
      display: grid;
      transition: all 0.3s ease;
    }
    
    /* Column Variations */
    .gallery-cols-2 { grid-template-columns: repeat(2, minmax(0, 1fr)); }
    .gallery-cols-3 { grid-template-columns: repeat(3, minmax(0, 1fr)); }
    .gallery-cols-4 { grid-template-columns: repeat(4, minmax(0, 1fr)); }
    
    /* Gap Variations */
    .gallery-gap-2 { gap: 0.5rem; }
    .gallery-gap-4 { gap: 1rem; }
    .gallery-gap-6 { gap: 1.5rem; }
    
    /* Masonry Layout */
    .gallery-masonry {
      column-count: 3;
      column-gap: 1rem;
    }
    .gallery-masonry .gallery-item {
      break-inside: avoid;
      margin-bottom: 1rem;
    }
    
    /* Gallery Item Styles */
    .gallery-item {
      position: relative;
      overflow: hidden;
      border-radius: 0.5rem;
    }
    
    .gallery-caption {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: rgba(0, 0, 0, 0.7);
      color: white;
      padding: 0.5rem;
      transition: opacity 0.3s ease;
    }
    
    /* Responsive Adjustments */
    @media (max-width: 768px) {
      .gallery-cols-3, .gallery-cols-4 {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }
      .gallery-masonry {
        column-count: 2;
      }
    }
    
    @media (max-width: 480px) {
      .gallery-grid {
        grid-template-columns: 1fr !important;
      }
      .gallery-masonry {
        column-count: 1;
      }
    }
  </style>
  
  <script>
    // Gallery Layout Controls
    function changeLayout(layoutType) {
      const gallery = document.getElementById('gallery-container');
      
      if (layoutType === 'masonry') {
        gallery.classList.add('gallery-masonry');
        gallery.classList.remove('gallery-grid', 'gallery-cols-2', 'gallery-cols-3', 'gallery-cols-4');
      } else {
        gallery.classList.remove('gallery-masonry');
        gallery.classList.add('gallery-grid');
        
        // Keep current column count
        const currentCols = Array.from(gallery.classList).find(c => c.startsWith('gallery-cols-'));
        if (!currentCols) gallery.classList.add('gallery-cols-3');
      }
    }
    
    function changeColumns(columns) {
      const gallery = document.getElementById('gallery-container');
      
      // Remove all column classes
      gallery.classList.remove('gallery-cols-2', 'gallery-cols-3', 'gallery-cols-4');
      
      // Add selected column class
      gallery.classList.add(`gallery-cols-${columns}`);
      
      // Ensure we're in grid mode
      gallery.classList.remove('gallery-masonry');
      gallery.classList.add('gallery-grid');
    }
  </script>

      <!-- CV Section -->
      <section id="cv" class="min-h-screen p-8 bg-white">
        <h2 class="text-xl font-semibold mb-4">Curriculum Vitae</h2>
        <p>Include your experience, education, and skills here.</p>
      </section>
    </div>
  </div>

  <script>
    const sectionIds = ['home', 'publications', 'gallery', 'cv'];

    function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
      updateActiveLink(id);
    }

    function updateActiveLink(activeId) {
      sectionIds.forEach(id => {
        const btn = document.getElementById('btn-' + id);
        btn.classList.remove('active-link');
      });
      document.getElementById('btn-' + activeId).classList.add('active-link');
    }

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          updateActiveLink(entry.target.id);
        }
      });
    }, {
      threshold: 0.6,
    });

    sectionIds.forEach(id => {
      observer.observe(document.getElementById(id));
    });

    // Set Home as active on load
    window.onload = () => updateActiveLink('home');


    
  </script>

</body>
</html>
