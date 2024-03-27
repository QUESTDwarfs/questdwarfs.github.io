---
layout: about
title: Data
permalink: /
subtitle: Quasars to Understand Environments and STar formation in/around Dwarfs
---

The QUEST Dwarfs project extends existing samples of dwarf galaxies for which the CGM and broader physical and chemical characteristics of the galaxy have been probed. This sample encompasses dwarf galaxies over three decades in mass in a variety of environments, enabling exquisitely detailed, holistic study of the baryon cycle in low mass galaxies.

To cite QUEST Dwarfs data and/or results, please refer to our [Publications](questdwarfs.github.io/publications) and reference [HST AR-17049](https://ui.adsabs.harvard.edu/abs/2022hst..prop17049P/abstract){:target="_blank"}.

All code associated with this sample is available on [GitHub](https://github.com/QUESTDwarfs){:target="_blank"}.

**QUEST Dwarfs DR1 is coming soon!**


<!-- load jQuery and tablesorter scripts -->
<script type="text/javascript" src="https://code.jquery.com/jquery-3.7.1.min.js"   integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo="   crossorigin="anonymous"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery.tablesorter/2.31.3/js/jquery.tablesorter.min.js"></script>

<!-- tablesorter widgets (optional) -->
<script type="text/javascript" src="/assets/js/jquery/jquery.tablesorter.widgets.js"></script>

<table id="myTable" class="tablesorter">
  <thead>
    <tr>
      <th>Name</th>
      <th>RA</th>
      <th>Dec</th>
      <th>log M<sub>star</sub>/M<sub>&#9737</sub></th>
      <th>Environment</th>
      <th>log sSFR/yr<sup>-1</sup></th>
      <th>N<sub>QSO</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sample Galaxy 1</td>
      <td>00:00:00/td>
      <td>+00:00:01</td>
      <td>9</td>
      <td>Isolated</td>
      <td>-11</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Sample Galaxy 1</td>
      <td>10:00:00/td>
      <td>-20:00:01</td>
      <td>7.5</td>
      <td>Group</td>
      <td>-10</td>
      <td>1</td>
    </tr>
  </tbody>
</table>

$(function() {
  $("#myTable").tablesorter();
});



