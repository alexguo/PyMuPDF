.. raw:: html

   <div class="feedbackLink"><a id="feedbackLinkBottom" target=_blank>Do you have any feedback on this page?</b></a></div>

----

.. raw:: html

   <script>

      var url_string = window.location.href;
      var a = document.getElementById('feedbackLinkBottom');
      a.setAttribute("href", "https://artifex.com/contributor/feedback.php?utm_source=rtd-pymupdf&utm_medium=rtd&utm_content=footer-link&url="+url_string);

      Prism.plugins.NormalizeWhitespace.setDefaults({
        'remove-trailing': true,
        'remove-indent': true,
        'left-trim': true,
        'right-trim': true,
        'break-lines': 100,
        'indent': 0,
        'remove-initial-line-feed': false,
        'tabs-to-spaces': 4,
        'spaces-to-tabs': 4
      });
   </script>

   <p style="color:#999" id="footerDisclaimer">This software is provided AS-IS with no warranty, either express or implied. This software is distributed under license and may not be copied, modified or distributed except as expressly authorized under the terms of that license. Refer to licensing information at <a href="https://www.artifex.com?utm_source=rtd-pymupdf&utm_medium=rtd&utm_content=footer-link">artifex.com</a> or contact Artifex Software Inc., 39 Mesa Street, Suite 108A, San Francisco CA 94129, United States for further information.</p>



   <script>

      let docLanguage = document.getElementsByTagName('html')[0].getAttribute('lang');

      function getHeaderAndFooterTranslation(str) {
          if (docLanguage == "ja") {
              if (str == "Do you have any feedback on this page?") {
                  return "このページに関するご意見はありますか？";
              } else if (str == "Find <b>#pymupdf</b> on <b>Discord</b>") {
                  return "<b>Discord</b>の <b>#pymupdf</b> を見つける";
              } else if (str == "This software is provided AS-IS with no warranty, either express or implied. This software is distributed under license and may not be copied, modified or distributed except as expressly authorized under the terms of that license. Refer to licensing information at <a href='https://www.artifex.com?utm_source=rtd-pymupdf&utm_medium=rtd&utm_content=footer-link'>artifex.com</a> or contact Artifex Software Inc., 39 Mesa Street, Suite 108A, San Francisco CA 94129, United States for further information.") {

                  return "このソフトウェアは無保証で提供されており、明示または黙示を問わず、いかなる保証もありません。このソフトウェアはライセンスの下で配布され、ライセンスの条件に明示的に許可されている場合を除き、コピー、変更、または配布してはなりません。ライセンシング情報については、<a href='https://www.artifex.com?utm_source=rtd-pymupdf&utm_medium=rtd&utm_content=footer-link'>artifex.com</a>でライセンス情報を参照するか、アメリカ合衆国カリフォルニア州サンフランシスコのアーティファクス・ソフトウェア株式会社（Artifex Software Inc.）までお問い合わせください。"
              }
          }

          return str;
      }

      document.getElementById("findOnDiscord").innerHTML = getHeaderAndFooterTranslation("Find <b>#pymupdf</b> on <b>Discord</b>");
      document.getElementById("feedbackLinkTop").innerHTML = getHeaderAndFooterTranslation("Do you have any feedback on this page?");
      document.getElementById("feedbackLinkBottom").innerHTML = getHeaderAndFooterTranslation("Do you have any feedback on this page?");
      document.getElementById("footerDisclaimer").innerHTML = getHeaderAndFooterTranslation("This software is provided AS-IS with no warranty, either express or implied. This software is distributed under license and may not be copied, modified or distributed except as expressly authorized under the terms of that license. Refer to licensing information at <a href='https://www.artifex.com?utm_source=rtd-pymupdf&utm_medium=rtd&utm_content=footer-link'>artifex.com</a> or contact Artifex Software Inc., 39 Mesa Street, Suite 108A, San Francisco CA 94129, United States for further information.");

   </script>




.. note - this ensures that the Sphinx build system will pull in the image (as it is referenced in an RST file) to _images,
   we don't want to display it via rst markup due to limitations (hence width:0), however we do want it available for our raw HTML
   which we use in header.rst.

.. image:: images/discord-mark-blue.svg
          :alt: Discord logo
          :width: 0
          :height: 0
          :target: https://discord.gg/TSpYGBW4eq
