---
title: VPN site à site
publishDate: 2020-03-04 00:00:00
img: /assets/stock-3.jpg
img_alt: Pearls of silky soft white cotton, bubble up under vibrant lighting
description: |
  Mise en œuvre de VPN site à site.
tags:
  - Machines virtuelles
  - VPN
  - Chiffrement
---

Objectif :<br>
Créer un “tunnel” entre deux serveurs VPN afin que les clients de deux sites distants puissent se communique par ce réseau privé virtuel, Comme si ils étaient dans le même site géographique et d’une manière transparente.
Les données seront chiffrées et transitées dans ce réseau virtuel.

<img
					width="1553"
					height="873"
					src="/assets/siteasite.jpg"
					alt=""
				/>

 Ensuite faire évoluer l’infrastructure comme celle-ci-dessous :

Objectifs à atteindre :<br>
<p>
==> Le client1VPN obtient d’une IP délivrée par le serveurDHCP 10.1.0.99.<br>
==> Le client1VPN peut communiquer avec le réseau 10.0.0.0 surtout avec 10.2.0.2
<p>

<img
					width="1553"
					height="873"
					src="/assets/enhance.jpg"
					alt=""
				/>
