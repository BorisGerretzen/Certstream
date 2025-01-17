﻿# Certstream

<div align="center">
  <img width="256" height="256" src="https://raw.githubusercontent.com/actually-akac/Certstream/master/Certstream/icon.png">
</div>

<div align="center">
  A C# library for processing newly issued SSL certificates in real time using the Certstream API. 
</div>

## Usage
This library can be downloaded as the package `Certstream`. The main class is `CertstreamClient`. 

https://www.nuget.org/packages/Certstream

## Features
- Connect to the Certstream server and receive certificates in real time
- Parse and process over 200 issued certificates per second
- Automatic reconnects
- Updates exposed through events

## Available methods
- void `Start`()
- void `Stop`()

## Available events
- EventHandler\<LeafCertificate> `CertificateIssued`

## Official Links
https://certstream.calidog.io/</br>
https://github.com/CaliDog/certstream-server</br>
https://certificate.transparency.dev/</br>

## Example
Under the `Example` folder you can find a demo application that works with the library.
```
Google Trust Services LLC issued a SSL certificate for bestbuiltcon.biz
cPanel, Inc. issued a SSL certificate for shreeramns.com
DigiCert, Inc. issued a SSL certificate for myaccounttool.sunwebgroup.com
Let's Encrypt issued a SSL certificate for *.degarage.ch
Cloudflare, Inc. issued a SSL certificate for *.charlottetownbutcherpei.ca
DigiCert, Inc. issued a SSL certificate for margarete-blarer.de
Amazon issued a SSL certificate for *.us-west-2.es.amazonaws.com
DigiCert, Inc. issued a SSL certificate for remote-helpdesk.addaxmotors.com
Let's Encrypt issued a SSL certificate for *.diogoantonio.autocode.gg
Cloudflare, Inc. issued a SSL certificate for *.popracanaho.tk
Cloudflare, Inc. issued a SSL certificate for *.weirogiljare.tk
Amazon issued a SSL certificate for *.ap-northeast-3.es.amazonaws.com
cPanel, Inc. issued a SSL certificate for sawanschoolsirsa.developerszone.in
Amazon issued a SSL certificate for *.us-east-2.es.amazonaws.com
cPanel, Inc. issued a SSL certificate for webdisk.davidictrade.org.za
Cloudflare, Inc. issued a SSL certificate for *.africantelevisiononline.com
Let's Encrypt issued a SSL certificate for *.e-davetiyem.com
Cloudflare, Inc. issued a SSL certificate for *.independentguide.net
cPanel, Inc. issued a SSL certificate for webdisk.indiyaa.in
Amazon issued a SSL certificate for 69f3d881-9deb-4a2b-a0f7-70558c2b43a1.forgeapps.ec2.aws.dev
Cloudflare, Inc. issued a SSL certificate for *.autocarose.tech
Let's Encrypt issued a SSL certificate for *.divichangelog.com
Let's Encrypt issued a SSL certificate for *.dream.opstella.in.th
Let's Encrypt issued a SSL certificate for *.dub200.autocode.gg
Cloudflare, Inc. issued a SSL certificate for *.yldsn.top
cPanel, Inc. issued a SSL certificate for runwal-thane.in
DigiCert Inc issued a SSL certificate for hanacloud.ondemand.com
Cloudflare, Inc. issued a SSL certificate for *.circhaufluticcar.tk
Actalis S.p.A. issued a SSL certificate for sanguedolcecostruzioni.it
Cloudflare, Inc. issued a SSL certificate for *.service-coio.coi-occitanie.workers.dev
Google Trust Services LLC issued a SSL certificate for coisearlamitkea.tk
DigiCert Inc issued a SSL certificate for burstableflexrunnerserver637915813880232072.postgres.database.azure.com
Amazon issued a SSL certificate for *.ds-2016.env.polar.com
Let's Encrypt issued a SSL certificate for *.daniels-fotoexzesse.de
Amazon issued a SSL certificate for alt.canary.s3.us-west-2.vpce.amazonaws.com
Amazon issued a SSL certificate for app.simplementeeeuu.com
Entrust, Inc. issued a SSL certificate for srm-ui-bat.sddc-35-85-252-30.vmwarevmc.com
Cloudflare, Inc. issued a SSL certificate for *.butlaticho.tk
Actalis S.p.A. issued a SSL certificate for *.sanguedolcecostruzioni.it
cPanel, Inc. issued a SSL certificate for upclosebolivia.blogcreator.pl
DigiCert Inc issued a SSL certificate for fq26-viber.getmewin.com
cPanel, Inc. issued a SSL certificate for thegoldensandresort.com
Amazon issued a SSL certificate for ax91.bridge.setu.co
Cloudflare, Inc. issued a SSL certificate for *.hhdsn.top
Cloudflare, Inc. issued a SSL certificate for *.v0f.org
Amazon issued a SSL certificate for *.canary0341a7c6a260.gim1a1.c3.kafka.eu-west-3.amazonaws.com
DigiCert Inc issued a SSL certificate for e1xl-viber.getmewin.com
Let's Encrypt issued a SSL certificate for *.desyth.autocode.gg
Google Trust Services LLC issued a SSL certificate for fcfycpuxph.sub1.ccm-breakit.certsbridge.com
```