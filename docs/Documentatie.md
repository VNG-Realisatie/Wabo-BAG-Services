---
layout: page-with-side-nav
title: Documentatie Zaak- en Documentservices
folder_files:
  - title: Extra-elementen voor bg0310 WABO-Bag 1.04
    path: documenten\Extra-elementen_voor_bg0310_wbg104.zip
    group: 104
    versie: 1.04
    status: 
    omschrijving: 
  - title: Koppelvlakspecificatie Wabo Bag v1.04
    path: documenten\Koppelvlakspecificatie_Wabo_Bag_v1.04.pdf
    group: 104
    versie: 1.04
    status: 
    omschrijving: 
  - title: Koppelvlakspecificatie Wabo Bag v1.04 met renvooi
    path: documenten\Koppelvlakspecificatie_Wabo_Bag_v1.04_met_renvooi.pdf
    group: 104
    versie: 1.04
    status: 
    omschrijving: 
  - title: Onderhoudsverzoeken Wabo-BAG 1.04
    path: documenten\Onderhoudsverzoeken_Wabo-BAG_wbg104.zip
    group: 104
    versie: 1.04
    status: 
    omschrijving: 
  - title: Wabo - BAG v104
    path: documenten\Wabo-bag_v1.04.zip
    group: 104
    versie: 1.04
    status: 
    omschrijving: 
  - title: Koppelvlakspecificatie Wabo Bag met gemarkeerde wijzigingen v1.03
    path: documenten\Koppelvlakspecificatie_Wabo_Bag_met_gemarkeerde_wijzigingen_v1.03.pdf
    group: 103
    versie: 1.03
    status: 
    omschrijving: 
  - title: Koppelvlakspecificatie Wabo Bag v1.03
    path: documenten\Koppelvlakspecificatie_Wabo_Bag_v1.03.pdf
    group: 103
    versie: 1.03
    status: 
    omschrijving: 
  - title: Wabo-bag v1.03
    path: documenten\Wabo-bag_v1.03.zip
    group: 103
    versie: 1.03
    status: 
    omschrijving: 
  - title: Extra-elementen voor wbg0310 
    path: documenten\Extra-elementen_voor_wbg0310.xls.zip
    group: 100
    versie: 
    status: 
    omschrijving: 
  - title: Factsheet Wabo-Bag koppelvlak V1.0
    path: documenten\Factsheet_Wabo-Bag_koppelvlak_V1.0.pdf
    group: 100
    versie: 1.0
    status: 
    omschrijving: 
  - title: Koppelvlakspecificatie Wabo Bag v1.0 
    path: documenten\Koppelvlakspecificatie_Wabo_Bag_v1.0.pdf
    group: 100
    versie: 1.02
    status: 
    omschrijving: 
  - title: Proceshandreiking Wabo-BAG v1.0
    path: documenten\Proceshandreiking_Wabo-BAG_v1.0.pdf
    group: 100
    versie: 1.0
    status: 
    omschrijving: 
  - title: Testset Wabo Bag Services 1.0
    path: documenten\Testset_Wabo_Bag_Services_1.0_v1.1.zip
    group: 100
    versie: 1.1
    status: Onbekend
    omschrijving: 
  - title: Wabo-bag v1.0
    path: documenten\Wabo-bag_v1.0.zip
    group: 100
    versie: 1.0
    status: 
    omschrijving: 
---

# Documentatie

* Koppelvlakspecificatie Wabo-BAG services (inclusief bijlages)
* Schema's
* Compliancy testset Wabo-BAG services 1.0
* Voorbeeldberichten

## Wabo-BAG_services 1.04

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 104 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## Wabo-BAG_services 1.03

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 103 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## Wabo-BAG_services 1.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 100 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
