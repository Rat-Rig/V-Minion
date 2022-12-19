---
title: BOM
hide:
  - navigation
---

# Bill of Materials (BOM)

!!! warning "WARNING: Regarding the Raspberry Pi shortage"

    The V-Minion requires a Raspberry Pi if you wish to use RatOS. However, due to the worldwide semiconductor shortage, availability of these can vary on a day-to-day basis. The store pages for the V-Minion kits now include a customizable option allowing purchase of a Raspberry Pi if required, and if they are currently in stock.

    If the Raspberry Pi you wish to purchase is not currently in stock, the [:material-link-box-variant:Raspberry Pi Locator](https://rpilocator.com/){: target=_blank} website can be of great assistance in sourcing one in your country.

Below you can find the full bill of materials for the {{ ratrig.product_name }}.

{{ hardware_bom("bom/vminion_09122022_0939.csv") }}

### Printed parts
The entire set of printed parts can be downloaded in a [:material-download-box: single ZIP package]({{ config.repo_url }}/archive/main.zip)

Once extracted, the printed parts can be found in printed_parts inside the cad folder.

{{ printed_parts_bom("machine", "bom/machine.json") }}

{{ printed_parts_bom("electronics case", "bom/electronics_case.json") }}

### Printed electronics panels
The electronics enclosure panels are included in the full V-Minion kit. These printable parts are only required should you decide to purchase a mechanical kit and do not wish to have the panels produced yourself.

| Category | Name | QTY | Link |
| -------- | ---- | --- | ---- |
| electronics panel | panel_electronics_base | 1 | [:material-download: Download](https://github.com/Rat-Rig/V-Minion/tree/main/cad/panels/STL/panel_electronics_base_v1.0.stl){: target=_blank } |
| electronics panel | panel_electronics_board | 1 | [:material-download: Download](https://github.com/Rat-Rig/V-Minion/tree/main/cad/panels/STL/panel_electronics_board_v1.0.stl){: target=_blank } |
| electronics panel | panel_electronics_psu | 1 | [:material-download: Download](https://github.com/Rat-Rig/V-Minion/tree/main/cad/panels/STL/panel_electronics_psu_v1.0.stl){: target=_blank } |
| electronics panel | panel_electronics_top | 1 | [:material-download: Download](https://github.com/Rat-Rig/V-Minion/tree/main/cad/panels/STL/panel_electronics_top_v1.0.stl){: target=_blank } |

## EVA
<img align="right" alt="EVA Logo" width="100" src="/assets/eva_logo.png">
The latest developments of all EVA parts can be found at the EVA website here: https://main.eva-3d.page/

However, if you are looking for the version of EVA supplied by Rat Rig with the V-Minion, you can find those here: [:material-github: EVA 2.4.2 release](https://github.com/EVA-3D/eva-main/releases/tag/2.4.2)
