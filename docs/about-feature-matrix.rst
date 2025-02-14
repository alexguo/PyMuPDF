

.. required image embeds for HTML to reference


.. image:: images/icons/icon-pdf.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-svg.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-xps.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-cbz.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-mobi.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-epub.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-image.svg
          :width: 0
          :height: 0

.. image:: images/icons/icon-fb2.svg
          :width: 0
          :height: 0

.. raw:: html


    <style>

        table {
            border-style: hidden;
        }

        #feature-matrix th {
            border: 1px #999 solid;
            padding: 10px;
            background-color: #007aff;
            color: white;
        }

        #feature-matrix tr {

        }

        #feature-matrix td {
            border: 1px #999 solid;
            padding: 10px;
        }

        #feature-matrix tr td.yes {
            background-color: #83e57c !important;
            color: #000;
        }

        #feature-matrix tr td.yes::before {
            content: "✔︎ ";
        }

        #feature-matrix tr td.no {
            background-color: #e5887c !important;
            color: #000;
        }

        #feature-matrix tr td.no::before {
            content: "✕ ";
        }

        #feature-matrix tr td.limited {
            background-color: #e4c07b !important;
            color: #000;
        }

        #feature-matrix .icon-holder {
            line-height: 40px;
        }

        #feature-matrix .icon {
            text-indent: 45px;
            line-height: 40px;
            width: 100px;
            height: 40px;
        }

        #feature-matrix .icon.pdf {
            background: url("_images/icon-pdf.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.xps {
            background: url("_images/icon-xps.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.epub {
            background: url("_images/icon-epub.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.mobi {
            background: url("_images/icon-mobi.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.fb2 {
            background: url("_images/icon-fb2.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.cbz {
            background: url("_images/icon-cbz.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.svg {
            background: url("_images/icon-svg.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

        #feature-matrix .icon.image {
            background: url("_images/icon-image.svg") 0 0 transparent no-repeat;
            background-size: 40px 40px;
        }

    </style>


    <table id="feature-matrix" border="0" cellpadding="0" cellspacing="0">
        <tr>
            <th style="width:20%;" id="transFM1">Feature</th>
            <th style="width:20%;">PyMuPDF</th>
            <th style="width:20%;">pikepdf</th>
            <th style="width:20%;">PyPDF2</th>
            <th style="width:20%;">pdfrw</th>
        </tr>


        <tr id="PyMuPDFFileSupport">
            <td><cite id="transFM2">Supports Multiple Document Formats</cite></td>

            <td>
                <span class="icon pdf"><cite>PDF</cite></span>
                <span class="icon xps"><cite>XPS</cite></span>
                <span class="icon epub"><cite>EPUB</cite></span>
                <span class="icon mobi"><cite>MOBI</cite></span>
                <span class="icon fb2"><cite>FB2</cite></span>
                <span class="icon cbz"><cite>CBZ</cite></span>
                <span class="icon svg"><cite>SVG</cite></span>
                <span class="icon image"><cite id="transFM3">Image</cite></span>
            </td>
            <td>
                <span class="icon pdf"><cite>PDF</cite></span>
            </td>
            <td>
                <span class="icon pdf"><cite>PDF</cite></span>
            </td>
            <td>
                <span class="icon pdf"><cite>PDF</cite></span>
            </td>
        </tr>

        <tr>
            <td><cite id="transFM4">Implementation</cite></td>
            <td><cite>C</cite> <span id="transFM5">and</span> <cite>Python</cite></td>
            <td><cite>C++</cite> <span id="transFM6">and</span> <cite>Python</cite></td>
            <td><cite>Python</cite></td>
            <td><cite>Python</cite></td>
        </tr>

        <tr>
            <td><cite id="transFM7">Render Document Pages</cite></td>
            <td class="yes" id="transFM8">All document types</td>
            <td class="no" id="transFM9">No rendering</td>
            <td class="no" id="transFM10">No rendering</td>
            <td class="no" id="transFM11">No rendering</td>
        </tr>

        <tr>
            <td><cite id="transFM12">Extract Text</cite></td>
            <td class="yes" id="transFM13">All document types</td>
            <td class="no"></td>
            <td class="yes"><cite>PDF</cite> <span id="transFM14">only</span></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM15">Extract Vector Graphics</cite></td>
            <td class="yes" id="transFM16">All document types</td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM17">Draw Vector Graphics (PDF)</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM18">Based on Existing, Mature Library</cite></td>
            <td class="yes"><cite>MuPDF</cite></td>
            <td class="yes"><cite>QPDF</cite></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM19">Automatic Repair of Damaged PDFs</cite></td>
            <td class="yes"></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM20">Encrypted PDFs</cite></td>
            <td class="yes"></td>
            <td class="yes"></td>
            <td class="limited" id="transFM21">Limited</td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM22">Linerarized PDFs</cite></td>
            <td class="yes"></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM23">Incremental Updates</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM24">Integrates with Jupyter and IPython Notebooks</cite></td>
            <td class="yes"></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM25">Joining / Merging PDF with other Document Types</cite></td>
            <td class="yes" id="transFM26">All document types</td>
            <td class="yes"><cite>PDF</cite> <span id="transFM27">only</span> </td>
            <td class="yes"><cite>PDF</cite> <span id="transFM28">only</span> </td>
            <td class="yes"><cite>PDF</cite> <span id="transFM29">only</span> </td>
        </tr>

        <tr>
            <td><cite id="transFM30">OCR API for Seamless Integration with Tesseract</cite></td>
            <td class="yes" id="transFM31">All document types</td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM32">Integrated Checkpoint / Restart Feature (PDF)</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM33">PDF Optional Content</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM34">PDF Embedded Files</cite></td>
            <td class="yes"></td>
            <td class="yes"></td>
            <td class="limited" id="transFM35">Limited</td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM36">PDF Redactions</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM37">PDF Annotations</cite></td>
            <td class="yes" id="transFM38">Full</td>
            <td class="no"></td>
            <td class="limited" id="transFM39">Limited</td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM40">PDF Form Fields</cite></td>
            <td class="yes" id="transFM41">Create, read, update</td>
            <td class="no"></td>
            <td class="limited" id="transFM42">Limited, no creation</td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM43">PDF Page Labels</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>

        <tr>
            <td><cite id="transFM44">Support Font Sub-Setting</cite></td>
            <td class="yes"></td>
            <td class="no"></td>
            <td class="no"></td>
            <td class="no"></td>
        </tr>


    </table>

    <script>

        let lang = document.getElementsByTagName('html')[0].getAttribute('lang');

        function getTranslation(str) {
            if (lang == "ja") {
                if (str=="Feature") {
                    return "特徴";
                } else if (str=="Supports Multiple Document Formats") {
                    return "複数の文書形式に対応";
                } else if (str=="Image") {
                    return "画像";
                } else if (str=="Implementation") {
                    return "実装";
                } else if (str=="and") {
                    return "と";
                } else if (str=="Render Document Pages") {
                    return "文書ページの表示";
                } else if (str=="All document types") {
                    return "すべてのドキュメントタイプ";
                } else if (str=="No rendering") {
                    return "レンダリングなし";
                } else if (str=="Extract Text") {
                    return "テキストを抽出する";
                } else if (str=="only") {
                    return "のみ";
                } else if (str=="Extract Vector Graphics") {
                    return "ベクターグラフィックスを抽出する";
                } else if (str=="Draw Vector Graphics (PDF)") {
                    return "ベクターグラフィックスを描(PDF)";
                } else if (str=="Based on Existing, Mature Library") {
                    return "既存で成熟したライブラリに基づいています";
                } else if (str=="Automatic Repair of Damaged PDFs") {
                    return "PDFファイルの自動修復";
                } else if (str=="Encrypted PDFs") {
                    return "暗号化されたPDFファイル";
                } else if (str=="Limited") {
                    return "限られた";
                } else if (str=="Linerarized PDFs") {
                    return "リニアライズされたPDFファイル";
                } else if (str=="Incremental Updates") {
                    return "インクリメンタル更新";
                } else if (str=="Integrates with Jupyter and IPython Notebooks") {
                    return "JupyterおよびIPython Notebooksと統合";
                } else if (str=="Joining / Merging PDF with other Document Types") {
                    return "他のドキュメントタイプとPDFの結合 / マージ";
                } else if (str=="OCR API for Seamless Integration with Tesseract") {
                    return "Tesseractとのシームレスな統合のためのOCR API";
                } else if (str=="Integrated Checkpoint / Restart Feature (PDF)") {
                    return "統合されたチェックポイント / リスタート機能(PDF)";
                } else if (str=="PDF Optional Content") {
                    return "PDF オプションコンテンツ";
                } else if (str=="PDF Embedded Files") {
                    return "PDF 埋め込みファイル";
                } else if (str=="PDF Redactions") {
                    return "PDFの隠蔽";
                } else if (str=="PDF Annotations") {
                    return "PDFの注釈";
                } else if (str=="Full") {
                    return "すべて";
                } else if (str=="PDF Form Fields") {
                    return "PDFフォームフィールド";
                } else if (str=="Create, read, update") {
                    return "作成、読み取り、更新";
                } else if (str=="Limited, no creation") {
                    return "限定、作成不可";
                } else if (str=="PDF Page Labels") {
                    return "PDFページラベル";
                } else if (str=="Support Font Sub-Setting") {
                    return "フォントのサブセット化をサポートする";
                }


            }

            return str;
        }

        document.getElementById("transFM1").innerHTML = getTranslation("Feature");
        document.getElementById("transFM2").innerHTML = getTranslation("Supports Multiple Document Formats");
        document.getElementById("transFM3").innerHTML = getTranslation("Image");
        document.getElementById("transFM4").innerHTML = getTranslation("Implementation");
        document.getElementById("transFM5").innerHTML = getTranslation("and");
        document.getElementById("transFM6").innerHTML = getTranslation("and");
        document.getElementById("transFM7").innerHTML = getTranslation("Render Document Pages");
        document.getElementById("transFM8").innerHTML = getTranslation("All document types");
        document.getElementById("transFM9").innerHTML = getTranslation("No rendering");
        document.getElementById("transFM10").innerHTML = getTranslation("No rendering");
        document.getElementById("transFM11").innerHTML = getTranslation("No rendering");
        document.getElementById("transFM12").innerHTML = getTranslation("Extract Text");
        document.getElementById("transFM13").innerHTML = getTranslation("All document types");
        document.getElementById("transFM14").innerHTML = getTranslation("only");
        document.getElementById("transFM15").innerHTML = getTranslation("Extract Vector Graphics");
        document.getElementById("transFM16").innerHTML = getTranslation("All document types");
        document.getElementById("transFM17").innerHTML = getTranslation("Draw Vector Graphics (PDF)");
        document.getElementById("transFM18").innerHTML = getTranslation("Based on Existing, Mature Library");
        document.getElementById("transFM19").innerHTML = getTranslation("Automatic Repair of Damaged PDFs");
        document.getElementById("transFM20").innerHTML = getTranslation("Encrypted PDFs");
        document.getElementById("transFM21").innerHTML = getTranslation("Limited");
        document.getElementById("transFM22").innerHTML = getTranslation("Linerarized PDFs");
        document.getElementById("transFM23").innerHTML = getTranslation("Incremental Updates");
        document.getElementById("transFM24").innerHTML = getTranslation("Integrates with Jupyter and IPython Notebooks");
        document.getElementById("transFM25").innerHTML = getTranslation("Joining / Merging PDF with other Document Types");
        document.getElementById("transFM26").innerHTML = getTranslation("All document types");
        document.getElementById("transFM27").innerHTML = getTranslation("only");
        document.getElementById("transFM28").innerHTML = getTranslation("only");
        document.getElementById("transFM29").innerHTML = getTranslation("only");
        document.getElementById("transFM30").innerHTML = getTranslation("OCR API for Seamless Integration with Tesseract");
        document.getElementById("transFM31").innerHTML = getTranslation("All document types");
        document.getElementById("transFM32").innerHTML = getTranslation("Integrated Checkpoint / Restart Feature (PDF)");
        document.getElementById("transFM33").innerHTML = getTranslation("PDF Optional Content");
        document.getElementById("transFM34").innerHTML = getTranslation("PDF Embedded Files");
        document.getElementById("transFM35").innerHTML = getTranslation("Limited");
        document.getElementById("transFM36").innerHTML = getTranslation("PDF Redactions");
        document.getElementById("transFM37").innerHTML = getTranslation("PDF Annotations");
        document.getElementById("transFM38").innerHTML = getTranslation("Full");
        document.getElementById("transFM39").innerHTML = getTranslation("Limited");
        document.getElementById("transFM40").innerHTML = getTranslation("PDF Form Fields");
        document.getElementById("transFM41").innerHTML = getTranslation("Create, read, update");
        document.getElementById("transFM42").innerHTML = getTranslation("Limited, no creation");
        document.getElementById("transFM43").innerHTML = getTranslation("PDF Page Labels");
        document.getElementById("transFM44").innerHTML = getTranslation("Support Font Sub-Setting");


    </script>


    <br/>
