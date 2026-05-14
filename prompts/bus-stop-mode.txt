Generate a Taiwanese public-transit 「站牌／候車亭告示」style screen or page using Huaguo aesthetic + BUS STOP MODE.

Read and apply: rules/bus-stop-mode.md (density, hierarchy, patching).

Requirements:
- information hierarchy like physical signage: route numbers / headings first, cramped timetables and stop lists below
- table-heavy layouts: arrivals, fares, intervals, 「平日／假日／寒暑假」variants if relevant
- multiple stacked bordered panels mimicking pasted notices (交通局宣導、業者備註、改道施工中)
- strong warning strips (yellow/red) for 「末班異動」「天候影響」「施工改道」「防疫／安全宣導」 tone as appropriate
- small legal/service footnotes: complaints hotline、1999、QR placeholder、carrier names
- mixed typography scales: oversized route ID vs tiny footnotes vs dense station names
- allow 1–2px-ish visual unevenness between sections（different paddings/borders intentional）
- cyan/blue utility links vibe（像政府交通頁鏈結）okay if not over-modern

Avoid:
- global transit app minimalism（huge whitespace, dreamy maps, SaaS KPI cards）
- single clean hero storytelling
- pristine component uniformity across every block

Tone:
functional, crowded, 「好像印表機縮印貼上去的」 sincerity — still usable, not randomly broken UX.
