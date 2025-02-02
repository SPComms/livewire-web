---
title: "Podcast CDN Rankings by Episode Share (January 2022)"
description: "Ranked list of podcast CDNs (content delivery networks), based on number of new episodes published"
slug: "archive/podcast-cdns-by-episode-share-january-2022"
images:
- cdns-2022-01.png
date: 2022-02-10T20:10:00-06:00
lastmod: 2022-02-10T20:10:00-06:00
draft: false
---
*This is an archived version, the current version is [here](/podcast-cdns-by-episode-share/).*

In our third and final installment observing the current state of the podcast world, as measured by number of new episodes produced in January 2022, 
we wanted to take a look at which underlying CDNs serve which episodes, and which podcast hosting companies use which network.

*See our earlier analyses of [podcast hosts by episode share](/podcast-hosts-by-episode-share) and [podcast trackers by episode share](/podcast-trackers-by-episode-share)*

In general, every podcast episode has a single url that tells the podcast client app what to play.  However, this episode-level
url might redirect several times in the course a single download request, through various first and third-party trackers, before
ultimately landing at the internet host responsible for serving the audio file byte payload.  

This last entity in the chain is what we are interested in for this analysis.  Bandwidth costs are still non-trivial for hosting
providers, hence most of them use a third-party content delivery network (CDN) to minimize this cost, and also to provide lower-latency
global distribution.

---

We started with our universe of _every single new podcast episode published_ (about 1.6 million in January 2022), and mapped the
underlying host of the last entity in the request chain to a known CDN or network provider.  We were able to identify the underlying
network for 97.25% of the universe.

Below are the top 50 podcast content delivery networks ordered by share percentage of new episodes published during 
the month of January 2022.

If significant, we also list the top podcast hosting companies using each CDN, and the percentage of their own episodes allocated to the network.

---

### 1. [Amazon Cloudfront · 44.71%](https://aws.amazon.com/cloudfront/)

Amazon CloudFront is a content delivery network (CDN) operated by Amazon Web Services with over 275 edge locations on six continents.

For episodes that used Amazon Cloudfront, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://anchor.fm/" "Anchor" >}} {{< span "weak" "99%" >}}
2. {{< a "https://www.spreaker.com/" "Spreaker" >}} {{< span "weak" "100%" >}}
3. {{< a "https://soundcloud.com/stream" "Soundcloud" >}} {{< span "weak" "100%" >}}
4. {{< a "https://simplecast.com/" "Simplecast" >}} {{< span "weak" "100%" >}}
5. {{< a "https://rss.com/" "RSS Podcasting" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.acast.com/" "Acast" >}} {{< span "weak" "99%" >}}
7. {{< a "https://audioboom.com/" "Audioboom" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.blubrry.com/" "Blubrry" >}} {{< span "weak" "60%" >}}
9. {{< a "https://audiostart.jp/" "Audiostart" >}} {{< span "weak" "100%" >}}
10. {{< a "https://redcircle.com/" "RedCircle" >}} {{< span "weak" "100%" >}}
---

### 2. [Cloudflare · 13.59%](https://www.cloudflare.com/cdn/)

Cloudflare is an American web infrastructure and website security company that provides content delivery network (in over 250 cites in over 100 countries) and DDoS mitigation services. Cloudflare's services sit between a website's visitor and the customer's hosting provider, acting as a reverse proxy for websites.

For episodes that used Cloudflare, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.buzzsprout.com/" "Buzzsprout" >}} {{< span "weak" "100%" >}}
2. {{< a "https://transistor.fm/" "Transistor" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.sermonaudio.com/" "SermonAudio" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.podomatic.com/" "Podomatic" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.soundon.fm/" "SoundOn" >}} {{< span "weak" "83%" >}}
6. {{< a "https://castos.com/" "Castos" >}} {{< span "weak" "100%" >}}
7. {{< a "https://www.pinecast.com/" "Pinecast" >}} {{< span "weak" "99%" >}}
8. {{< a "https://fireside.fm/" "Fireside" >}} {{< span "weak" "100%" >}}
9. {{< a "https://www.podserve.fm/" "PodServe.fm" >}} {{< span "weak" "100%" >}}
---

### 3. [Highwinds · 9.07%](https://www.stackpath.com/highwinds)

Highwinds CDN was acquired by StackPath CDN, which is powered by over 45 edge locations around the world.

For episodes that used Highwinds, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.libsyn.com/" "Libsyn" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.megaphone.fm/" "Megaphone" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.captivate.fm/" "Captivate" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.oneplace.com/" "OnePlace.com" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.podcast.co/" "Podcast.co" >}} {{< span "weak" "100%" >}}
---

### 4. [OVH · 4.05%](https://www.ovh.com/world/)

OVH is a French cloud computing company which offers VPS, dedicated servers and other web services. As of 2016 OVH owned the world's largest data center in surface area.

For episodes that used OVH, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podbean.com/" "Podbean" >}} {{< span "weak" "79%" >}}
2. {{< a "https://www.rac1.cat/" "RAC1" >}} {{< span "weak" "100%" >}}
3. {{< a "https://zeno.fm/" "Zeno.FM" >}} {{< span "weak" "100%" >}}
4. {{< a "https://enacast.com/" "Enacast" >}} {{< span "weak" "100%" >}}
---

### 5. [Akamai · 3.56%](https://www.akamai.com/)

Akamai is a global content delivery network (CDN), cybersecurity, and cloud service company, providing web and Internet security services. Akamai's Intelligent Edge Platform is one of the world's largest distributed computing platforms.

For episodes that used Akamai, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.radiofrance.fr/" "Radio France" >}} {{< span "weak" "100%" >}}
2. {{< a "https://www.voanews.com/" "Voice of America English News" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.deutschlandradio.de/" "Deutschlandradio" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.npr.org/" "NPR" >}} {{< span "weak" "67%" >}}
5. {{< a "https://www.rferl.org/" "Radio Free Europe and Radio Liberty" >}} {{< span "weak" "100%" >}}
6. {{< a "https://www.bbc.co.uk/" "BBC" >}} {{< span "weak" "58%" >}}
7. {{< a "http://thecloudnetwork.com/" "the Cloud Network" >}} {{< span "weak" "88%" >}}
8. {{< a "http://www.abc.net.au/" "ABC Australia" >}} {{< span "weak" "100%" >}}
---

### 6. [CDN77 · 2.51%](https://www.cdn77.com/)

CDN77 provides a solid set of content delivery products and solutions all over the world, with 33 PoPs on 5 continents.

For episodes that used CDN77, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.ivoox.com/" "iVoox" >}} {{< span "weak" "98%" >}}
2. {{< a "https://www.podcastics.com/en/" "Podcastics" >}} {{< span "weak" "89%" >}}
3. {{< a "https://www.megafono.host/" "Megafono" >}} {{< span "weak" "100%" >}}
---

### 7. [Hetzner · 1.86%](https://www.hetzner.com/)

Hetzner Online GmbH is an Internet hosting company and data center operator based in Gunzenhausen, Germany.

For episodes that used Hetzner, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.podigee.com/" "Podigee" >}} {{< span "weak" "99%" >}}
2. {{< a "https://iono.fm/" "iono.fm" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.podcaster.de/" "podcaster.de" >}} {{< span "weak" "100%" >}}
4. {{< a "https://kabbalahmedia.info/" "Kabbalah Media" >}} {{< span "weak" "100%" >}}
5. {{< a "https://hearthis.at/" "hearthis.at" >}} {{< span "weak" "100%" >}}
6. {{< a "https://letscast.fm/" "LetsCast.fm" >}} {{< span "weak" "100%" >}}
---

### 8. [Triton Digital · 1.85%](https://www.tritondigital.com/)

Triton Digital, formerly Triton Media Group, is a digital audio technology and advertising company based in Los Angeles.

---

### 9. [Fastly · 1.72%](https://www.fastly.com/products/cdn)

Fastly's CDN service follows the reverse proxy model, routing all website traffic through their own servers instead of providing a 'cdn.mydomain.com' address to store site-specific files. It then fetches content from the point of presence nearest to the location of the requesting user, out of nearly 60 worldwide.

For episodes that used Fastly, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://www.squarespace.com/" "Squarespace" >}} {{< span "weak" "100%" >}}
2. {{< a "http://www.art19.com/" "ART19" >}} {{< span "weak" "100%" >}}
3. {{< a "https://www.atresmedia.com/" "Atresmedia" >}} {{< span "weak" "100%" >}}
4. {{< a "https://www.rtp.pt/" "RTP" >}} {{< span "weak" "100%" >}}
5. {{< a "https://www.cope.es/" "COPE" >}} {{< span "weak" "100%" >}}
6. {{< a "https://github.com/" "GitHub" >}} {{< span "weak" "100%" >}}
7. {{< a "https://wistia.com/" "Wistia" >}} {{< span "weak" "100%" >}}
8. {{< a "https://www.jwplayer.com/" "JW Player" >}} {{< span "weak" "82%" >}}
9. {{< a "https://www.supportingcast.fm/" "Supporting Cast" >}} {{< span "weak" "100%" >}}
---

### 10. [Hivelocity · 1.58%](https://www.hivelocity.net/)

Hivelocity provides Dedicated Servers, Colocation and Cloud Hosting services to customers from over 130 countries since 2002. Hivelocity operates 31 data centers on 4 continents.

For episodes that used Hivelocity, here are the top underlying podcast hosts, and percentage of their own episodes allocated to this network:

1. {{< a "https://omnystudio.com/learn" "Omny Studio" >}} {{< span "weak" "32%" >}}
2. {{< a "https://www.tritondigital.com/" "Triton Digital" >}} {{< span "weak" "11%" >}}
3. {{< a "https://www.voxnest.com/" "Voxnest" >}} {{< span "weak" "52%" >}}
4. {{< a "https://spokenlayer.com/" "SpokenLayer" >}} {{< span "weak" "32%" >}}
5. {{< a "https://www.securenetsystems.net/" "Securenet Systems" >}} {{< span "weak" "68%" >}}
---

### 11-50.

11. {{< a "https://aws.amazon.com/s3/" "Amazon S3 · 1.10%" >}}
12. {{< a "https://archive.org/" "Internet Archive · 1.01%" >}}
13. {{< a "https://www.cogentco.com/en/" "Cogent · 0.97%" >}}
14. {{< a "https://netrack.ru/" "NETRACK Russia · 0.76%" >}}
15. {{< a "https://www.gtt.net/us-en" "GTT Communications · 0.63%" >}}
16. {{< a "https://www.edgecast.com/" "Edgecast · 0.59%" >}}
17. {{< a "https://cloud.google.com/" "Google Cloud · 0.58%" >}}
18. {{< a "https://www.alibabacloud.com/product/networking" "Alibaba Cloud CDN · 0.52%" >}}
19. {{< a "https://www.tatacommunications.com/" "Tata Communications · 0.49%" >}}
20. {{< a "https://aws.amazon.com/ec2/" "Amazon EC2 · 0.45%" >}}

<br>

21. {{< a "https://he.net/" "Hurricane Electric · 0.45%" >}}
22. {{< a "https://en.wikipedia.org/wiki/Endurance_International_Group" "Unified Layer · 0.44%" >}}
23. {{< a "https://en.wikipedia.org/wiki/Level_3_Communications" "Level 3 Communications · 0.41%" >}}
24. {{< a "https://empirestreaming.com/" "EmpireStreaming · 0.39%" >}}
25. {{< a "https://www.deft.com/" "Deft · 0.37%" >}}
26. {{< a "https://www.dreamhost.com/" "DreamHost · 0.20%" >}}
27. {{< a "https://cloud.ionos.com/" "IONOS Cloud · 0.19%" >}}
28. {{< a "https://www.infomaniak.com/en" "Infomaniak · 0.17%" >}}
29. {{< a "https://www.scaleway.com/en/" "Scaleway · 0.16%" >}}
30. {{< a "https://automattic.com/" "Automattic · 0.15%" >}}

<br>

31. {{< a "https://www.mediactive-network.net/" "Mediactive Network · 0.15%" >}}
32. {{< a "https://www.digitalocean.com/" "DigitalOcean · 0.15%" >}}
33. {{< a "https://wasabi.com/" "Wasabi · 0.14%" >}}
34. {{< a "https://www.godaddy.com/" "GoDaddy · 0.13%" >}}
35. {{< a "https://www.axians.fr/en/" "AXIANS · 0.13%" >}}
36. {{< a "https://www.spie-ics.com/nos-solutions/cloud/" "SPIE ICS · 0.12%" >}}
37. {{< a "https://www.master.cz/" "MasterDC · 0.11%" >}}
38. {{< a "http://www.avensys.net/" "Avensys Networks · 0.10%" >}}
39. {{< a "https://www.quantil.com/" "QUANTIL · 0.10%" >}}
40. {{< a "https://1gservers.com/" "1G Servers · 0.09%" >}}

<br>

41. {{< a "https://www.swan.sk/" "SWAN · 0.09%" >}}
42. {{< a "https://www.swisstxt.ch/de/" "SWISS TXT · 0.09%" >}}
43. {{< a "https://www.err.ee/" "Eesti Rahvusringhääling · 0.07%" >}}
44. {{< a "https://cloud.mts.ru/en/" "MTS Cloud · 0.07%" >}}
45. {{< a "https://www.rtvslo.si/" "RTV Slovenija · 0.07%" >}}
46. {{< a "https://www.gmo.jp/en/" "GMO Internet Group · 0.07%" >}}
47. {{< a "https://www.liquidweb.com/" "Liquid Web · 0.07%" >}}
48. {{< a "https://www.aruba.it/" "Aruba.it · 0.06%" >}}
49. {{< a "https://www.linode.com/" "Linode · 0.06%" >}}
50. {{< a "https://apa.at/about/apa-tech/" "APA Tech · 0.06%" >}}

---
Analysis by [John Spurlock](https://twitter.com/johnspurlock)

Thanks to the [Podcast Index](https://podcastindex.org/) for crawling every podcast, and giving us a signal of when 
to check for new episodes.

Also thanks to the [Open Podcast Analytics Working Group](https://github.com/opawg) for maintaining a list of media url patterns and analytics services patterns.
We've incorporated these patterns along with some of our own to come up with the host and analytics service identification and metadata for this ranking.

And thanks to folks working at various networks to help us identify each one as accurately as possible.

---
*Updated 2022-02-10, with data for the month of January 2022.*

*Updated 2022-01-10, with data for the month of December 2021.*

*Updated 2021-11-15, with data for the month of November 2021.*

*Updated 2021-11-15, with data for the month of October 2021.*

*Updated 2021-10-21: Was showing the top 20, now showing the top 50, added thanks about feedback from networks.*

---
Previous versions:
 - [Podcast Host Rankings by Episode Share (December 2021)](/archive/podcast-cdns-by-episode-share-december-2021/)
 - [Podcast Host Rankings by Episode Share (November 2021)](/archive/podcast-cdns-by-episode-share-november-2021/)
 - [Podcast Host Rankings by Episode Share (October 2021)](/archive/podcast-cdns-by-episode-share-october-2021/)
 - [Podcast Host Rankings by Episode Share (September 2021)](/archive/podcast-cdns-by-episode-share-september-2021/)

---
*[Modify](https://github.com/skymethod/livewire-web/blob/master/content/posts/archive/podcast-cdns-by-episode-share-2022-01.md) this page, [Discuss](https://github.com/skymethod/livewire-web/discussions) this page*
