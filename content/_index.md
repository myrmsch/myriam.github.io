---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      #button:
        #text: Download CV
        #url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: elliott-70adYpETLD8-unsplash.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '<svg width="144" height="144" viewBox="0 0 144 144" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M130.643 73.1741C129.786 82.3148 128.453 94.8357 120.716 108.642C117.789 113.855 102.697 139.325 79.5118 141.539C76.7268 141.801 73.656 141.563 67.4908 141.11C60.5877 140.587 55.0652 140.063 50.4948 139.278C45.1866 138.373 41.1637 137.111 37.7597 135.088C31.8087 131.541 29.1903 123.995 28.1191 116.521C29.6902 116.83 31.4279 117.164 33.3322 117.521C40.4258 118.854 45.2342 119.52 51.8755 119.592C53.7084 119.616 55.4698 119.544 57.2075 119.354C58.8738 119.497 60.5163 119.592 62.1111 119.592C65.5865 119.639 68.8715 119.33 71.8946 118.521C71.5851 120.949 71.7279 123.472 72.7277 125.805C72.9419 126.304 73.18 126.781 73.4894 127.257C76.6315 132.374 83.249 134.112 87.5337 134.065C105.291 133.874 123.002 102.762 127.024 74.6737C130.738 48.8703 124.454 15.1163 109.6 11.5695C104.815 10.4269 99.0786 12.4265 94.0322 15.9018C90.6282 18.2584 87.5337 21.2815 85.2486 24.495C82.7968 27.9466 81.3923 31.4458 80.6068 34.4689C77.7979 33.0407 74.632 32.0409 71.2995 31.2554C66.9909 30.2556 62.3968 29.6129 57.8026 28.994C49.3046 27.8276 43.2822 27.0183 38.0692 28.3513C39.9735 23.0668 43.4489 16.5445 49.8045 11.2839C59.7546 3.0477 71.1328 2.54782 80.583 2.28598C80.8448 2.28598 81.1067 2.26217 81.3685 2.26217C91.5804 2.00033 103.982 1.66708 114.337 8.99869C135.308 23.8285 131.976 58.9393 130.643 73.1741Z" fill="#262B2C"/>
<path d="M127.024 74.6747C122.978 102.763 105.291 133.875 87.5336 134.066C83.2489 134.113 76.6314 132.375 73.4893 127.258C73.2036 126.781 72.9418 126.305 72.7275 125.806C81.0351 120.378 88.2715 114.999 89.6045 111.952C93.0561 104.144 100.578 89.4093 103.887 72.4847C107.196 55.5601 104.482 41.9205 100.578 27.6619C99.507 23.7819 97.0552 19.7352 94.0321 15.9028C99.0785 12.4274 104.791 10.4279 109.6 11.5705C124.453 15.1173 130.738 48.8712 127.024 74.6747Z" fill="#ECD3EF"/>
<path d="M88.723 41.228C86.6045 38.2763 83.8194 36.1101 80.6059 34.4915C77.797 33.0632 74.6311 32.0635 71.2985 31.2779C66.99 30.2782 62.3959 29.6355 57.8017 29.0165C49.3037 27.8502 43.2813 27.0408 38.0682 28.3738C37.7112 28.4691 37.3541 28.5643 36.9971 28.6833C37.3065 28.6833 37.6398 28.6595 37.973 28.6595C41.0675 28.6357 44.3049 28.8261 47.5898 29.0165C50.9938 29.207 55.5403 29.5164 61.0866 31.2779C64.8715 32.4919 73.6789 35.277 78.4873 41.228C78.4873 41.228 78.4873 41.2518 78.5111 41.2518C84.5097 48.6548 78.1779 53.3442 77.9636 81.6946C77.9398 85.5033 77.7256 97.8575 74.3454 106.879C73.4409 109.283 72.3221 111.473 70.9177 113.187C70.513 113.663 70.1083 114.044 69.6799 114.425C66.2283 117.401 61.9674 118.853 57.2304 119.4C58.8967 119.543 60.5392 119.638 62.134 119.638C65.6094 119.686 68.8943 119.376 71.9174 118.567C74.8691 117.758 77.559 116.448 79.8917 114.425C82.772 111.949 84.6049 108.807 88.1755 81.6946C92.5554 48.4406 90.9368 44.3225 88.723 41.228Z" fill="#4E02C6"/>
<path d="M78.4877 41.2291C78.4877 41.2053 78.4877 41.2053 78.4877 41.2291C73.6317 35.2543 64.848 32.4692 61.0632 31.2552C55.5169 29.4937 50.9941 29.2081 47.5664 28.9938C44.2814 28.8034 41.0203 28.613 37.9496 28.6368C37.6163 28.6368 37.3069 28.6368 36.9736 28.6606C32.4271 28.7796 28.2614 29.4461 24.905 31.3742C21.0964 33.5642 17.502 37.8965 13.7648 74.6022C10.8369 103.381 12.1223 109.642 16.526 113.141C18.1209 114.426 21.6439 115.259 28.1186 116.545C29.6896 116.854 31.4273 117.187 33.3316 117.544C40.4252 118.877 45.2336 119.544 51.8749 119.615C53.7078 119.639 55.4693 119.568 57.2069 119.377C61.9439 118.854 66.2048 117.402 69.6564 114.402C70.0849 114.021 70.4895 113.641 70.8942 113.165C72.2986 111.451 73.4174 109.284 74.322 106.856C77.7021 97.8348 77.9164 85.4806 77.9402 81.6719C78.1544 53.2977 84.4863 48.6321 78.4877 41.2291Z" fill="#ECD3EF"/>
<path d="M89.2704 69.5324C88.4848 69.7704 87.4137 69.937 86.3425 69.5562C82.8909 68.4136 82.4863 63.2243 82.4625 62.6054C82.2244 58.773 84.224 54.0598 87.7469 53.0839C88.1278 52.9886 89.3418 52.6554 90.5558 53.1553C87.1518 54.2502 85.2475 58.8682 85.4856 62.6054C85.5094 63.2243 85.8902 68.3184 89.2704 69.5324Z" fill="#262B2C"/>
<path d="M93.6747 53.2034C92.4131 52.6322 91.1277 52.9892 90.7468 53.0844C90.6754 53.1082 90.604 53.132 90.5326 53.1558C87.1286 54.2508 85.2243 58.8688 85.4623 62.606C85.5099 63.2249 85.8908 68.3189 89.271 69.5329C89.2948 69.5329 89.3186 69.5567 89.3662 69.5567C91.5085 70.2709 93.5319 68.9855 93.6985 68.8902C95.817 67.5096 96.1503 64.9864 96.4121 62.9631C96.4835 62.487 97.4119 54.8935 93.6747 53.2034Z" fill="#ECD3EF"/>
<path d="M41.8291 72.5071L49.494 56.1776L56.4923 41.0859L59.4916 42.0857C59.4916 42.0857 48.8751 62.7475 48.5656 63.6045C48.2562 64.4614 43.3287 73.6259 43.3287 73.6259L41.8291 72.5071Z" fill="#4E02C6"/>
<path d="M41.0201 71.6982C41.0201 71.6982 32.7363 69.1273 31.5223 68.9845C30.3083 68.8417 20.1679 66.4375 20.1679 66.4375L19.0967 73.3406C19.0967 73.3406 33.9265 74.4594 35.4024 74.7213C36.8782 74.9831 41.8294 74.7213 41.8294 74.7213L41.0201 71.6982Z" fill="#F4F4F4"/>
<path d="M42.5438 69.579C42.282 69.579 41.0204 69.6742 40.1158 70.674C39.1637 71.7214 39.2351 73.0544 39.2827 73.6257C39.4255 75.53 40.1396 76.625 41.068 77.0297C42.52 77.6248 44.0911 76.3394 44.3053 76.1727C45.5907 75.1015 46.7095 72.864 45.686 71.1739C45.0195 70.0789 43.7102 69.5314 42.5438 69.579Z" fill="#FA0018"/>
<path d="M42.3057 74.0306L57.1593 92.5739L67.0617 104.738L68.1805 103.452L58.4685 91.4551L42.8293 73.0547L42.3057 74.0306Z" fill="#FA0018"/>
</svg>
 My Research'
      subtitle: ''
      text: |-
        I apply a range of Design Science, qualitative and quantitative methods to comprehensively investigate the role of artificial intelligence in organizations.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
