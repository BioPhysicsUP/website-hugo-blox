---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <style>
            .container {
                display: flex;
                align-items: center; /* Vertically centers the text next to the image */
                justify-content: center;
                flex-direction: row-reverse;
                max-width: 1400px;
            }
            .container img {
                max-width: 60%; /* Adjust the width as needed */
                height: auto
                margin-left: 25px; /* Space between the image and the text */
            }
            .container .text {
                font-size: 25px; /* Adjust the text size as needed */
                min-width: 40%; /* Adjust the width as needed */
                margin-right: 25px; /* Space between the image and the text */
            }
        @media (max-width: 600px) {
            .container {
                flex-direction: column; /* Stack items vertically */
                text-align: center; /* Center text horizontally */
            }
            .container img {
                margin-left: 0; /* Remove left margin for vertical layout */
                margin-bottom: 25px; /* Add bottom margin for spacing in vertical layout */
            }
            .container .text {
                order: -1; /* Move text above image */
            }
        }

        </style>
        <div class="container">
            <img src="group-photo.jpg" alt="Description of Image">
            <div class="text">
                Welcome to the Biophysics Research Group at the <a
                href="https://www.up.ac.za/">University of Pretoria</a>. 
                We are based in the <a href="https://www.up.ac.za/physics">Department of Physics</a> where we use laser spectroscopy to investigate photosynthesis.
            </div>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      title: Latest News
      subtitle:
      image:
        filename: group-photo.jpg
      text: |
        - Prof. Krüger went on a three-month sabbatical (October to December 2024) to the University of Bayreuth where he worked with Prof. Jürgen Köhler.
        - Towan, Bertus, Francois and Michael attended the [ICO Congress 2024](https://shorturl.at/7ntht) in Cape Town from 21 to 25 October.
        - Our [paper](https://doi-org.uplib.idm.oclc.org/10.1016/j.bpr.2024.100173) about
          our [SMS software](http://github.com/BioPhysicsUP/Full_SMS) was featured on the cover of *Biophysical Reports*!

        For more news, follow us on [X](https://x.com/TjaartKrueger), [LinkedIn](
        https://www.linkedin.com/company/biophysics-research-group-tuks/), or [Instagram](
        https://www.instagram.com/biophysics.up).
      
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'



---

