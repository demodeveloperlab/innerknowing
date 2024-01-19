---
title: "Contact"
date: 2020-08-16
draft: false
description: "How to install the Blowfish theme."
cascade:
  showDate: false
  showAuthor: false
  invertPagination: true
  showRelatedContent: false
---
## Contact

{{< rawhtml >}}

<div class="max-w-2xl mt-20 mx-auto text-center p-6 shadow-xl">
  <section class="mx-auto">
        <div class="items-center">
          <form   action="https://formspree.io/f/mbjnlzov"
                  method="POST">
            <div class="mb-6">
              <label for="name" class="form-label">
                Your Name <span style="color:orange">*</span>
              </label><br>
              <input
                id="name"
                name="name"
                class="form-input"
                placeholder=""
                type="text" />
            </div>
            <div class="mb-6">
              <label for="email" class="form-label">
                Your Email <span style="color:orange">*</span>
              </label><br>
              <input
                id="email"
                name="email"
                class="form-input"
                placeholder=""
                type="email" />
            </div>
            <div class="mb-6">
              <label for="message" class="form-label">
                Message <span style="color:orange">*</span>
              </label><br>
              <textarea
                id="message"
                name="message"
                class="form-input"
                placeholder="Message goes here..."
                rows="8"></textarea>
            </div>
            <button type="submit" class="bg-transparent hover:text-primary-500 prose dark:prose-invert font-semibold hover:text-white py-2 px-4 border border-primary-500 hover:border-transparent rounded-full">
             Submit
            </button>
          </form>
        </div>
 </section>
</div>

## Mailchimp

 <form
        action="{{ .mailchimp_form_action | safeURL }}"
        method="post"
        id="mc-embedded-subscribe-form"
        novalidate="novalidate">
        <div class="input-group w-75 mx-auto mb-3">
          <input
            type="email"
            name="EMAIL"
            placeholder="Email"
            class="form-control required email mce_inline_error"
            id="mce-EMAIL"
            aria-required="true"
            autocomplete="off"
            required />
          <button
            class="input-group-text"
            name="subscribe"
            id="mc-embedded-subscribe">
            Label
          </button>
        </div>
        <input
          type="hidden"
          name="EMAILTYPE"
          id="mce-EMAILTYPE-0"
          value="html" />
        <div style="position:absolute;left:-5000px" aria-hidden="true">
          <input type="text" name="{{ .name }}" tabindex="-1" />
        </div>
      </form>
      <div id="mce-responses" class="clear">
        <div
          class="response text-white"
          id="mce-error-response"
          style="display:none"></div>
        <div
          class="response text-white"
          id="mce-success-response"
          style="display:none"></div>
      </div>
      <script
        type="text/javascript"
        src="//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js"></script>
      <!-- /subscription form -->
<div class="max-w-full mt-20 mx-auto text center p-6 shadow-xl">
  <section>
<!-- Github -->
        <a target="_blank" class="m-1 rounded bg-neutral-300 p-1.5 text-neutral-700 hover:bg-primary-500 hover:text-neutral dark:bg-neutral-700 dark:text-neutral-300 dark:hover:bg-primary-400 dark:hover:text-neutral-800" href="" title="" aria-label=""></a>
<button
  type="button"
  data-te-ripple-init
  data-te-ripple-color="light"
  class="mr-2 inline-block shadow-xl">
<svg width="32px" height="32px" viewBox="0 -0.5 48 48" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <title>Github-color</title> <desc>Created with Sketch.</desc> <defs> </defs> <g id="Icons" stroke-width="0.00048000000000000007" fill="none" fill-rule="evenodd"> <g id="Color-" transform="translate(-700.000000, -560.000000)" fill="#3E75C3"> <path d="M723.9985,560 C710.746,560 700,570.787092 700,584.096644 C700,594.740671 706.876,603.77183 716.4145,606.958412 C717.6145,607.179786 718.0525,606.435849 718.0525,605.797328 C718.0525,605.225068 718.0315,603.710086 718.0195,601.699648 C711.343,603.155898 709.9345,598.469394 709.9345,598.469394 C708.844,595.686405 707.2705,594.94548 707.2705,594.94548 C705.091,593.450075 707.4355,593.480194 707.4355,593.480194 C709.843,593.650366 711.1105,595.963499 711.1105,595.963499 C713.2525,599.645538 716.728,598.58234 718.096,597.964902 C718.3135,596.407754 718.9345,595.346062 719.62,594.743683 C714.2905,594.135281 708.688,592.069123 708.688,582.836167 C708.688,580.205279 709.6225,578.054788 711.1585,576.369634 C710.911,575.759726 710.0875,573.311058 711.3925,569.993458 C711.3925,569.993458 713.4085,569.345902 717.9925,572.46321 C719.908,571.928599 721.96,571.662047 724.0015,571.651505 C726.04,571.662047 728.0935,571.928599 730.0105,572.46321 C734.5915,569.345902 736.603,569.993458 736.603,569.993458 C737.9125,573.311058 737.089,575.759726 736.8415,576.369634 C738.3805,578.054788 739.309,580.205279 739.309,582.836167 C739.309,592.091712 733.6975,594.129257 728.3515,594.725612 C729.2125,595.469549 729.9805,596.939353 729.9805,599.18773 C729.9805,602.408949 729.9505,605.006706 729.9505,605.797328 C729.9505,606.441873 730.3825,607.191834 731.6005,606.9554 C741.13,603.762794 748,594.737659 748,584.096644 C748,570.787092 737.254,560 723.9985,560" id="Github"> </path> </g> </g> </g></svg>
</button>
<!-- Telegram -->
<button
  type="button"
  data-te-ripple-init
  data-te-ripple-color="light"
  class="mr-2 inline-block">
  <svg xmlns="http://www.w3.org/2000/svg" aria-label="Telegram" role="img" viewBox="0 0 512 512" width="32px" height="32px" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"><rect width="512" height="512" rx="15%" fill="#37aee2"></rect><path fill="#c8daea" d="M199 404c-11 0-10-4-13-14l-32-105 245-144"></path><path fill="#a9c9dd" d="M199 404c7 0 11-4 16-8l45-43-56-34"></path><path fill="#f6fbfe" d="M204 319l135 99c14 9 26 4 30-14l55-258c5-22-9-32-24-25L79 245c-21 8-21 21-4 26l83 26 190-121c9-5 17-3 11 4"></path></g></svg>
</button>
<!-- Archive.org -->
<button
  type="button"
  data-te-ripple-init
  data-te-ripple-color="light"
  class="mr-2 inline-block">
 <svg xmlns="http://www.w3.org/2000/svg" aria-label="Internet Archive" role="img" viewBox="0 0 512.00 512.00" width="32px" height="32px" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"><rect x="0" y="0" width="512.00" height="512.00" rx="0" fill="#ffffff" strokewidth="0"></rect></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"><rect width="512" height="512" rx="15%" fill="#ffffff"></rect><path d="m81 419h350v18h-350zm14-34h323v25h-323zm-2-284h321v35h-321zm319-10 10-11-169-39-168 39 10 11h158zm-273 154-1-51-3-47c0-2 0-2-2-2a67 67 0 0 0 -28 0c-1 0-2 0-2 2l-2 47a2223 2223 0 0 0 0 127l2 43 1 8 15 3c6-1 11-1 16-3l1-8 2-43a1616 1616 0 0 0 1-76zm88 0-2-51-2-47c0-2-1-2-2-2a67 67 0 0 0 -28 0c-2 0-2 0-2 2l-3 47a2223 2223 0 0 0 0 127l2 43 1 8c5 2 11 2 16 3l16-3v-8l2-43a1620 1620 0 0 0 2-76zm101 0-1-51-3-47c0-2 0-2-2-2a67 67 0 0 0 -28 0c-1 0-2 0-2 2l-2 47a2223 2223 0 0 0 0 127l2 43 1 8 15 3c5-1 11-1 16-3l1-8 2-43a1624 1624 0 0 0 1-76zm85 0-1-51-2-47c0-2-1-2-2-2a67 67 0 0 0 -29 0l-1 2-3 47a2227 2227 0 0 0 0 127l2 43 1 8c5 2 10 2 16 3l15-3 1-8 2-43a1620 1620 0 0 0 1-76z"></path></g></svg>
</button>
<!-- Email -->
<button
  type="button"
  data-te-ripple-init
  data-te-ripple-color="light"
  class="mr-2 inline-block">
 <svg height="32px" width="32px" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 512" xml:space="preserve" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <path style="fill:#FA6E51;" d="M512,256.006C512,397.402,397.394,512.004,256.004,512C114.606,512.004,0,397.402,0,256.006 C-0.007,114.61,114.606,0,256.004,0C397.394,0,512,114.614,512,256.006z"></path> <path style="fill:#E8573F;" d="M512,256.005c0-13.015-0.987-25.798-2.861-38.291c-0.14-0.138-0.272-0.282-0.417-0.417 c-0.367-0.394-0.742-0.769-1.136-1.136c-0.368-0.395-87.19-87.217-87.585-87.585c-4.134-4.437-9.981-7.258-16.511-7.258H108.51 c-12.481,0-22.633,10.148-22.633,22.629v224.103c0,6.529,2.82,12.373,7.258,16.507c0.368,0.395,0.743,0.771,1.139,1.139 c0.367,0.395,122.45,122.476,122.845,122.843c0.194,0.208,0.399,0.4,0.599,0.599c12.492,1.873,25.274,2.86,38.288,2.86 C397.394,512.004,512,397.401,512,256.005z"></path> <path style="fill:#F4F6F9;" d="M403.49,121.319H108.51c-12.481,0-22.633,10.148-22.633,22.629v224.104 c0,12.481,10.151,22.629,22.633,22.629h294.981c12.481,0,22.633-10.148,22.633-22.629V143.949 C426.123,131.468,415.971,121.319,403.49,121.319z M100.053,145.605l112.945,114.859L100.053,366.766V145.605z M265.76,274.061 c-5.466,5.302-14.038,5.302-19.399,0.117L109.995,135.497h292.011L265.76,274.061z M222.945,270.579l13.429,13.658 c5.486,5.316,12.523,7.982,19.58,7.982c7.095,0,14.211-2.692,19.791-8.099l10.074-10.244l115.459,102.63H110.4L222.945,270.579z M295.771,263.754l116.176-118.148v221.415L295.771,263.754z"></path> </g></svg>
</button>
<!-- Eventbrite -->
<button
  type="button"
  data-te-ripple-init
  data-te-ripple-color="light"
  class="mr-2 inline-block">
  <svg width="32px" height="32px" viewBox="0 0 256 256" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="xMidYMid" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <g> <circle fill="#F05537" cx="128" cy="128" r="128"> </circle> <path d="M117.475323,82.7290398 C136.772428,78.4407943 156.069532,86.3025777 166.790146,101.311437 L81.5017079,120.608542 C84.3605382,102.26438 98.1782181,87.0172853 117.475323,82.7290398 Z M167.266618,153.48509 C160.596014,163.252761 150.351872,170.161601 138.678314,172.782195 C119.38121,177.070441 99.8458692,169.208657 89.1252554,153.961562 L174.651929,134.664457 L188.469609,131.567391 L215.152026,125.611495 C214.91379,119.893834 214.199082,114.176173 213.007903,108.696749 C202.287289,62.7172275 155.354825,33.8906884 108.42236,44.6113021 C61.4898956,55.3319159 32.1868848,101.073201 43.1457344,147.290958 C54.1045839,193.508715 100.798813,222.097018 147.731277,211.376404 C175.366637,205.182272 196.807864,186.599875 207.766714,163.014525 L167.266618,153.48509 L167.266618,153.48509 Z" fill="#FFFFFF" fill-rule="nonzero"> </path> </g> </g></svg>
</button>
<!-- RSS -->
<button
  type="button"
  data-te-ripple-init
  data-te-ripple-color="light"
  class="inline-block">
  <svg xmlns="http://www.w3.org/2000/svg" aria-label="RSS" role="img" viewBox="0 0 512 512" width="32px" height="32px" fill="#000000"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"><rect width="512" height="512" rx="15%" fill="#f80"></rect><circle cx="145" cy="367" r="35" fill="#ffffff"></circle><path fill="none" stroke="#ffffff" stroke-width="60" d="M109 241c89 0 162 73 162 162m114 0c0-152-124-276-276-276"></path></g></svg>
</button>
</section>
</div>
{{< /rawhtml >}}

---