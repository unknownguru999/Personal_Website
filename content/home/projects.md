---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: blank

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  # filter_button:
  # - name: All
  #   tag: '*'
  # - name: Machine Learning
  #   tag: Machine Learning
  # - name: Others
  #   tag: Others

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: true


---
<div>
  <span class="d-none default-project-filter">*</span>
  <div class="project-toolbar">
     <div class="project-filters">
       <div class="btn-toolbar">
          <div class="btn-group flex-wrap">
             <a href="#" data-filter="*" class="btn btn-primary btn-lg active">All</a>
             <a href="#" data-filter=".js-id-Machine-Learning" class="btn btn-primary btn-lg">Machine Learning</a>
             <a href="#" data-filter=".js-id-Others" class="btn btn-primary btn-lg">Others</a>
          </div>
        </div>
      </div>
  </div>
  <div class="isotope projects-container js-layout-masonry ">
    <div class="project-card project-item isotope-item js-id-Machine-Learning"  style="width:47%;">
      <div class="card">
        <a href="https://docs.google.com/presentation/d/1L9hDO06Da-BQPkVQw43E0YiowjoJVxlt/edit#slide=id.p1" target="_blank" rel="noopener" class="card-image hover-overlay">
          <!-- <img src="/project/bearing-fault-analysis/featured_hudaa2406c08d5691f23c6ffd9430f1454_47595_550x0_resize_q75_lanczos.jpg" alt="Bearing Fault Analysis" class="img-responsive" loading="lazy"> -->
          <img src="/project/bearing-fault-analysis/featured.jpg" alt="Bearing Fault Analysis">
        </a>
        <div class="card-text">
          <h4><a href="https://docs.google.com/presentation/d/1L9hDO06Da-BQPkVQw43E0YiowjoJVxlt/edit#slide=id.p1" target="_blank" rel="noopener">Bearing Fault Analysis</a></h4>
          <div class="article-style">
            <p>Estimated the remaining useful life of a bearing using Machine Learning. Achieved better prognostic performance with 98.2% accuracy as compared to SOTA techniques such as Kalman filter.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="project-card project-item isotope-item js-id-Others"  style="width:47%;">
    <div class="card">
      <a href="https://drive.google.com/file/d/1jWiwrbebNARA4Vtifr_QObck2eZ-HAvA/view?usp=sharing" target="_blank" rel="noopener" class="card-image hover-overlay">
        <!-- <img src="/project/cleangenix/featured_hua5388018f25e1ba9573ac4b5849318d4_1598068_550x0_resize_lanczos_3.png" alt="Cleangenix" class="img-responsive" loading="lazy"> -->
         <img src="/project/cleangenix/featured.png" alt="Cleangenix" class="img-responsive" loading="lazy">
      </a>
      <div class="card-text">
        <h4><a href="https://drive.google.com/file/d/1jWiwrbebNARA4Vtifr_QObck2eZ-HAvA/view?usp=sharing" target="_blank" rel="noopener">Cleangenix</a></h4>
        <div class="article-style">
          <p>Devised a solution to improve city sanitation under Solid Waste Management Department using Neo4J and PostGreSQL. Developed an algorithm to identify trash from geotagged images using a Mask R-CNN model.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="project-card project-item isotope-item js-id-Others" style="width:47%;">
    <div class="card">
      <a href="https://github.com/ritikamangla/StartupQuest" target="_blank" rel="noopener" class="card-image hover-overlay">
        <!-- <img src="/project/startup-quest/featured_hu6a16746814d7e497725bbe64b91bedc7_200252_550x0_resize_q75_lanczos.jpg" alt="Startup Quest" class="img-responsive" loading="lazy"> -->
        <img src="/project/startup-quest/featured.jpg" alt="Startup Quest" class="img-responsive" loading="lazy">
      </a>
      <div class="card-text">
        <h4><a href="https://github.com/ritikamangla/StartupQuest" target="_blank" rel="noopener">Startup Quest</a></h4>
        <div class="article-style">
          <p>Created a social media bot which indexes 2000+ potential startup ideas in a database and a CRM dashboard to display it. Developed a news feed scraper to trace activities of the projects by web scraping data using Beautiful Soup.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="project-card project-item isotope-item js-id-Machine-Learning" style="width:47%;">
    <div class="card">
      <a href="https://github.com/ritikamangla/USS" target="_blank" rel="noopener" class="card-image hover-overlay">
        <!-- <img src="/project/unsupervised-speech-summarization/featured_hu130b2cad8ce86b835e60eea1b8dce233_28875_550x0_resize_q75_lanczos.jpg" alt="Unsupervised Speech Summarization" class="img-responsive" loading="lazy"> -->
        <img src="/project/unsupervised-speech-summarization/featured.jpg" alt="Unsupervised Speech Summarization" class="img-responsive" loading="lazy">
      </a>
      <div class="card-text">
        <h4><a href="https://github.com/ritikamangla/USS" target="_blank" rel="noopener">Unsupervised Speech Summarization</a></h4>
        <div class="article-style">
          <p>Performed text summarization by clustering sentence embeddings trained to embed paraphrases together using K-Means. Improved the accuracy by using a Skip-Thoughts (GRU-RNN) model to preserve sequence of words in a sentence.</p>
        </div>
        <div class="btn-links">
  <a class="btn btn-outline-primary btn-page-header btn-sm" href="https://drive.google.com/file/d/1Pv8snYcLHXj14vid9GXMdEr1TZK9_71A/view" target="_blank" rel="noopener">
    PDF
  </a>
        </div>
      </div>
    </div>
  </div>
  <div class="project-card project-item isotope-item js-id-Others" style="width:47%;">
    <div class="card">
        <a href="https://github.com/ritikamangla/Geo-Tracking-Of-Waste" target="_blank" rel="noopener" class="card-image hover-overlay">
          <!-- <img src="/project/geo-tracking/featured_hu8a4d985118fc14ac511c05a9bb20034e_398836_550x0_resize_lanczos_3.png" alt="GeoTracking of Waste" class="img-responsive" loading="lazy"> -->
          <img src="/project/geo-tracking/featured.png" alt="GeoTracking of Waste" class="img-responsive" loading="lazy">
        </a>
        <div class="card-text">
          <h4><a href="https://github.com/ritikamangla/Geo-Tracking-Of-Waste" target="_blank" rel="noopener">GeoTracking of Waste</a></h4>
          <div class="article-style">
            <p>Devised a platform for BMC, the governing civic body, to view the real time location of garbage trucks and the amount of waste collected.Created a dashboard to view daily statistics and reports in order to formulate measures to optimize waste management</p>
          </div>
          <div class="btn-links">
            <a class="btn btn-outline-primary btn-page-header btn-sm" href="https://docs.google.com/presentation/d/1bh13xyfoYqJT6KEHoojKBTo0L04ygglm/edit?usp=sharing&amp;ouid=117075748965628428005&amp;rtpof=true&amp;sd=true" target="_blank" rel="noopener">
              Slides
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>