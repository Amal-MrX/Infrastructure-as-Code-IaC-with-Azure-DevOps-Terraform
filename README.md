<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<svg width="1200" height="500" xmlns="http://www.w3.org/2000/svg">
  <style>
    .box { fill:#1e293b; stroke:#38bdf8; stroke-width:2; rx:10; ry:10; }
    .text { fill:white; font-family:Arial; font-size:14px; text-anchor:middle; }
    .arrow { stroke:#94a3b8; stroke-width:2; marker-end:url(#arrowhead); }
  </style>

  <defs>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="10" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#94a3b8"/>
    </marker>
  </defs>

  <!-- Boxes -->
  <rect class="box" x="20" y="200" width="180" height="80"/>
  <text class="text" x="110" y="240">Write Terraform</text>
  <text class="text" x="110" y="260">VS Code</text>

  <rect class="box" x="220" y="200" width="180" height="80"/>
  <text class="text" x="310" y="240">Push Code</text>
  <text class="text" x="310" y="260">Azure Repos</text>

  <rect class="box" x="420" y="180" width="200" height="120"/>
  <text class="text" x="520" y="210">Build Pipeline</text>
  <text class="text" x="520" y="235">terraform init</text>
  <text class="text" x="520" y="255">terraform validate</text>
  <text class="text" x="520" y="275">terraform plan</text>

  <rect class="box" x="660" y="180" width="200" height="120"/>
  <text class="text" x="760" y="210">Release Pipeline</text>
  <text class="text" x="760" y="235">terraform apply</text>

  <rect class="box" x="900" y="100" width="220" height="80"/>
  <text class="text" x="1010" y="140">Azure Storage</text>
  <text class="text" x="1010" y="160">Terraform State</text>

  <rect class="box" x="900" y="300" width="220" height="80"/>
  <text class="text" x="1010" y="340">Azure Policy</text>
  <text class="text" x="1010" y="360">Compliance</text>

  <!-- Arrows -->
  <line class="arrow" x1="200" y1="240" x2="220" y2="240"/>
  <line class="arrow" x1="400" y1="240" x2="420" y2="240"/>
  <line class="arrow" x1="620" y1="240" x2="660" y2="240"/>
  <line class="arrow" x1="860" y1="200" x2="900" y2="140"/>
  <line class="arrow" x1="860" y1="260" x2="900" y2="340"/>

</svg>
