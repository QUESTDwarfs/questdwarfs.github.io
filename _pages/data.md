---
layout: about_logo
title: Data
permalink: /
subtitle: Quasars to Understand Environments around, and STar formation in, Dwarfs
---

<!-- remove to use the bootstrap buttons from the theme, but this looks cleaner, I think -->
<style>
a.btn {
          color: var(--global-text-color);
          border: 1px solid #000000;
          padding-left: 1rem;
          padding-right: 1rem;
          padding-top: 0.25rem;
          padding-bottom: 0.25rem;
          margin-left: 0;
          text-decoration: none;
          box-shadow: none;
          text-transform: none;

          &:hover {
            color: var(--global-theme-color);
            border-color: var(--global-theme-color);
            text-decoration: none;
            box-shadow: none;
          }
        }

</style>

The QUEST Dwarfs project extends existing samples of dwarf galaxies for which the CGM and broader physical and chemical characteristics of the galaxy have been probed. This sample encompasses dwarf galaxies over three decades in mass in a variety of environments, enabling exquisitely detailed, holistic study of the baryon cycle in low mass galaxies.

To cite QUEST Dwarfs data and/or results, please refer to our [Publications](https://questdwarfs.github.io/publications).


<!-- All code associated with this sample is available on [GitHub](https://github.com/QUESTDwarfs){:target="_blank"}. -->


<!-- **Our first release paper is out now on [arXiv](){:target="_blank}!** -->


Summary tables are available here:
<a href="/assets/catalogs/QUESTgalaxies_v1.csv" download="QUESTgalaxies_v1.csv" class="btn">Download Galaxy CSV</a> <a href="/assets/catalogs/QUESTsightlines_v1.csv" download="QUESTsightlines_v1_columnonly.csv" class="btn">Download Sightline CSV</a>


Explore the data further: <a href="https://questdwarfs.github.io/assets/html/quest_compare_spectra_full.html" class="btn">Compare Optical Spectra</a> <a href="https://questdwarfs.github.io/assets/html/quest_compare_abs.html" class="btn">Compare FUV Spectra</a>


&nbsp;

<!-- The answer for dynamic resizing -- works perfectly for iframe getting larger: https://stackoverflow.com/a/53286303 -->
<script type="text/javascript">
  function resizeIframe(iframe) {
    iframe.height = iframe.contentWindow.document.body.scrollHeight + "px";
    window.requestAnimationFrame(() => resizeIframe(iframe));
  }
</script>

<!-- May be the best option if it ends up working for browsers -- https://developer.mozilla.org/en-US/docs/Web/API/Window/requestResize -->

*Open table in new tab [here](https://questdwarfs.github.io/assets/html/galpropstable_expandable.html).*
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe src="/assets/html/galpropstable_expandable.html" frameborder='0' scrolling='no' width="800px"
        onload="resizeIframe(this)"></iframe>
    </div>
</div>

<!-- Will just live with the white space at the bottom for now... maybe I'll figure out the on click stuff at some point. -->




