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
        - Our [paper](https://doi-org.uplib.idm.oclc.org/10.1016/j.bpr.2024.100173) about
          our [SMS software](http://github.com/BioPhysicsUP/Full_SMS) has been published
          in *Biophysical Reports*.
        - Mamaru attended the [SASBMB Congress 2024](https://shorturl.at/fevx3) in Polokwane from 7 to 10 July.
        - Prof. Krüger and Francois attended [SAIP 2024](https://shorturl.at/SEihg) in Grahamstown from 1 to 5 July.
        - Bertus [attended](https://shorturl.at/L9OGs) two conferences: The [Lindau Nobel Laureate Meeting](
          https://www.mediatheque.lindau-nobel.org/meetings/2024
          ) and the European Photosynthesis Congress.
        - Leonato is on a [research visit](https://shorturl.at/kWgDN) to Friedrich Alexander University Erlangen-Nürnberg.
        - We had 4 graduates! Bertus (PhD), Francois (MSc), Emma (BSc Hons) and Sarah
          (BSc Hons).

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

